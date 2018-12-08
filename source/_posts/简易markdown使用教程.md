---
title: 简易markdown使用教程
date: 2018-12-08 15:56:11
tags: 
categories: 实用工具
---

# 标题一
## 标题二
**加粗**
*斜杠*
<u>下划线</u>
~~删除线~~

* * * 
>引用块

* 原点列表

1. 数字列表1
2. 数字列表2

* [ ] 任务

[链接](http:www.baidu.com)
我现在写了一个段落，并且想在这个段落的某一个地方[图片上传失败...(img/pacman.jpg)]引入一张图片


![author.JPG](pic/author.JPG)


```

```

```math
e^{i\pi} + 1 = 0
```


```mermaid
graph TD
A[模块A] -->|A1| B(模块B)
B --> C{判断条件C}
C -->|条件C1| D[模块D]
C -->|条件C2| E[模块E]
C -->|条件C3| F[模块F]
```

```mermaid
sequenceDiagram
A->>B: 是否已收到消息？
B->>C:hao 
B-->>A: 已收到消息
```

```
graph LR
	绘图 --> 导出图像
	导出图像 --> 上传服务器
	上传服务器 --> 文章插入
```


