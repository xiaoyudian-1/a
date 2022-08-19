# CSS概述

## 1.1 background属性

```  html
background-image: url('https://img-qn.51miz.com/preview/video/00/00/15/25/V-152528-6E188523.gif');【背景图片】
background-repeat: no-repeat;【单一图片不重复】
background-image: url('http://static.runoob.com/images/mix/img_tree.png');
background-position: top right;【图片位置 右上】
background-attachment:fixed;【图片不动，下滑网页，图片一直在那里】
```

## 1.2 text属性

文本颜色color:	文本对齐方式text-align	文本修饰a {text-decoration:none;}【删除下划线】	文本转换text-transform	文本缩进text-indent

## 1.3 Fonts字体样式

字体样式font-style	字体大小font-size: 40px	

## 1.4 CSS链接

a:link {color:#000000;}      /* 未访问链接*/ 	a:visited {color:#00FF00;}  /* 已访问链接 */ 	a:hover {color:#FF00FF;}  /* 鼠标移动到链接上 */ 	a:active {color:#0000FF;}  /* 鼠标点击时 */

## 1.5 CSS盒子模型

![CSS box-model](https://www.runoob.com/images/box-model.gif)



最终元素的总宽度计算公式是这样的：

总元素的宽度=宽度+左填充+右填充+左边框+右边框+左边距+右边距

元素的总高度最终计算公式是这样的：

总元素的高度=高度+顶部填充+底部填充+上边框+下边框+上边距+下边距

## 1.6 css组合选择符

- 后代选择器(以空格   分隔)
- 子元素选择器(以大于 **>** 号分隔）
- 相邻兄弟选择器（以加号 **+** 分隔）
- 普通兄弟选择器（以波浪号 **～** 分隔）









