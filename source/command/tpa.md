---
title: 插件：TPA
date: 2020-12-23 19:27:30
tags:
  - Commands
  - Plugin
keywords: "Minecraft"
description: 插件命令
cover: /assets/resources/build_coral.png
copyright: true
---

{% btn 'https://dds.2to.fun/post/commands/', 返回, far fa-hand-point-right,outline green larger %}

## TPA
玩家之间相互传送插件。

插件开源地址 https://github.com/Da-Dog/MCDR-Plugins/tree/master/MCDR-tpa

### 用法帮助
| 语法 | 描述 |
| --- | --- |
|tpa|显示本条帮助信息|
|tap `player`|请求传送目标玩家|
|tpa deny|拒绝来自其他玩家的传送请求|
|tpa accept|接受来自其他玩家的请求|

### 说明
在目标或者本身已有传送事件发生的时候（包括请求阶段以及传送阶段），其他传送请求不被允许。

若想更换请求目标，请先根据需求输入`tpa cancel`取消上次传送事件。

> 举个栗子

![](/assets/resources/plugin-tpa.png)

