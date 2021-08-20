---
layout:     post
title:      ReactiveCocoa 进阶1
subtitle:   函数式编程框架 ReactiveCocoa 进阶1
date:       2017-01-06
author:     BY
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - iOS
    - ReactiveCocoa
    - 函数式编程
    - 开源框架
---
# 前言

>在[上篇文章](http://qiubaiying.github.io/2016/12/26/ReactiveCocoa-基础/)中介绍了**ReactiveCocoa**的基础知识,接下来我们来深入介绍**ReactiveCocoa**及其在**MVVM**中的用法。


![ReactiveCocoa进阶思维导图](https://ww3.sinaimg.cn/large/006y8lVagw1fbgye3re5xj30je0iomz8.jpg)
# 常见操作方法介绍


#### 操作须知

所有的信号（RACSignal）都可以进行操作处理，因为所有操作方法都定义在RACStream.h中，因此只要继承RACStream就有了操作处理方法。
#### 操作思想

运用的是Hook（钩子）思想，Hook是一种用于改变API(应用程序编程接口：方法)执行结果的技术.

Hook用处：截获API调用的技术。

有关Hook的知识可以看我的这篇博客[《Objective-C Runtime 的一些基本使用》](http://www.jianshu.com/p/ff114e69cc0a)中的 *更换代码的实现方法* 一节,

Hook原理：在每次调用一个API返回结果之前，先执行你自己的方法，改变结果的输出。

#### 操作方法
123




>最后附上GitHub：<https://github.com/qiubaiying/ReactiveCocoa_Demo>
