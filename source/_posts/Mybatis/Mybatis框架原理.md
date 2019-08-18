---
title: Mybatis 框架原理
date: 2019-08-18 16:43:23
comments: true
categories:
- ORM
- Mybatis
tags:
- Mybatis 框架原理
---

# Mybatis 框架原理

## 概述
Mybatis 框架采用母版模式，即将所有的功能都嵌入到Configuration中。Configuration就像一个模板，各个功能模块的交互也要通过
Configuration进行存储和交互代理获取。

<!-- more -->
