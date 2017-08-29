# 《PyQt5快速开发与实战》

![](http://i.imgur.com/CQ37559.jpg)

为什么要编写本书？
=========
PyQt近年来发展很快，从最初的1998年的PyQt0.1，到PyQt1、PyQt2、PyQt3、PyQt4以及最新的PyQt5.9(截止到2017年8月9日)，然而非常不幸的是，市面上并没有一本真正指导新手学习PyQt5的教材，网络上针对PyQt5的学习案例的知识结构也都非常零碎，形成不了一个学习PyQt5的系统化框架。因此对于新手来说，想要快速接受PyQt5系统性的训练是一个非常困难的事情，2位笔者在最初学习PyQt5的时候也是吃尽了苦头，查阅了PyQt5与Qt5的大量官方文献资料并结合几年的实战应用之后，才敢说在PyQt5方面稍微有所建树，能够开发出自己想要的程序。

编程是一个孰能生巧的活儿，但是如果未来不使用这项技术，那么再过几年说不定就完全忘记PyQt5是如何使用的了，如果是这样的话就会给自己留下一些遗憾。本书考虑到现在个人还有一些额外的时间与精力，考虑到目前市面上还没有一本关于PyQt5使用的教材，经过两位作者近一年的不懈努力，于是才有本书现在的结果。


本书的结构
=========
使用的是最新版本的PyQt5.9，详细讲解了PyQt5的各个知识点，包含从入门到实战的所有例子。

本书共包含11个章节，这些章节基本包含了笔者在使用PyQt中遇到的绝大多数技术以及一些简单的应用。本书虽然有11个章节，但是有些章节是具有独立性的，读者可以针对自己的实际情况选择性阅读。

本书第一章介绍了PyQt的入门知识，讲述了PyQt的安装配置以及Eric6这个IDE的简单使用方法。对于对PyQt已经有一定基础的朋友可以略去这一章。

本书第二章简单介绍了Python的基本语法，本章针对一些没有接触过python的读者，对于Python已经有一些基础的朋友可以略去这一章。

本书第三章介绍Qt Designer的使用方法，Qt Designer是一个PyQt的可视化界面编辑程序，他的作用是帮助我们快速开发出界面文件，我们可以通过其他方式把界面文件转化成python代码文件。对于不懂太多PyQt知识的读者来说，本章可以让你快速入门，同时，本章也是让自己的PyQt技术快速进步的最重要的章节。

本书第四章介绍了PyQt的基本控件的使用方法，如果读者时间并不充裕，只对部分控件感兴趣，可以选取相应的小节进行阅读。

本书第五章介绍了PyQt的高级控件的使用方法，如果读者对PyQt的表格、树、多文本页面、数据库、多线程等等感兴趣，可以在这一章中选择相应的小节阅读。

本书第六章重新介绍了PyQt的布局管理的使用（之前在第3章通过Qt Designer的使用方法中已经介绍，第3章是通过Qt Designer这个代码生成器进行介绍，这里通过手工敲打代码的方法介绍）。由于布局管理非常重要，值得我们以一个新的章节介绍，如果读者对纯代码实现布局管理器感兴趣可以参考这一章，如果对代码生成器Qt Designer的布局管理器感兴趣也可以忽略这个章节。实际上两种方法并没有本质的区别。

本书第七章介绍了PyQt信号与槽的应用，信号与槽是PyQt的核心，想要掌握PyQt的高级玩法的朋友可以仔细阅读这个章节。

本书第八章介绍了PyQt的图形特效，如果读者对PyQt绘图，背景着色等感兴趣，可以阅读这个章节。

本书第九章介绍了PyQt的扩展应用，如果你想知道如何把Python的一些非常流行的模块如pyinstaller、pandas、matplotlib、pyqtgraph、plotly等与PyQt结合，可以从这一章节中选择性的阅读。

本书第十章通过几个例子介绍PyQt的实战应用，想要简单了解一些简单的程序是如何开发的朋友可以选择性的阅读这个章节。

本书第十一章介绍PyQt在金融领域中的应用，是本书的另一个作者孙洋在金融公司工作过程中积累的一些实战性较高的案例，向读者展示PyQt如何应用到投资研究系统、量化投资、以及金融工具开发，读者可以根据自己的需求选择性阅读。

本书的运行环境
===============
笔者在业余时间为本书封装了可以运行本书所有程序的绿色版的PyQt5环境，不会影响自己系统的默认环境，适合对python刚入门的新手或不想为本书重新折腾一个安装环境的老手。下载地址见网盘链接：http://pan.baidu.com/s/1i4Pp5VB 密码：u83w


**注意：**  
- 下载后需要解压到D盘根目录（必须是D盘，而且是根目录，否则eric不能运行）。
- 这个安装环境没有配置jupyter qtconsole，jupyter notebook，spyder，但是配置好了eric，读者可以使用eric跑通所有程序。
- eric打开的路径：d:\WinPyQt5.9-32bit-3.5.3.1\python-3.5.3\Scripts\eric6.bat

购买通道
=========
《PyQt5快速开发与实战》将于下个月（9月）在京东商城首发，读者可以发送邮件到邮箱(xpws2006@163.com)预定本书，也可以点击[这个链接](http://cn.mikecrm.com/3TMKe2y)填个非常简单的表格进行预订，到时有神秘好礼相送。
- 2017年8月24日已经通过稿件一排。


联系作者
=========
如果读者有任何问题，请发送电子邮件联系2位笔者，邮箱为xpws2006@163.com，邮件主题为“PyQt5代码”。也可以直接加入QQ的**PyQt5开发高级群(592588163)** 联系笔者，2位笔者白天都在群里。

路漫漫其修远兮，吾将上下而求索。在读者的不断求索中，能够与本书相遇也是一种缘分，如果读者能够从本书中获取自己想要的东西，那就是对笔者最大的欣慰。最后，提前预祝读者学习上轻松愉快、工作上更进一步、生活上幸福美满。
