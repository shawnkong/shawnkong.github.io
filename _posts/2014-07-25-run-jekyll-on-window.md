---
layout: post
title: 如何在本地运行Jekyll
---

本地的Jekyll环境已经可以运行，折腾步骤大致如下:

##1.安装Ruby和Ruby DevKit

进入到你的Ruby DevKit目录，运行如下命令。

> ruby dk.rb init  
> ruby dk.rb install

##2.安装Jekyll Gem
  运行如下命令：
 
  > gem install jekyll

##3.运行Jekyll
  运行如下命令：
 
  >jekyll build    
  >jekyll serve --watch

  访问http://localhost:4000/即可。

  如果想发布内容，只需在_posts下加入你的内容文件即可，markdown和html格式都可以。

