# DDIA

# 第一部分：数据系统的基石

### 第一章：可靠性，可伸缩性，可维护性

数据主要提供读写能力，在面对不同的场景，应用可以按照，写放大，读放大的方式也提升系统的读写能力

* 可靠性（Reliability）（稳定性）：硬件故障（硬盘/内存/网络故障）、软件错误、人为失误（运维配置错误）
* 可扩展性（Scalability）：系统负载能力。描述负载（QPS，缓存命中率，活跃用户数量），描述性能（吞吐、TP、SLA），单机变为分布式部署提升系统承载能力。
* 可维护性（Maintainability）：平台监控、运营维护，设计的简单性和可扩展性来满足系统的一直变化。


### 第二章：数据模型与查询语言

