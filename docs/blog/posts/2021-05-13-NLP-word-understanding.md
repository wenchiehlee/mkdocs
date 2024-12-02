---
title:  "NLP- Word Understanding"
date: 2021-05-13
draft: true
categories: [AI,Language Model]
tags: [NLP]
image: "https://lena-voita.github.io/resources/lectures/word_emb/analysis/king_example-min.png"
visit:
featured: true
authors: [wenchiehlee]
---

## Overview

<figure markdown="span">
  [![](https://www.plantuml.com/plantuml/svg/RP3FIWD138VlynGHRriAYWUl_LE4GgM55Y_Y8Sw4wT2TPCraNVVj7K5b4NCAlozV0baKGxMSE6JidBkoCsK2az4TBuaxLCnGwAqdzhHKbU5qJlx2L0hSkV8xSa2rv5E7R0SC8N64-mbUoSTFV7ipoT6RwD76bW07Af9f0dSKYSDAD93-V_KL_IMgz1pMqeg2ANAfYDXShTdpzKXjAqDK8dw1fbbkcyRDvx2XztrNlhhbTdzoinci9NUzaS9JAacuHd_aQk-GOu-Hu542jNLJzJPe20-YvB6OMn27xrz-0W00)](https://www.plantuml.com/plantuml/uml/RP3FIWD138VlynGHRriAYWUl_LE4GgM55Y_Y8Sw4wT2TPCraNVVj7K5b4NCAlozV0baKGxMSE6JidBkoCsK2az4TBuaxLCnGwAqdzhHKbU5qJlx2L0hSkV8xSa2rv5E7R0SC8N64-mbUoSTFV7ipoT6RwD76bW07Af9f0dSKYSDAD93-V_KL_IMgz1pMqeg2ANAfYDXShTdpzKXjAqDK8dw1fbbkcyRDvx2XztrNlhhbTdzoinci9NUzaS9JAacuHd_aQk-GOu-Hu542jNLJzJPe20-YvB6OMn27xrz-0W00)
  <figcaption>Figure 1 Lanaguage Model in AI</figcaption>
</figure>

[![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F4440537%2F9893aebfd4a94def4806612dc98eb2e1%2Fnlp.png?generation=1610797433251310&alt=media)](https://www.kaggle.com/getting-started/211797)

[![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F4440537%2Fa3a11ff3167936d62cfc8af32