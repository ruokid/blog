---
title: macOS的homebrew-v2ray配置
date: 2021-11-29 09:55:04
tags: MacBook,M1,macOS,Monterey
---

## 安装与配置
```shell
# 安装
brew install v2ray

# 以服务形式启动
brew services start v2ray
```

- M1版的brew安装目录都在/opt/homebrew，所以配置文件路径是/opt/homebrew/etc/v2ray/config.js
- 如需要自定义配置文件路径请编辑/opt/homebrew/opt/v2ray/homebrew.mxcl.v2ray.plist
- 修改配置后重启生效

## 网络配置
{% asset_img 1.jpg 图1 %}
{% asset_img 2.jpg 图2 %}
{% asset_img 3.jpg 图3 %}
