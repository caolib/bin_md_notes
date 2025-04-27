---
title: cursor重置使用次数
date: '2025-03-15 11:13:48'
updated: '2025-04-27 16:58:59'
tags:
  - cursor
categories:
  - tools
permalink: /post/cursor-reset-usage-times-dahdp.html
comments: true
toc: true
---



# cursor重置使用次数

# Cursor重置

cursor有一定的免费使用额度，在官网但肯定是不够我们~~白嫖~~使用的，github上有个项目[go-cursor-help][go-cursor-help]可以重置账号的使用次数（~~可以无限白嫖了😋~~ ，接下来讲讲怎么操作

## 1.删除账号

先进入[cursor][cursor]官网，点击右上角进入登录，然后进入账号设置，这里可以看到已经使用的次数（我已经重置过一次了

点击**Delete Account**删除账号

![image-20250315112903872](https://s2.loli.net/2025/03/15/UQZxu8t6MTFYCsj.png)

## 2.重置cursor

来到项目的[说明文档][说明文档]复制对应平台的命令，我这里使用windows

```powershell
irm https://aizaozao.com/accelerate.php/https://raw.githubusercontent.com/yuaotian/go-cursor-help/refs/heads/master/scripts/run/cursor_win_id_modifier.ps1 | iex
```

![image-20250315113332101](https://s2.loli.net/2025/03/15/ONpXb3DqmVyk8ih.png)

打开一个powershell（管理员身份）控制台，粘贴运行就ok了

## 3.重新登录

重置完成后，重启cursor后重新注册登录账号就可以了

[go-cursor-help]:https://github.com/yuaotian/go-cursor-help

[cursor]:https://www.cursor.com/cn

[说明文档]:https://github.com/yuaotian/go-cursor-help?tab=readme-ov-file#-one-click-solution
