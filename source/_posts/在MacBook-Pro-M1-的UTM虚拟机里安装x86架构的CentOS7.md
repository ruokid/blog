---
title: 在MacBook Pro(M1)的UTM虚拟机里安装x86架构的CentOS7
date: 2021-12-16 15:09:54
tags:
---

## 安装前的准备
MacBook Pro M1Pro芯片
macOS: Monterey 12.1
下载虚拟机：[UTM.dmg](https://github.com/utmapp/UTM/releases/download/v2.4.1/UTM.dmg)
下载镜像文件：[阿里镜像](https://mirrors.aliyun.com/centos/7/isos/x86_64/CentOS-7-x86_64-DVD-2009.iso)

## 开始安装
1.新建虚拟机
{% asset_img 1.jpg 图1：新建虚拟机 %}

2.初始化配置
{% asset_img 2.jpg 图2：初始化配置1 %}
{% asset_img 3.jpg 图3：初始化配置2 %}

3.CentOS安装配置
略……

PS: 安装完成后会要求重启，这里可能会发生报错，直接关机把【驱动器】里的ISO删除再启动就可以了
