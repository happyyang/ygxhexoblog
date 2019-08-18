---
title: Netty 框架原理
date: 2019-08-18 16:12:07
comments: true
categories:
- Netty
- 网络框架
tags:
- Netty 框架原理 
---

# Netty 框架原理

## 概念
Netty 网络框架，基于Java NIO 并采用异步事件机制，并对于Linux系列，引入Tomcat的底层网络通讯包，来实现linux下的kqueue级别更高效的并发量。
所以大多数的分布式框架的通讯组件都基于Netty进行实现。

<!-- more -->