---
title: 安装已不受支持的Windows Server 2008 R2
date: 2021-12-10 18:45:31
tags:
---

我平时移动办公比较多，很多时候没有网络去连接远程的服务器环境，所以在笔记本上安装了虚拟机运行着Windows Server环境。最新的操作系统对硬件要求是越来越高，我的笔记本虚拟机显然是带不动的，所以安装的还是能流畅运行的Windows Server 2008，但是2020年1月14日微软结束了对 Windows Server 2008[ R2] 的支持，虽然还是可以在网上找到iso来安装，但没有了自动更新之类的支持，最近换了新笔记本，重新安装了一下，遇到了以前没见过的问题，这里记录一下

这里推荐微软的一个站点，里面应该都是这些历史补丁下载
https://www.catalog.update.microsoft.com/

SP1补丁代号：KB976932

升级IE浏览器
https://docs.microsoft.com/zh-tw/troubleshoot/browsers/prerequisite-updates-for-ie-11
前置补丁：KB2729094, KB2731771, KB2670838, KB2786081, KB2834140
注意：Internet Explorer 11 桌面應用程式會在2022年6月15日淘汰

.NET 4.6 
已处理证书链,但是在不受信任提供程序信任的根证书中终止
MicrosoftRootCertificateAuthority2011.cer
时间戳签名和或证书无法验证或已损坏
KB2813430
32位系统补丁下载地址：https://www.microsoft.com/zh-CN/download/details.aspx?id=39110
64位系统补丁下载地址：https://www.microsoft.com/zh-CN/download/details.aspx?id=39115

由于缺少 d3dcompiler 更新，.NET Framework 4.7 安装在 Windows 7、Windows Server 2008 R2 和 Windows Server 2012 上被阻止
KB4019990
