---
title:  "Raspberry PI with github actions runner"
date: 2024-07-15
draft: true
categories: [IOT]
image: https://earthly.dev/blog/assets/images/composite-actions-github/workflow.png
visit:
authors: [andylee-me,wenchiehlee]
---

## Overview

<figure markdown="span">
![QuickPOC](http://www.plantuml.com/plantuml/proxy?cache=no&fmt=svg&src=https://raw.githubusercontent.com/wenchiehlee/mkdocs/refs/heads/main/docs/blog/posts/QuickPOC.plantuml)
  <figcaption>Figure 1 DevOps with AI</figcaption>
</figure>

## Dashboard to overview the runners


<iframe width="540px" height="300px" src="https://docs.google.com/spreadsheets/d/1LtxS_ZH3dd5ycHIlkHENfWahl7QCVwYgoXJstf6HzQY/pubhtml?gid=0&amp;single=true&amp;widget=false&amp;headers=false"></iframe>

## Raspberry PI 5 to enable read/write google sheet

## Raspberry PI to get self-hosted runner status from github API
## Raspberry PI 5 to enable camera

```
sudo apt install -y python3-picamera2
sudo apt install -y python3-opencv
```

## Refrences
* [RaspberryPi+Github Actions+CI/CD](https://pabluc.medium.com/raspberrypi-github-actions-ci-cd-1dc098b4c7d3)
* [How we set up a production CI workflow with GitHub actions](https://insights.project-a.com/how-we-set-up-a-production-ci-workflow-with-github-actions/)
* [github awesome-raspberry-pi](https://github.com/thibmaek/awesome-raspberry-pi)
* [使用Python讀寫Google Sheet：輕鬆管理資料的步驟指南](https://medium.com/@yunnnzeng/%E4%BD%BF%E7%94%A8python%E8%AE%80%E5%AF%ABgoogle-sheet-%E8%BC%95%E9%AC%86%E7%AE%A1%E7%90%86%E8%B3%87%E6%96%99%E7%9A%84%E6%AD%A5%E9%A9%9F%E6%8C%87%E5%8D%97-5e029c2c4c3c)
* [Th3Fire/Temp-SpreadSheet](https://github.com/Th3Fire/Temp-SpreadSheet)
* [pygsheets - Using dotenv instead of json file](https://stackoverflow.com/questions/58643462/pygsheets-using-dotenv-instead-of-json-file)
* [Using secrets in GitHub Actions](https://docs.github.com/en/actions/security-for-github-actions/security-guides/using-secrets-in-github-actions?tool=webui)
* [IMX219-170 Camera](https://www.waveshare.com/wiki/IMX219-170_Camera)
