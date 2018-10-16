---
layout: post
title: 如何搭建自己的博客
date: 2018-10-16 18:00
description: 如何搭建自己的博客 # Add post description (optional)
img: hello-world.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [博客搭建]
---

技术博客是程序员的标配，但据我所知绝大部分技术同学到现在仍然没有自己的技术博客。原因有很多，有的是懒的写，有的是怕写不好，还有的是一直想憋个大招，幻想做到完美再发出来，结果一直胎死腹中。但其实更多程序员是不知道如何去搭建一个博客，其实如今搭建一个个人技术博客非常简单，其中最简单搭建方式莫属使用 GitHub Pages + Jekyll 了，我的博客就是使用这种技术。

## 概述
建立自己的博客有什么好处：
* 把平时积累的知识记录下来，方便查看和使用
* 不受其他博客平台的限制
* 面试的时候可以装逼

## 准备工作
### Github
GitHub是一个利用Git进行版本控制、专门用于存放软件代码与内容的共享虚拟主机服务,很多人都把它称作程序员的同性交友网站,具体为啥这么叫我也不知道。
### GitHub Pages
Github Pages设计的初衷是为托管在GitHub上的项目提供介绍页面,开发者们可以通过GitHub Pages为他们的每一个项目创建一个用于介绍该项目的静态网站,不过由于他的空间免费而且稳定,因此用它搭建一个个人博客网站是再好不过了。
### Git
Git是一个开源的分布式版本控制系统,可以有效、高速的处理从很小到非常大的项目版本管理.它的作用和Svn类似,就是一个版本控制的工具,用它可以将我们写的代码提交到Github上。
### Jekyll
Jekyll是一个简单的免费的Blog生成工具,将纯文本转化为静态网站和博客;由于咱们的GitHub Pages生成的是静态页面,每次更新博客都需要手动更改HTML,这就使得每次写博客都变得很麻烦,而用了这个工具以后,它会根据预先设置好的格式来生成博客内容,你就无需关心html代码,只需要把重心放在博客的写作上。

## 快速构建一个博客
1、登录Github账号，如果没有就注册一个。
2、创建一个空的Git项目，项目命名为git_username.github.io,其中git_username是你github的用户名；
![github]({{site.baseurl}}/assets/img/2018-10-16/github.jpg)
3、在[Jekyllthemes](http://jekyllthemes.org/)上找一个自己喜欢的模板，下载到本地，改一改_config.yml中的配置 ，主要是url等；
![theme]({{site.baseurl}}/assets/img/2018-10-16/theme.jpg)
4、然后提交到自己新建的项目中；
5、在Github项目中的Settings中往下拉找到Github Pages，将Source修改为master，然后会出现一个链接，直接访问就可以了。
![setting]({{site.baseurl}}/assets/img/2018-10-16/setting.jpg)
![pages]({{site.baseurl}}/assets/img/2018-10-16/pages.jpg)
![blogs]({{site.baseurl}}/assets/img/2018-10-16/blogs.jpg)
