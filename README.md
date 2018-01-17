# CSS
layout of pages with CSS

**web标准**逐步地变为由三大部分组成的标准集：结构（structure）、表现（persentation）以及行为（behavior）

![](/Img/CSSNote1.png) 

## 结构（structure）
结构用来对网页中用到的信息进行整理与分类。用于结构化设计的web标准主要有这样几种：HTML、XML、XHTML

## 表现（presentation）
表现技术用于对以及被结构化的信息进行显示上的控制，包括版式、颜色、大小等样式控制。在目前的web展示中，用于表现的web标准技术主要就是CSS技术


## 行为（behavior）
行为是指对整个文档内部的一个模板进行定义和交互行为的编写，用于编写用户可以进行交互式操作的文档。表现行为的web标准技术主要有：
↘DOM
↘ECMAScript(JavaScript的扩展脚本语言)

## margin外边距外间距 即div与div间距 

[margin语法详解](http://www.divcss5.com/rumen/r128.shtml#top "外链")

margin用于设置对象标签之间距离间隔，比如2个上下排列的DIV盒子，我们就可以使用margin样式实现上下2个盒子间距。Margin呈现是位于对象边框外侧，紧贴于边框，marign与padding位置却相反css padding却是紧贴边框位于边框内侧。

CSS外边距指CSS属性单词margin，margin是设置对象四边的外延边距，没有背景颜色也无颜色。

### 1、margin语法
```CSS
margin:10px
margin的值是数字+html单位，同时也可以为auto（自动、自适应）
```
### 2、应用结构
```CSS
div{margin:10px}
设置div对象四边间距为10px
```
### 3、Margin说明
#### margin是设置对象外边距外延边距离。
margin的值有三种情况，可以为正整数和负整数并加单位如PX像素（margin-left:20px）；可以为auto自动属性(margin-left:auto 自动)；可以为百分比（%）值（margin-left:3%）。
```CSS
Margin延伸（单独设置四边间距属性单词）
margin-left 对象左边外延边距 （margin-left:5px; 左边外延距离5px）
margin-right 对象右边外延边距 （margin-right:5px; 右边外延距离5px）
margin-top 对象上边外延边距 （margin-top:5px; 上边外延距离5px）
margin-bottom 对象下边外延边距 （margin-bottom:5px; 下边外延距离5px）
```
### 4、实际应用(暂略）

### 二、缩写(暂略)

## padding内补白(内边距)left right top bottom 

[padding语法详解](http://www.divcss5.com/rumen/r418.shtml "外链")

padding : +数值+单位 或 百分比数值

div{padding:5px}设置对象距离四边边距为5px间隔

同时可以单独设置左、右、上、下边距离发布设置

### 1、padding-left 设置对象距离左边的边距补白间隔
```CSS
div{padding-left:5px}
对象内距离左边补白间距为5px
```
### 2、padding-right 设置对象距离右边的边距补白间隔
```CSS  
div{padding-right:5px}
对象内距离右边补白间距为5px
```
### 3、padding-top 设置对象距离上边的边距补白间隔
```CSS
div{padding-top:5px}
对象内距离上边补白间距为5px
```
4、padding-bottom 设置对象距离下边的边距补白间隔
```CSS
div{padding-bottom:5px}
对象内距离下边补白间距为5px
```
div css Padding说明

检索或设置对象四边的补丁边距。
如果提供全部四个参数值，将按上－右－下－左的顺序作用于四边。
如果只提供一个，将用于全部的四条边。
如果提供两个，第一个用于上－下，第二个用于左－右。
如果提供三个，第一个用于上，第二个用于左－右，第三个用于下。
内联对象要使用该属性，必须先设定对象的height或width属性，或者设定position属性为absolute。

Padding的值不能为负值。


**padding**与**margin**的区别
```
padding是在容器内部，margin是在容器外部
就像墙上挂着的两个相框，margin指的是相框与相框的距离，padding指的是每个相框里照片与相框边框的距离。 
```
