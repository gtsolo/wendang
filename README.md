# wendang

TVBox地址：https://github.com/liu673cn/box

TVBox下载
截止2023年1月31日，TVBoxOSC项目的更新版本是 20230129-2134

信用：takagen99
提交：5bfb7abb754ab6cf4fa98c50521a03619f5aa69f
变更日志：
实时 UI：清理代码 + SurfaceView 的解决方法修复

截止2023年1月19日，TVBoxOSC项目的更新版本是 20230106-2252

版本更新内容

Credit: takagen99
Commit: 038f48103a1dcc2a88a71a081fff2c59f2253e18
Changelog:
VOD UI – 添加 BACK 按钮（按钮仅在非电视上显示）
移除 Pyramid 支持
添加对 Android 4.4 的支持（测试）
添加在 Live UI 中更改 Live URL 的选项 > 偏好设置 > 直播列表

Home Pg: “TVBox” 可通过遥控器聚焦的文本
详细 Pg：更新系列列表动态宽度（ref amoylel）
设置 Pg：添加了实时 URL 历史记录
VOD 快进按钮
a.) 按向上/向下以增加/减少速度。
b.) x1.0时，长按到x5.0。再次长按到x1.0
免费电视盒子APP TVBox 安卓最新版本，免费观看全网影视TV点播！-1TVBox下载：

TVBox_takagen99_20230129-2134.apk
TVBox_takagen99_20230106-2252.apk
Github上的TVBoxOSC项目：https://github.com/o0HalfLife0o/TVBoxOSC

TVBox配置数据源接口大全：https://github.com/tv-player/TvBox

TVBox接口大全：TVBox接口 TVBox 下载最新版接口，亲测可用无广告速度快

TVBox安装
在Github的TVBoxOSC项目网站，下载最新版本的TVBox应用。

将TVBox APK文件下载完毕后，进行安装。

下面列举几种TVBox下载安装方法：
U盘安装TVBox

在PC端下载TVBox应用程序，并将其复制到您的 USB 驱动器中。
插在到电视上，直接通过安卓电视的文件管理器或者媒体管理器安装TVBox应用程序。
电视浏览器下载TVBox

使用安卓电视/盒子/投影仪自带的浏览器访问：https://github.com/o0HalfLife0o/TVBoxOSC/releases
从浏览器下载并安装最新版 TVBox APK。
Android 调试桥 (ADB)

您可以使用 Android 自己的 ADB 服务直接在您的 Android 电视/盒子上安装 TVBox APK 应用。
*查看 ADB 服务文档：https://developer.android.com/studio/command-line/adb

智能电视通过文件传输下载TVBox

您可以在 Google Play 商店（或您的电视的 APP 商店）中找到文件传输应用程序（如电视文件传输）
使用它们直接将 TVBox APK 应用从您的手机/PC 发送到您的 Android 电视。
点击查看如何在 小米电视上下载应用程序

TVBox应用安装完毕后，只是一个单纯的影视播放器，应用中没有任何可播放的影视内容。如果想播放电影，还需要进行设置，添加播放源。

免费电视盒子APP TVBox 全网电影TV点播免费看2

TVBox设置
上面已经成功的将TVBox应用安装在智能电视上了，此时还无法播放任何视频，点击电影海报也没有反应，对于小白用户来说，严重怀疑下载了一个垃圾应用。别急，下面让你感受TVBox的强大，用一句话形容，TVBox 一旦拥有，别无所求！

在TVBox主界面上，点击 设置 进入到TVBox设置界面中，核心的配置就是首页数据源，此时还没有数据源，所以点击首页数据源没有任何反应。

免费电视盒子APP TVBox 全网电影TV点播免费看3

TVBox 通过URL配置地址导入数据源
点击 配置地址 ，弹出配置窗口，使用电脑或者手机扫码访问TVBox的配置地址。

注意：你的电视上显示的是什么地址就访问什么地址，不要扫描下方图片的二维码，这只是一个测试机的虚拟IP地址。

免费电视盒子APP TVBox 全网电影TV点播免费看4

URL导入数据源
数据源接口是TVBox的核心所在，它是一个编译好的JSON文件或者是TXT文件，文件中包含了网络上各大影视站的影视爬虫，TVBox通过数据源接口文件可将影片加载至播放器中。

下面开始测试导入数据源，TVBox支持网络接口和本地文件，为了使用方便，通常是直接复制数据源接口网址，在配置地址中粘贴在配置地址处。

