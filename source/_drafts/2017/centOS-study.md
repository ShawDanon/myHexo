---
title: 'centOS学习笔记'
category: 技术
tags: 学习笔记
date: 2017-11-11
---

学习 centOS 的记录。

<!-- more -->

# 1

远程登录软件：PuTTY  
配置公网 ip，连接，输入登录名和密码（密码输入时看不见）。

[user@ctdog ~]$ command [-options] parameter1 parameter2

- user：当前用户名
- ctdog：当前计算机名
- ~：当前所在目录
- command：指令名，如：date
- \[-options\]：带'-'或'--'的指令，如：date --help
- parameter：参数，可以存在多个参数

# 2

双击 tab 键可以获取提示  
在所有的 Unix Like 系统当中，man command 可以查询指令或者相关文档的用法（command 代表指令，如：man date 就是查询 date 的用法）  
在 Linux 系统中，info command 可以查询指令或者相关文档的用法（command 代表指令，如：info date 就是查询 date 的用法）。它比 man 更易读。
