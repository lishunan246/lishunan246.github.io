---
layout: post
title:  "Websocket++ 使用"
date:   2016/3/5 
categories: C++
---

#Linux下编译
使用的具体发行版为Linux Mint 17.3 64位

安装scons

`sudo apt-get install scons`

安装boost

`sudo apt-get install libboost-all-dev`

安装ssl

`sudo apt-get install libssl-dev`

之后为build system配置环境变量,boost的安装方式不同，下面两个目录的位置也可能不同。

`export BOOST_INCLUDES = /usr/include/boost`

`export BOOST_LIBS = /usr/lib/x86_64-linux-gnu`

从github clone源码，在项目根目录下运行scons即可。
