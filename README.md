﻿[US English]
===================

[![](https://img.shields.io/badge/release-v3.1.0-blue.svg)](https://github.com/Tencent/tpo/releases/tag/v3.1.0) 	[![](https://img.shields.io/github/forks/Tencent/tpo.svg)]() [![](https://img.shields.io/github/stars/Tencent/tpo.svg)]()

New Android Release: tpo 3.1.0
------------------------------------------

What is tpo?
------------------------------------------
tpo (Great Tit) is a portable debugging tool for bug hunting and performance tuning on smartphones anytime and anywhere just as listening music with Walkman. tpo can act as the Integrated Debug Environment by directly running on smartphones.

With the help of tpo, you can carry out the following jobs only using one smartphone: quick performance tests (CPU, memory, flow, power, fluency tests etc.), viewing developer log and crash log, capturing the network packets, debugging the APP internal parameters and code time-consuming statistics.

If the functions tpo provides cannot meet your requirements, you can also develop your own tpo plugins with special functions to help solving more complicated debugging issues.



How to use?
------------------------------------------
tpo are supported on both IOS and Android platforms.

The IOS tpo is a Framework package, which must be compiled into your APPs before being used. It can be supported by both iPhone and iPad APPs.

The Android tpo is composed of one tpo console APP which can be installed directly and tpo SDK. tpo SDK must be embedded into the applications so that tpo console can display the information and modify the parameters.

If you have more questions, welcome to join our QQ group: 145535035/364740349(full)/546237347(full)/415036792(full) .Note: when applying to join the QQ group please attach the following information: tpo Communication


Source code description
------------------------------------------
The directory "android" is for Android tpo version.
The directory "ios" is for iOS tpo version.



[Simplified Chinese]
====================
Android tpo新版本发布：tpo 3.1.0
------------------------------------------

什么是tpo？
------------------------------------------

tpo（随身调）是APP的随身调试平台，它是直接运行在手机上的“集成调试环境”(IDTE, Integrated Debug Environment)。

利用tpo，仅凭一部手机，无需连接电脑，即可对APP进行快速的性能测试(CPU、内存、流量、电量、帧率/流畅度等等)、开发日志的查看、Crash日志查看、网络数据包的抓取、APP内部参数的调试、真机代码耗时统计等。

如果您觉得tpo提供的功能还不够满足您的需要，您还可以利用tpo提供的基础API自行开发有特殊功能的tpo插件，帮助您解决更加复杂的APP调试问题。


如何使用？
------------------------------------------
tpo支持iOS和Android两个手机平台，其中：

iOS版是一个Framework包，必须嵌入APP工程，编译出带tpo的APP才能使用；iPhone和iPad应用都能支持。

Android版由一个可直接安装的tpo控制台APP和tpo SDK组成，tpo控制台可以独立安装使用，SDK需嵌入被调试的应用、并利用tpo控制台进行信息展示和参数修改。

遇到问题请优先查阅网站上的faq，如无法解决请到Issues页提交问题。

使用交流请加QQ群：

145535035（请优先加此群）

364740349（已满）

415036792（已满）

546237347（已满）,

申请加入QQ群时请提供如下信息：交流tpo使用

源代码说明
------------------------------------------
android是Android版本tpo。
ios是iOS版本tpo。

相关开源工程
------------------------------------------
[tpoTools]工具包主要提供给基于AndroidJUnit的测试脚本用于性能指标的采集和数据监控。

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/stAore-comments-in-markdown-syntax)

[tpoTools]: <https://github.com/r551/tpoTools>
