#Everything
##1.简介
仿照Everything桌面工具，基于Java语言开发的命令行文件搜索工具
##2.背景
有时候在Windows命令行下需要查询一些文件，由于`for`命令并不如Linux下的`find`命令好用，所以DIY开发一款命令行工具，用来实现Windows命令行中搜索文件。
##3.意义
+ 解决Windows命令行下文件搜索问题
+ 基于Java开发的工具可以在Windows和Linux平台上无差异使用
+ 锻炼编码能力
##4.功能
![](everything.PNG)
备注：不建议采用MySQL存储
##5.技术
+ Java(文件操作)
+ Database(嵌入式H2数据库或者MySQL数据库)
+ JDBC
+ Lombok库(IDEA安装Lombok插件)
+ Java多线程
+ 文件系统监控(Apache Commons IO)
##6.实现
