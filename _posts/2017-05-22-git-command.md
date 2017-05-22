---
layout: post
title: git 常用命令
---

 1.git clone <版本库的网址> <本地目录名>

 2.git add .添加当前工作目录文件到index

 3.git commit -m "<message>"  添加commit信息
	 
 4.git push  推送服务器

 5.删除版本库中的一个提交

	git reset --hard HEAD~1
	git push --force

 6.设置当前project的用户名和邮箱

	git config user.name 你的目标用户名
	git config user.email 你的目标邮箱名


