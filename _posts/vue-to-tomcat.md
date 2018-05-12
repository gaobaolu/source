---
title: 如何把vue.js发布到Tomcat下
date: 2018-05-06 19:58:37
tags: [前端技术]
---

如何把vue.js发布到Tomcat下

需要修改文件，vue项目目录下的config目录下

文件index.js

修改：
assetsPublicPath: '/',

为
assetsPublicPath: './',