---
title: 队列渲染 - 任务模式
category: RenderStack
order: 2
---

自定义渲染队列任务，渲染标记任务
+ 目前支持多任务静帧/动画混合渲染
+ 自定义渲染引擎（目前支持eevee 和 cycles），采样，视图层，输出格式，相机（包含独立属性），灯光工作室等

**自动更新按钮**

点击后，在每次更改任务参数时，都会实时刷新渲染画面，从而能轻松观察到最终结果

![rendertask1](../../uploads/rendertask1.gif)

#### 关于输出

若未开启自定义输出路径，则默认输出要blend文件相对目录下的以${文件名}_render命名的文件夹下（**并以task名字作为子文件夹名字**）

允许进行自定义的格式化命名

![renderstack ouput](../../uploads/renderstack%20ouput.png)