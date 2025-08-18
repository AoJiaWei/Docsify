# Welcome.欢迎

IKUN_3058的Docsify网页（Ctrl+F打开搜索）

### Docsify部署网页

Docsify的官网：https://docsify.js.org/

Tips：使用GitHub新建库，并存储Docsify的文件，开启GitHub Pages功能实现随时访问。也可以用Cloudflare Workers中的Pages功能

所需工具：Typora（Markdown文件编辑工具）Node.js（使用NPM安装Docsify到Windows实现本地编写）

所需命令：

检查Node.js是否正确安装：`node -v`

检查Npm是否正确安装：`npm -v`

安装Docsify：`npm i docsify-cli -g`

初始化Docsify：`docsify init ./docs`

本地预览网页：`docsify serve docs`

### vivo Y51刷机笔记

**开始之间先要区分A版和C版：**

**A版：Android5.0**

**C版：Android5.1**

1.解BL锁：重启到Fastboot，使用脚本**（注：需要安装Fastboot驱动）**

2.刷入TWRP：直接使用一键刷入脚本**（注：需要安装Fastboot驱动）**

3.获取刷机包：在[萤火虫资源站](https://www.yhcres.top/)查找（推荐MIUI,Flyme）

4.直接在TWRP刷入

5.格式化内部储存分区

6.重启

参考文献：https://www.mintimate.cn/2019/06/21/Y51/

### 各类PE系统官网

FirPE：https://firpe.cn/

微PE：https://www.wepe.com.cn/

Edgeless：https://home.edgeless.top/（低配版Win To Go）

### Ventoy启动工具

Ventoy可以引导多个U盘中的ISO文件，VHD虚拟磁盘文件等等，适合用作装系统等适用场景

Ventoy官网：https://www.ventoy.net/

Ventoy文档手册：https://www.ventoy.net/cn/doc_news.html

![](https://www.ventoy.net/static/img/screen/screen_bios2.png)

Ventoy 1.0.07 版本开始支持 Secure Boot (安全启动)

理论上开启这个选项之后，不管BIOS里面的安全启动是开启的还是关闭的，都可以正常启动。

当BIOS里的安全启动开启时，正常情况下首次启动会出现类似下面这样的界面

![](https://www.ventoy.net/static/img/mokmanager.png)

只需要向下面这样操作一遍即可

![](https://www.ventoy.net/static/img/secure_key.gif)

### 制作Windows To Go

Windows To Go（缩写WTG）：是微软官方提供的一种 Windows 安装形式，可以把完整的 Windows 系统部署到U盘或者移动硬盘上，在任何可以引导 Windows 的设备中启动。

当然，我们亲爱的砍刀部已经在2020年及以后的 Windows 版本中砍掉了这个功能，这个功能以后也不会得到什么更新。但这并不等于这个功能无法使用了

WTG对于U盘的要求比较大，4K读写要求大，普通的闪存盘可能不足以支撑WTG，推荐使用移动硬盘或者移动固态U盘

**制作方法**

推荐使用Windows 的LTSC版本，预装软件较少占用空间比全量Windows少

使用Rufus制作WTG

Rufus官网：https://rufus.ie/zh/

在软件中选择镜像，并选择Windows To Go安装，开始即可

![](https://free-img.400040.xyz/4/2025/08/18/68a2e1d7c67e5.png)

注：WTG系统虽然可以在任何可引导外置设备上启动，但部分驱动不可通用

### Windows仿Mac工具

1.仿MacOS的Dock与Finder：MyDockFinder

官网地址：https://www.mydockfinder.com/

Steam商店地址：https://store.steampowered.com/app/1787090/MyDockFinder/

GitHub地址：https://github.com/gaxCat/Mydockfinder/releases

软件展示图：

![](https://free-img.400040.xyz/4/2025/08/18/68a320cd878c1.png)

![](https://free-img.400040.xyz/4/2025/08/18/68a320ce0dd75.png)

![](https://free-img.400040.xyz/4/2025/08/18/68a320cc7398a.png)

![](https://free-img.400040.xyz/4/2025/08/18/68a320ccf131a.png)

![神奇动画效果](https://free-img.400040.xyz/4/2025/08/18/68a31fe7c136c.png)

![](https://free-img.400040.xyz/4/2025/08/18/68a31fe8186d2.png)

![](https://free-img.400040.xyz/4/2025/08/18/68a31fe87af95.png)

![](https://free-img.400040.xyz/4/2025/08/18/68a31fe94bdef.png)

2.空格键快速预览工具

QuickLook微软商店下载地址：https://apps.microsoft.com/detail/9NV4BS3L1H4S?hl=zh&gl=CN&ocid=pdpshare

安装成功后选中文件按下空格键快速预览

支持视频、音乐、PDF、TXT等

更多插件扩展下载：https://github.com/QL-Win/QuickLook/wiki/Available-Plugins

下载插件后选中插件，按下空格键安装插件即可

![](https://free-img.400040.xyz/4/2025/08/18/68a322ce2b451.png)

### Windows 11优化小工具

![](https://free-img.400040.xyz/4/2025/08/18/68a3236e3f85a.png)

Windows 11轻松设置B站：https://www.bilibili.com/opus/904672369138729017

### DIY爱好者的必备工具合集

![](https://www.tbtool.cn/rc_images/aboutimg.png)

**快捷查看详细配置+一堆工具**

官网：https://www.tbtool.cn/

### Windows快捷重装软件：EasyRC

**软件功能：**

- 系统重装
- 系统备份
- 在线重装
- 扩展工具

官网：https://firpe.cn/page-196



### 作者：IKUN_3058

![](https://free-img.400040.xyz/4/2025/08/18/68a2e35aebb2b.jpg)
