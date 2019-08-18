---
title: SpringBoot 自动配置机制
date: 2019-08-18 16:48:41
comments: true
categories:
- SpringBoot
- 微服务
tags:
- SpringBoot 自动配置
---

# SpringBoot 自动配置机制

## 概述
SpringBoot 的理念即是【习惯优于配置】，所以在SpringBoot的Starter项目中，都进行了习惯配置，SpringBoot项目通过AutoConfig来实现对配置的读取，从而使
项目中的配置文件降到最少。

<!-- more -->

