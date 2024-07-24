---
title: VSCode与Keil协同嵌入式开发
author: alaye
date: 2024-07-23 20:20:43 +0800
categories: [Blogging, Tutorial]
tags: [Keil, VSCode, 嵌入式开发]
render_with_liquid: flase
---

## 先前条件

* 已经安装了*VSCode*和*Keil*
* 已经配置好*Keil*的`License`
* 可以使用Keil直接进行代码编辑和编译

*VSCode*和*Keil*的安装与基础配置，网络上已经有很多教程，可自行搜索，本篇教程不做介绍。

> VSCode：[下载地址](https://code.visualstudio.com/download)
> 
> Keil：[下载地址](https://www.keil.com/download/product/)
{: .prompt-tip }

## 安装和配置*VSCode*插件

1. 打开VSCode，点击`扩展`图标，搜索`Keil uVision Assistant`，安装该插件并启用。

![VSCode拓展搜索](/assets/img/posts/2024-07-23-vscode-and-keil-collaborative-embedded-development/VSCode拓展搜索.png)

> 这里搜索结果可能会出现两个名字类似的插件，这里做出解释：*Keil Assistant* 已于 Jun 13, 2021 归档转为只读。*Keil uVision Assistant* 是 *Keil Assistant* 的后续版本，由另外一个开发者 *jacksonjim* 负责继续更新及维护。 
{: .prompt-info }

2. 根据所开发的单片机芯片的架构和Keil的安装目录，完成插件的基础配置。