免费电视盒子APP TVBox 全网电影TV点播免费看5

首先开启一下存储权限，通过URL方式导入，在电视上输入比较麻烦，建议使用电脑配置或者是手机端进行配置。

粘贴好播放源之后，点击确认，然后返回首页，读取配置完毕后，就可以看到，TVBox左上角的播放源名称。

免费电视盒子APP TVBox 全网电影TV点播免费看6

可以通过相同的方式，导入更多的播放源！

在导入接口设置数据源后，TVBox就是一个功能强大的追剧神器，你可以查看目标站点资源的所有分类，包括其所有相关的影片。

TVBox提供了一个聚合模式，顾名思义，当你点入一个影片时，它会自动搜索聚合展示接口中所有站点相关的影视资源，这样方便你寻找更优质的片源。

免费电视盒子APP TVBox 全网电影TV点播免费看7

数据源接口导入成功后，在TVBox的首页上，点击 主页 ，在主页中可以选择首页数据源，每个数据源都不同，这里你可以多尝试几个数据源，选择你喜欢的就可以了。

免费电视盒子APP TVBox 全网电影TV点播免费看8

TVBox 通过浏览器导入数据源
电脑端在浏览器中输入IP地址，手机端扫码打开配置地址。

免费电视盒子APP TVBox 全网电影TV点播免费看9

将数据接口文件的路径，复制在自定义配置接口地址中，然后点击确认。然后在电视上的配置地址页面中就已经显示出配置接口地址了，点击确认即可导入。在使用浏览器配置接口的时候，一定要打开电视的存储权限。

TVBox 通过本地文件导入数据源
如果你担心数据源接口有一天会失效，其实大部分数据源接口都已经失效了，目前仅有少部分还可以使用，你可以将数据源接口文件保存在本地，然后将数据源接口文件上传到电视上就可以了。

TVBox 的直播功能
在导入数据源接口后，TVBox 的直播功能也是十分强大的，你可以在TVBox 中看到国内的电视直播频道。包括香港澳门的频道播放速度也很快。



使用USB安装TVBox
准备一个大于8G的U盘，将TVBox的安装程序下载到U盘中，插入电视，在媒体浏览器中打开U盘，选择TVBox的APK进行安装，安装之后不要拔出U盘，将U盘插在电视上，TVBox程序将在U盘上运行。TVBoxOSC可以在低版本的安卓电视上运行，其它的版本会闪退，不支持低版本的安卓电视。

关于TVBox数据源接口
仅限安卓系统和电视TV使用，在手机或者电视TV安装后， 依次点击：

设置>配置地址>复制下方任一接口>粘贴到配置地址处>点击确定>返回主页面

显示加载成功后即可使用！想更改成TVBox本地接口，只需将接口文件下载到本地，然后上传到电视上即可。

注意事项：

如电视TV安装软件出现闪退很可能因为系统版本过低或者不兼容导致，建议升级系统或者更换电视使用。
接口来源于网络，部分接口会不定期失效，失效后手动更换接口即可。
2022年11月2日网络上搜集了一些还有效的TVBox数据源接口，仅供测试使用。

TVBox接口：https://ghproxy.com/https://raw.githubusercontent.com/tv-player/tvbox-line/main/tv/fj.json
TVBox接口： https://ghproxy.com/https://raw.githubusercontent.com/ShadowDemon1997/CatVodSpiderJS/main/cfg.json
TVBox接口： https://ghproxy.com/https://raw.githubusercontent.com/chengxueli818913/maoTV/main/44.txt
TVBox接口： https://ghproxy.com/https://raw.githubusercontent.com/tv-player/tvbox-line/main/tv/xymc.json
TVBox接口： https://freed.yuanhsing.cf/TVBox/meowcf.json
TVBox接口： https://pastebin.com/raw/gtbKvnE1
TVBox接口： https://pastebin.com/raw/sbPpDm9G
TVBox接口： http://0454dt.com/tvbox
TVBox接口： https://raw.liucn.cc/box/m.json
更多tvbox接口请访问：TVBox接口 TVBox 最新版接口，亲测可用无广告速度快

TVBox下载 网盘备用下载地址：https://pan.quark.cn/s/697b59390e8d

TVBox下载 网盘备用地址2：https://pan.quark.cn/s/b48d439e262c

以上内容收集于互联网！

https://uzbox.com/tech/tvbox-jiekou.html
