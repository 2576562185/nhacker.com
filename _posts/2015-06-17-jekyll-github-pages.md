---
layout: post
title: "jekyll+github pages搭建博客的一些容易迷惑的地方"
keywords: ["jekyll","github"]
description: "jekyll+github pages搭建博客的一些容易迷惑的地方"
category: "技术"
tags: ["github pages","jekyll"]
---
{% include JB/setup %}

  折腾了几天，终于将博客搭建起来了，下面写一下期间卡住比较耗时的地方。

##github pages的两种形式
　　github pages有两种，一种是个人的，每个帐号可以设置一个，一种是项目的，每个项目可以设置一个。
####个人
-  仓库名称必须是：用户名.github.io
-  分支必须是master，不要求设置成默认
-  访问地址为：http://用户名.github.io

####项目
-  仓库名称随意
-  分支必须是gh-pages，不要求设置成默认
-  访问地址为：http://用户名.github.com/仓库名

　　这个区别很多教程都没讲，直接选了一种就教，很让人迷惑。  
　　我选择的是第二种。  
　　绑定域名的话两者都是一样的方法，只要在CNAME文件里写上nhacker.com就行了，不知道加上www会产生什么影响。另外我估计如果多写几行有可能将多个域名解析过来，但是我只有一个域名，没法尝试。

##其实jekyll不需要安装
　　这个jekyll其实是不用安装在本地的，安装在本地的作用只是用来预览，或者用来运行一些额外的程序比如需要本地渲染的公式等，假如没有这些需求的话只要文件编辑好上传到github，或者直接到github上改，服务器会自动跑程序，过一会刷新就能看到效果。

  
##### 2015.06.17初具雏形，以后慢慢来吧，尽量少折腾，勿忘初心，好好写文。