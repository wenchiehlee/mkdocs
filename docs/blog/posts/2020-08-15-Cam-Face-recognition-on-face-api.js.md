---
title:  "Tensorflow.js POC 12: Cam Face-recognition on face-api.js"
date: 2020-06-23
categories: [AI,Computer Vision]
tags: [ Tensorflow, "Pre-trained Model", "Face Recognition", "Reinforcement Learning" ]
image: "/assets/images/16.07.2020_10.56.29_REC.png"
visit: "http://dlc.barco.com:3001/webcam_face_recognition"
authors: [wenchiehlee]
image: "https://pic1.xuehuaimg.com/proxy/csdn/https://img-blog.csdnimg.cn/20181106203614588.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MjQ1MjA3,size_16,color_FFFFFF,t_70"
visit: "http://dlc.barco.com:3001/webcam_face_recognition"
---
## Overview

<figure markdown="span">
[![](https://www.plantuml.com/plantuml/svg/RP1FIpj1343lyodoutURKb0yUEsV8XGgBRHu4Gzn9ao7xYHh9kkwtzujg2neJk6z1u4igg5QoHmBjixzipCL0fF17I-PMrGiKEcj8mwqL9N-TCxXmbGhtBdwannGBOVS8ji1OyoSu7wYL_BnZMzl9Xo3YHvjQ0Ymfog59d97YJYkH2FftrTVCLoIIiTnBOqec2BNKH6R6sVs_7-Wff4-AH6_WFVBhVTkFeSDlU_RUjsMs_t9pNwNQobjPwJmb6iMzdwCO8USEam4ZnAfkP8D6iA3A0MivXR4yUkLdm00)](https://www.plantuml.com/plantuml/uml/RP1FIpj1343lyodoutURKb0yUEsV8XGgBRHu4Gzn9ao7xYHh9kkwtzujg2neJk6z1u4igg5QoHmBjixzipCL0fF17I-PMrGiKEcj8mwqL9N-TCxXmbGhtBdwannGBOVS8ji1OyoSu7wYL_BnZMzl9Xo3YHvjQ0Ymfog59d97YJYkH2FftrTVCLoIIiTnBOqec2BNKH6R6sVs_7-Wff4-AH6_WFVBhVTkFeSDlU_RUjsMs_t9pNwNQobjPwJmb6iMzdwCO8USEam4ZnAfkP8D6iA3A0MivXR4yUkLdm00)
  <figcaption>Figure 1 Computer Vision in AI</figcaption>
</figure>

| Git Repo                                                                                                                                         | Status                                                                                                                                                                | Progress                                                                                                                    | Comments                                                     |
|--------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| [![face-api.js](https://img.shields.io/badge/face_api.js-gray?logo=tensorflow)](https://git.barco.com/users/wjlee/repos/face-api.js/browse/posenet) | [![status](https://tailab.barco.com:9443/deeplearningcomputing/face-api.js/badges/master/pipeline.svg)](https://tailab.barco.com:9443/deeplearningcomputing/face-api.js/pipelines) | [![progress](https://img.shields.io/badge/face_api.js-POC-red?logo=javascript)](http://dlc.barco.com:3001/webcam_face_recognition)|tensorflow.js POC #11, #12|

[![](https://rebrand.ly/dlc_png_url)](https://rebrand.ly/dlc_uml_url)

## What is reinforcement learning?

![](https://nervanasystems.github.io/coach/_images/design.png)

## Goals of POC #12

* Improve the POC #11 from semi-supervised learning to Reinforcement Learning by improve its face recognition rate

## References
* [Attention-aware deep reinforcement learning for video face recognition](https://www.twblogs.net/a/5bf329f7bd9eee04040aa388)

* [180204 Attention-aware Deep Reinforcement Learning for Video Face Recognition](https://www.slideshare.net/takanoriogata1121/180203-attentionaware-deep-reinforcement-learning-for-video-face-recognition)



