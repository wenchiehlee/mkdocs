---
title:  "Github runner in Synology NAS"
date: 2023-09-16
draft: true
categories: [DevOps]
tags: [Synology]
image: "https://kb.synology.com/_images/autogen/Quick_Start_Synology_Drive_admin/1.png"
visit:
authors: [wenchiehlee]
---

## Overview

<figure markdown="span">
![QuickPOC](http://www.plantuml.com/plantuml/proxy?cache=no&fmt=svg&src=https://raw.githubusercontent.com/wenchiehlee/mkdocs/refs/heads/main/docs/blog/posts/QuickPOC.plantuml)
  <figcaption>Figure 1 DevOps with AI</figcaption>
</figure> 

1. Create YAMl file as below (it is a org github runner)
2. In /volume1/docker/github-runner/data make sure remove .runner
3. Generate docker with the new YAML and restart

```yaml
version: '2.3'
services:
  worker:
    image: myoung34/github-runner:latest
    container_name: GITHUB-RUNNER
    restart: always
    environment:
      RUNNER_SCOPE: org
      ORG_NAME: xxx
      ACCESS_TOKEN: github_pat_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
      RUNNER_NAME: wenchiehlee.quickconnect.to
      RUNNER_WORKDIR: /tmp/runner/work
      RUNNER_GROUP: xxxx
      RUNNER_ALLOW_RUNASROOT: true
      DISABLE_AUTOMATIC_DEREGISTRATION: true
      CONFIGURED_ACTIONS_RUNNER_FILES_DIR: /actions-runner-data # Required for persistence
      LABELS: linux,x64,gpu,ubuntu-latest
    security_opt:
      # needed on SELinux systems to allow docker container to manage other docker containers
      - label:disable
    volumes:
      - /volume1/docker/docker.sock:/var/run/docker.sock
      - /volume1/docker/github-runner/tmp:/tmp:rw,Z
      - /volume1/docker/github-runner/data:/actions-runner-data:rw,Z # required for persistence
      - /volume1/web:/web:rw,Z
      - /volume1/docker:/docker:rw,Z
      - /volume1/homes:/homes:rw,Z
      # note: a quirk of docker-in-docker is that this path
      # needs to be the same path on host and inside the container,
      # docker mgmt cmds run outside of docker but expect the paths from within

```


## Refrences
* [Installing a Self-Hosted GitHub Actions Runner on Synology NAS](https://oleksandrkirichenko.com/blog/github-runner-on-synolo