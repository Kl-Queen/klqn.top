---
title: 用Github Action免费获取像素绘画软件Aseprite
published: 2026-06-30
description: Aseprite其正版价值80元，普通学生很难负担得起。本文用一个Github项目实现编译Aseprite源代码，从而免费获取Aseprite
image: ./images/cover3.png
tags:
  - 教程
category: 教程
draft: false
lang: ""
---
:::tip
要使用Github Action，你必须拥有一个Github账号。
:::
你可以直接去[Kl-Queen/aseprite-builder](https://github.com/Kl-Queen/aseprite-builder/releases/tag/v1.3.17.2)下载我已经编译好的程序。如果你想自己编译最新版本的Aseprite，请看下文。
# 将Aseprite-builder Fork到自己仓库
打开[Aseprite-builder](https://github.com/a1393323447/aseprite-builder)项目，点击Fork
![[aseprite-fork.png]]
# 用Github Action编译源码
打开你刚刚Fork的仓库（不是原项目，是你Fork的自己的仓库）
![[aseprite-action.png]]
然后依次点击以下按钮：（如果你是Mac用户就点击Mac那个）
![[aseprite-final.png]]
最后点击Run workflow
差不多要编译十几分钟，然后去releases页面就能看到了。