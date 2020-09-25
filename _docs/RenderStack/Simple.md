---
title: 队列渲染 - 简单模式
category: RenderStack
order: 1
---

基于renderburst基础上进行开发的模块
可以渲染场景中所有或选中镜头（读取独立的分辨率，曝光）

> 以当前的渲染设置进行单帧渲染

![renderstack_simple](img/renderstack_simple.gif)

在偏好设置中可以设置自定义输出路径和输出格式化名字

#### 关于输出

若未开启自定义输出路径，则默认输出要blend文件相对目录下的以${文件名}_render命名的文件夹下