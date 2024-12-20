---
title:  "High Availablity Deployment"
date: 2021-06-13
draft: true
categories: ["DevOps"]
image: "https://programmaticponderings.files.wordpress.com/2015/05/virtual-vehicles-architecture-4.png"
visit:
tags: [featured]
featured: true
author: [wjlee]
---

[![](https://miro.medium.com/max/3830/1*EGrGVCnU907tcT_Yj8H7UA.png)](https://medium.com/schkn/monitoring-a-server-cluster-using-grafana-and-influxdb-d5ff5f7151b2)

[![](https://miro.medium.com/max/2264/1*pOlAOFybINeAsvj_YgXijA.png)](https://medium.com/schkn/monitoring-a-server-cluster-using-grafana-and-influxdb-d5ff5f7151b2)

## HA InfluxDB in dlc/TDC 

[![](https://www.plantuml.com/plantuml/png/ZL9DZw904BtNhwZ8ZGICVUImCQl9PazxsTl4Gm4b4ejkfcbqZFhVfvMPE2BZS8Dw7wzUmRnnP5rR2JJRKjTagS9IExPhoXYFW9XIjYsiQNM-C68i7bZ4x2-0iJdRRcWiwOBX302kTCBuVxd0F_w9Kbpoxb_T0Dni9nldwYQPJZqhJibc9ivCDK5ga7LU6yzK0CA5VqFXjODJ65uSQsCTIHYUSD3XvEEzf1C2-4bjD6k7BuvAlyeAZtTJBvxTr1xjWoY6San9I6Uyma3AOkCAownX28--h7_k9pqB-Y5dT4nNy_jEV_LQshVbRmncgyTvP5deSCK6VTK8N_N4rsFUTgXH7CU_xhV3u5e_UMtP7d2CHjrh01vQOHH5lPXaRql78wZgazhdgl6swedju7SU_0anIANbPCjSavIx3-biz4MnEyyOaUgBpZ1ddRULl0C0)](http://www.plantuml.com/plantuml/uml/ZL9DZw904BtNhwZ8ZGICVUImCQl9PazxsTl4Gm4b4ejkfcbqZFhVfvMPE2BZS8Dw7wzUmRnnP5rR2JJRKjTagS9IExPhoXYFW9XIjYsiQNM-C68i7bZ4x2-0iJdRRcWiwOBX302kTCBuVxd0F_w9Kbpoxb_T0Dni9nldwYQPJZqhJibc9ivCDK5ga7LU6yzK0CA5VqFXjODJ65uSQsCTIHYUSD3XvEEzf1C2-4bjD6k7BuvAlyeAZtTJBvxTr1xjWoY6San9I6Uyma3AOkCAownX28--h7_k9pqB-Y5dT4nNy_jEV_LQshVbRmncgyTvP5deSCK6VTK8N_N4rsFUTgXH7CU_xhV3u5e_UMtP7d2CHjrh01vQOHH5lPXaRql78wZgazhdgl6swedju7SU_0anIANbPCjSavIx3-biz4MnEyyOaUgBpZ1ddRULl0C0)

## References
* [docker下用keepalived+Haproxy實現高可用負載均衡叢集](https://www.itread01.com/content/1544742732.html)
* [[Day5] 實現 Kubernetes 高可靠架構部署](https://ithelp.ithome.com.tw/articles/10218362)
* [HA InfluxDB as an external storage for Prometheus](https://docs.openstack.org/developer/performance-docs/methodologies/monitoring/influxha.html)
* [Monitoring a server cluster using Grafana and InfluxDB](https://medium.com/schkn/monitoring-a-server-cluster-using-grafana-and-influxdb-d5ff5f7151b2)
* [Installing InfluxDB with High Availability](http://blog.parallelo.ai/2020/10/28/installing-influxdb-with-high-availability/)
* [使用 Haproxy + Keepalived 構建基於 Docker 的高可用負載均衡服務](https://itw01.com/O9XREWB.html)
* [使用Influxdb-relay实现Influxdb高可用](https://izsk.me/2020/08/04/influx-single-transfer-to-relay/)          