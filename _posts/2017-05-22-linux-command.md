---
layout: post
title: linux 常用命令
---

1.tar -xf all.tar 解压tar压缩文件

2.tail -f /var/log/messages  查看文件内容， -f 实时读取最新的内容，例如查看日志：tail -f catalina.out

3.ps -ef|grep tomcat  查看tomcat进程

4.kill -9 [PID]  终止进程  -9表示强迫进程立即停止

5.创建文件夹：mkdir dirname

6.重启：reboot

7.查看文件内容：cat filename

8.编辑文件 vi i  编辑内容  esc :wq
