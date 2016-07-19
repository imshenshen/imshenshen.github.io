---
title: yo脚手架的生成器
subtitle: 一键生成Angular+bootstrap的带主题的admin后台项目
header-img: post-bg.jpg
tags:
  - javascript
  - 工程化
  - tools
header-img-color: 0
date: 2016-06-27 19:10:38
---


Angular群众基础还是很高的，在admin后台的场景下使用angular真是省时省力，所以做了一个绞脚手架工具，用来一键生成项目文件。

大概的页面是酱式儿的：
![pic](admin.png)
![pic](admin2.png)

目前最终生成的项目所用的工具包括`webpack`,`gulp`,`font-awsome`,`ui-bootstrap`等，
已经是个可用的东西了，不过还有好多**需要加上**的功能：
* ES6/Coffeescript支持
* 路由的Controller支持按需加载
* 加入directive/provider...等等模板（现在只有Controller - -！）

比较简单，没有publish到npm，使用方法在[这里](https://github.com/imshenshen/generator-angular-admin#usage)，后续慢慢完善吧，话说Angular2发布之后
还要支持`Typescript`，呃。。。
