---
title: wcf简单入门教程
date: 2020-03-04 14:34:52
categories:
 - 编程
tags:
 - windows
 - .net
 - wcf
 - 教程
 - 敷衍zhd专用
cover: https://pic.idzd.top/usr/cover/cover_002.jpeg
---
>Windows Communication Foundation(WCF)是由微软开发的一系列支持数据通信的应用程序框架，可以翻译为Windows 通讯开发平台。

整合了原有的windows通讯的 .net Remoting，WebService，Socket的机制，并融合有 **HTTP** 和 **FTP** 的相关技术。

是Windows平台上开发分布式应用最佳的实践方式。

简单的归结为四大部分:
1. 网络服务的协议，即用什么网络协议开放客户端接入。
2. 业务服务的协议，即声明服务提供哪些业务。
3. 数据类型声明，即对客户端与服务器端通信的数据部分进行一致化。
4. 传输安全性相关的定义。

它是.NET框架的一部分，由 .NET Framework3.0 开始引入，与Windows Presentation Foundation及Windows Workflow Foundation并行为新一代 Windows操作系统以及 WinFX 的三个重大应用程序开发类库。

在 .NET Framework2.0 以及前版本中，微软发展了Web Service(SOAP with HTTP communication)，.NET Remoting (TCP/HTTP/Pipeline communication) 以及基础的 Winsock 等通信支持。

由于各个通信方法的设计方法不同，而且彼此之间也有相互的重叠性，对于开发人员来说，不同的选择会有不同的程序设计模型，而且必须要重新学习，让开发人员在使用中有许多不便。同时，面向服务架构(Service-Oriented Architecture) 也开始盛行于软件工业中，因此微软重新查看了这些通信方法，并设计了一个统一的程序开发模型，对于数据通信提供了最基本最有弹性的支持，这就是 Windows Communication Foundation。


------------

## WCF 简单教程

>访问：
> 1. [无废话WCF入门教程一](https://www.cnblogs.com/iamlilinfeng/archive/2012/09/25/2700049.html)
> 2. [WCF入门教程1](https://www.cnblogs.com/jiekzou/p/5325310.html)
> 3. [C# WCF简单入门图文教程(VS2010版)](https://www.jb51.net/article/81107.htm)
> 4. [WCF技术专题视频教程](https://pan.baidu.com/s/1mg6zQIG)