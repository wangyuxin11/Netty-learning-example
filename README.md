# Netty-learning-example ![知识共享协议(CC协议)](https://img.shields.io/badge/License-Creative%20Commons-DC3D24.svg) ![](pic/LICENSE.png)
[![GitHub stars](https://img.shields.io/github/stars/sanshengshui/netty-learning-example.svg?style=social&label=Star)](https://github.com/sanshengshui/netty-learning-example/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/sanshengshui/netty-learning-example.svg?style=social&label=Fork)](https://github.com/sanshengshui/netty-learning-example/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/sanshengshui/netty-learning-example.svg?style=social&label=Watch)](https://github.com/sanshengshui/netty-learning-example/watchers)

## 前言:
**You built it,You run it!**

> **尚未完成，持续更新中...!**

备注: :wrench: :表示**施工中,尚未完成**;   :memo: :表示**已完成,但是没有写博文**; :ok_hand: 表示**已完成,并有相应的博文**;

![水平分割线](pic/horizon.png)

**什么是Netty?能做什么?**

- [Netty](https://netty.io/)是一个致力于创建高性能网络应用程序的成熟的IO框架

- 相比较与直接使用底层的Java IO API, 你不需要先成为网络专家就可以基于Netty去构建复杂的网络
  应用

- 业界常⻅的涉及到网络通信的相关中间件大部分基于Netty实现网络层,如下图所示:

  ![中间件](pic/Middleware.jpg)

本工程致力于netty实践学习案例,是netty初学者及核心技术巩固的最佳实践



## a.『 基础 - 入门篇 』


- :ok_hand: : netty-helloworld  <br>
  [《netty 之 telnet HelloWorld 详解》](https://www.cnblogs.com/sanshengshui/p/9726306.html)<br>



## b. 『 基础 - 通讯协议篇 』


- 👌 :netty-http<br>
  [《netty 之 高性能http服务器 详解》](https://www.cnblogs.com/sanshengshui/p/9774746.html)<br>


- 👌 netty-springboot-protobuf <br>
  [《netty 之 netty整合springboot并使用protobuf进行传输》](https://www.cnblogs.com/sanshengshui/p/9741655.html)<br>


-  👌 netty-mqtt

  1. [《Netty实现高性能IOT服务器(Groza)之手撕MQTT协议篇上》](https://www.cnblogs.com/sanshengshui/p/9826009.html)
  2. [《Netty实现高性能IOT服务器(Groza)之精尽代码篇中》](https://www.cnblogs.com/sanshengshui/p/9859030.html)


## c. 『 中级 - 数据流传输篇 』

- :wrench:: netty-jpa-mysql

  [《netty之jpa持久化数据至MySql》](https://github.com/sanshengshui/netty-learning-example/tree/master/netty-jpa-mysql)<br>

- :wrench:: netty-mybatis-mongodb

  [《netty之mybaits持久化数据之mongodb》](https://github.com/sanshengshui/netty-learning-example/tree/master/netty-mybatis-mongodb)<br>

- :wrench:: netty-kafka

  [《netty 之 netty 整合 Kafka producer》](https://github.com/sanshengshui/netty-learning-example/tree/master/netty-kafka)<br>

## d. 『 高级 - 高级应用篇 』

- :memo: : netty-IM<br>

  [《netty之用netty实现IM功能》](https://github.com/sanshengshui/netty-learning-example/tree/master/netty-im)<br>

- :wrench: :netty-Rpc<br>

  :herb: 由于RPC的工程案例实在是太多，感觉我手写一个也没什么乐趣。

  所以我挑选了蚂蚁金融服务集团实现的基于Netty网络通讯框架([SOFABolt](https://github.com/alipay/sofa-bolt))对其进行源码解读，

  展示给阅读此工程的开发者。:herb:

  1. [《简述RPC实现原理》](https://www.cnblogs.com/sanshengshui/p/9769517.html)<br>
  2. [《蚂蚁通讯框架SOFABolt之私有通讯协议设计》](https://www.cnblogs.com/sanshengshui/p/10149217.html)

- 👌 :netty-IOT

  1. [《IOT市场与高性能服务器实现之路》](https://www.cnblogs.com/sanshengshui/p/9797352.html)<br>

  2. [《Netty实现高性能IOT服务器(Groza)之手撕MQTT协议篇上》](https://www.cnblogs.com/sanshengshui/p/9826009.html)<br>

  3. [《Netty实现高性能IOT服务器(Groza)之精尽代码篇中》](https://www.cnblogs.com/sanshengshui/p/9859030.html)

     ------

     拓展实践: [软件工程师树莓派获取室内温湿度的坎坷之旅](https://www.cnblogs.com/sanshengshui/p/9942963.html)


## e. 『 高级 - Netty特性,源码篇 』

## f. 『 号外 - 相关知识归纳篇 』
- 👌 :语言指南(proto3)<br>
  [《Protobuf 语言指南(proto3)》](https://www.cnblogs.com/sanshengshui/p/9739521.html)<br>
- 👌 :测试工具篇(Gatling)<br>
  - [x] [负载,性能测试工具-Gatling](https://www.cnblogs.com/sanshengshui/p/9747069.html)
  - [x] [Gatling简单测试SpringBoot工程](https://www.cnblogs.com/sanshengshui/p/9750478.html)


Netty实现高性能的HTTP服务器
https://blog.csdn.net/qq_42606051/article/details/83026723
