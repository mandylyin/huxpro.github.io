---
layout:     post
title:      "从Tomcat到Spring（一）"
subtitle:   " \"环境搭建\""
date:       2018-08-25 10:00:00
author:     "平凡之路"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - Tomcat，Spring
---


## 前言

一直用Tomcat和Spring，但是两者具体是怎么结合运作起来的，却不是太清楚。本系列文章，作为学习Tomcat和Spring实现原理的总结，总结一下。先来从第一步搭建源码环境开始吧。

## Tomcat

Tomcat源码环境的搭建参考了[这篇博文](https://blog.csdn.net/linxdcn/article/details/72811928)。
我编译Tomcat所采用的环境：


- OS Win10


- Intellij IDEA 2017.2.5


- Java version 1.9.0.1


- Apache Maven 3.5.2


- Tomcat 9.0.11

## Spring

从[github-spring-framework](https://github.com/spring-projects/spring-framework)下载源码，参考[Build from source](https://github.com/spring-projects/spring-framework/wiki/Build-from-Source)来进行编译。