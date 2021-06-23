# imx6ull

#### 介绍
这里是正点原子imx6ull光盘资料中的文档。其他需要更新的资料请到http://www.openedv.com/docs/index.html 正点原子资料下载中心下载。

开发板介绍 
开发板资料介绍视频 B站哔哩哔哩链接： https://www.bilibili.com/video/av68994676

开发板QT5演示视频 B站哔哩哔哩链接： https://www.bilibili.com/video/av61255737

开发板QT5新版本超流畅桌面演示：https://www.bilibili.com/video/BV1M54y1677N

资料下载链接 
资料盘链接 
资料盘 开发板资料链接： https://pan.baidu.com/s/1inZtndgN-L3aVfoch2-sKA 提取码：m65i

资料盘 PDF合集资料链接： https://pan.baidu.com/s/1FSJY3PdFgV2WV4lT6Ps8fA 提取码：qsxb

资料盘 视频PPT笔记链接： https://pan.baidu.com/s/12C3yhpVuugtaHkhWjxfsSg 提取码：ho0m

视频网盘链接 
配套 Linux之Ubuntu入门篇 视频链接： https://pan.baidu.com/s/1GNdsA6lhPy15vahOYMMngw 提取码：80vf

配套 Linux之ARM裸机篇 视频链接： https://pan.baidu.com/s/1TjaQSuRZK0OiUCqc6S0SiQ 提取码：r27n

配套 Linux之系统移植和文件系统构建篇 视频链接： https://pan.baidu.com/s/1ZlhaCTsdBlYdSAWVtQH_sw 提取码：x2z8

配套 Linux之驱动开发篇 视频链接： https://pan.baidu.com/s/1JU95JHG-v7MKvkvXsMNhdw 提取码：n3ju


#### 使用说明

  **Linux驱动** ：

 应根据【正点原子】I.MX6U嵌入式Linux驱动开发指南V1.x.pdf搭建开发环境，可学习裸机，移植uboot、内核。编写驱动等。

 **Linux C应用** ：

 请使用【正点原子】I.MX6U嵌入式Linux C应用编程指南V1.x.pdf学习c应用编程。

 **Qt开发/学习者** ：

 请参考【正点原子】I.MX6U 出厂系统Qt交叉编译环境搭建V1.x.pdf直接在正点原子出厂系统上运行用户编写的Qt应用程序。使用【【正点原子】I.MX6U嵌入式Qt开发指南V1.0.pdf学习Qt应用编程。


  **Qt移植** ： 

 根据【正点原子】I.MX6U 移植Qt4.8.4 V1.x.pdf 、【正点原子】I.MX6U 移植Qt5.12.9 V1.x.pdf学习移植Qt。备注移植Qt不是必须的，在板子运行只需要搭建出厂系统的Qt交叉编译环境后，编译Qt应用程序，使用出厂系统运行Qt即可。

  **验证板子硬件** ：

 请参考【正点原子】I.MX6U用户快速体验V1.x.pdf。包括系统烧写，板子启动及上手操作（用户只需要有一点基础即可）。包括测试板子的性能及板子的资源使用方法。可学习到板子
 各种资源的用法。

  **Yocto** ：

 请【正点原子】I.MX6U 构建Yocto根文件系统V1.x.pdf 。但是不建议新手操作，构建Yocto，需要虚拟机硬件剩余120G以上容量。内存要大，至少分配10G以上内存给虚拟机。由于 
 Yocto项目需要连接国外网站，下载速度及编译时间等等都是一般人不能接受的！如果一个初学者有配置高的电脑，假若没有编译和下载出错，岂码至少要搞一个星期。

  **快速上手项目者** ：

这里指的是用经验的用户，建议参考【正点原子】I.MX6U用户快速体验V1.x.pdf，了解板子的资源（软件硬件），需要修改出厂系统的Logo请参考【正点原子】I.MX6U 修改开机进度条参考手册V1.x.pdf；需要分步更新出厂系统的固件请参考正点原子】I.MX6U 开发板文件拷贝及固件更新参考手册V1.x.pdf。

  **Debian文件系统** ：

需要使用Debian文件系统，请参考【正点原子】I.MX6U 移植Debian文件系统参考手册V1.x.pdf。但是这个Debian文件系统只能体验功能。一般产品都不会使用这个系统。用户可能会使用buildroot/busybox/yocto定制自己的根文件系统。

  **OpenCV移植** ：

请参考【正点原子】I.MX6U 移植OpenCV V1.x.pdf,目前只讲移植，关于如何使用请自行查找资料。

  **网络环境搭建** ：

一般用于调试内核，挂载文件系统。可参考正点原子】I.MX6U网络环境TFTP&NFS搭建手册V1.x.x.pdf。包括电脑直连开发板，或者局域网内连接设置。
 
  **遇到错误不会解决** ：

 请先在【正点原子】I.MX6U 常见问题汇总V1.1.pdf使用Ctrl + F用关键字查找。