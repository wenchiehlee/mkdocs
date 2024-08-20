---
title:  "Gitlab-runner in Synology NAS"
date: 2023-09-16
draft: true
categories: [DevOps]
tags: [Synology]
image: "https://kb.synology.com/_images/autogen/Quick_Start_Synology_Drive_admin/1.png"
visit:
authors: [wjlee]
---

## Overview

[![](https://www.plantuml.com/plantuml/svg/RT31IWD1383X-pn5nDjAmUB1QxUAK11QQ6_Y8Sw4wR0xoPZ9kkxRkuZAWitn_mA1RAgXMauSCXRdF1PBml2Kug04Q-Ukx4oPm6HonovnGSKCbTu7Oa-jgeodS_8TKwrmv-hVoW7Laay5sGuOGk88zmlUokTlNjykEdeJFThK4-18LJ8jy9aYSTYA1jBBLz_GTr5buF0WlIYO8jUPYCtDS_DoFL7VonYLY5-XQTfTqxZLwbz_f8zzgTy6xMv_SXlYyFEcBm00)](https://www.plantuml.com/plantuml/uml/RT31IWD1383X-pn5nDjAmUB1QxUAK11QQ6_Y8Sw4wR0xoPZ9kkxRkuZAWitn_mA1RAgXMauSCXRdF1PBml2Kug04Q-Ukx4oPm6HonovnGSKCbTu7Oa-jgeodS_8TKwrmv-hVoW7Laay5sGuOGk88zmlUokTlNjykEdeJFThK4-18LJ8jy9aYSTYA1jBBLz_GTr5buF0WlIYO8jUPYCtDS_DoFL7VonYLY5-XQTfTqxZLwbz_f8zzgTy6xMv_SXlYyFEcBm00)

``` bash
# For files with "RSA" in the name
openssl rsa -in RSA-privkey.pem -out rsa.key

# For files with "ECC" in the name
openssl ec -in ECC-privkey.pem -out ecc.key

# For certificate files (regardless of type)
openssl x509 -in cert.pem -out cert.crt
```

## Refrences
* [Installing a Self-Hosted GitHub Actions Runner on Synology NAS](https://oleksandrkirichenko.com/blog/github-runner-on-synology/)
* [在 Synology NAS 上跑 gitlab-runner](https://viml.nchc.org.tw/archive_blog_759/)
* [Synology Gitlab 設定 HTTPS 連線](https://medium.com/@alex_cheng_9527/synology-gitlab-%E8%A8%AD%E5%AE%9A-https-%E9%80%A3%E7%B7%9A-376c2e933fd2)
* [SSL 基礎私有金鑰、CSR 、CRT 與 中繼憑證](https://haway.30cm.gg/ssl-key-csr-crt-pem/)
* [【網頁設計大解密】SSL 用的 Key, CRT, CA Bundle 中繼憑證到底是什麼？](https://simular.co/blog/post/75-crt-ca-bundle-%E5%88%B0%E5%BA%95%E6%98%AF%E4%BB%80%E9%BA%BC)