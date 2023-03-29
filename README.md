# WebPhotoshop

## 演示地址：[https://leanfish2011.github.io/WebPhotoshop-Simple/](https://leanfish2011.github.io/WebPhotoshop-Simple/)

> WebPhotoshop精简版是利用HTML5技术在Web上实现对图形图像的处理，构建易维护、易共享、易于拓展、实时性的Web图形图像处理平台。
> 精简版功能包括：图形绘制、图像处理、图像操作。完整版包括多人协作操作图像、实时交流、图片搜索，同时实现实时的多人协作处理图形图像技术。（完整版后续上传）
## WebPhotoshop绘制展示1
![WebPhotoshop绘制展示1](https://raw.githubusercontent.com/leanfish2011/WebPhotoshop-Simple/master/Images/1.png)

## WebPhotoshop绘制展示2
![WebPhotoshop绘制展示2](https://raw.githubusercontent.com/leanfish2011/WebPhotoshop-Simple/master/Images/2.png)

## 一、功能说明：
### 1、图形绘制
1. 实现铅笔、画笔（书法画笔、喷枪、蜡笔、记号笔、水彩画笔）的绘制效果。
2. 实现直线、曲线、椭圆（圆）、矩形（圆角矩形）、三角形（直角三角形、等边三角形、任意三角形）、多边形的绘制。
3. 绘制过程中，可以选择颜色，选择颜色有两种方式：颜色选择、颜色拾取。可以进行颜色填充，即对选定区域，用选择的颜色进行填充。

### 2、图像处理
1. 能够实现的效果有：黑白、模糊、亮度/透明度、反色、雾化、锐化、浮雕、雕刻、柔化、油画、积木、怀旧、蒙版.
2. 蒙版包括：红色蒙版、蓝色蒙版、绿色蒙版。

### 3、图像操作
1. 能够对图像进行的操作有：图像选择，包括区域选择、对象选择。
2. 图像移动，即对选择区域或对象的移动。
3. 图像裁剪，包括矩形裁剪（保留裁剪区内、保留裁剪区外）。
4. 图像的旋转，即将画布或者选择的区域对象向右90度、向左90度、180度、垂直旋转、水平旋转、任意度数。
5. 橡皮擦效果，能够擦除绘制的图像。
6. 图像的缩小放大，包括图像的局部缩放和图像的整体缩放。
7. 插入文本，即在图像上插入文本，能够改变文本颜色、字体、大小，实现加粗、倾斜、下划线、删除线效果。
8. 将图像保存为图片。将图像存到服务器。将图像另存为其他格式。图像保存为下次可以再进行编辑的自定义格式。

### 4、其他
1. 可以实现操作无限制回退，和跳转到任何一次操作。
2. 可以实现添加图层、删除图层、移动图层。

### 5、完整版功能
1. 多人协同绘图。实现了多人同时在线编辑同一张图片，实时合并和展现对方的绘制。
2. 实时交流。支持多人群聊、一对一单聊，方便多人协同绘制中沟通。

## 二、操作流程：
> 1) 进入系统后，显示主工作区，包括菜单栏、选项栏、工具箱、主画板、历史记录、图层管理。
> 2) 默认为铅笔，可以在主工作区画图。可以选择颜色等属性。
> 3) 打开图片，进行图片编辑。

## 三、TODO：
>1. 代码需要优化，很多代码都只是功能的实现和累积，没有使用面向对象的思想。
>2. 部分功能因前端局限性还未完全实现。
