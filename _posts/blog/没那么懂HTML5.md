---
layout: post
title: HTML5：你可能没那么懂
categories: Blog
description: HTML5规范已经出来了一段时间，但其中的一些特性很多人可能并没有去关注。
keywords: HTML5
update: 2017-04-09
---

> 标题为“HTML5 你可能没那么懂”，不是说自己对HTML5有多了解，掌握有多深，而是记录一些自己刚了解的，可能常被我们忽略了的一些HTML5特性。仅此共勉。

## JavaScript的DOM操作
###  DOM节点选择效率
> getElementsByTagName比querySelectorAll方法快  

很多前端工作者可能根本不会直接使用到以上两个DOM操作API，习惯性的使用了 `jquery` 提供的`$()`操作符来获取节点。但看过jquery源码的童鞋应该知道，
`$()` 操作也是调用了原生API并在此基础上做了一些加工处理。关于 `jquery` `$` 操作这里不做说明，有兴趣的可以参考这篇文章。

在讲解之前，需要先了解一下一下概念：
* `HTMLCollection` 与 `NodeList` 的区别
`HTMLCollection` 与 `NodeList` 都是DOM节点集合，但他们两个能够包含的节点是有所不同的。  
HTMLCollection顾名思义，包含的节点必须是HTML元素，NodeList包含的是节点集合，只要是节点都可以，不一定是html元素。
举个例子：

## css相关规范

## 浏览器也有数据库
### indexDB
> HTML5规范中，定义了浏览器端数据库，indexDB，目前indexDB还没有被网站广泛的使用，但相信不久的将来
indexDB会和localStorage一样流行起来。

indexDB让浏览器端做存储成为了可能，indexDB采用noSql方式。特别是针对离线应用，indexDB能够最大程度的发挥其作用。
关于indexDB操作，可参考。

