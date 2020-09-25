---
title: RenderStack - Task 
category: RenderStack
order: 2
---

Custom render Queue task, render mark task

+ At present, multi task still frame / animation hybrid rendering is supported

+ Custom rendering engine (currently supports eevee and cycles), sampling, view layer, output format, camera (including independent attributes), light studio, etc

**Auto Update Button**

After enable, the rendering screen will be refreshed in real time every time the task parameters are changed, so that the final results can be easily observed

![rendertask1](../../uploads/rendertask1.gif)

#### About Output

If the custom output path is not enabled, the default output is to use ${file name} in the relative directory of blend file_ Under the folder named "render" (**and take the name of task as the name of the subfolder**)

Allow custom formatted naming

![renderstack ouput](../../uploads/renderstack%20ouput.png)