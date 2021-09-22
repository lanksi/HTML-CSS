# HTML的简单学习

## Hyper Text Markup Language

[HTMLAPI]: https://www.w3cschool.cn/html/dict

<html lang="en">lang意思为language 后跟语言

[meta name="viewport" content="width=device-width,initial-scale=1.0" 解释](http://www.cnblogs.com/yuzhongwusan/p/4184923.html)

<meta> 中最主要的属性为name和content，还有charset规定页面编码
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
content的属性值
	width:可视区域宽度，值为数字或者关键词为device-width
	height:同width
	intial-scale:页面首次被显示是可视区域的缩放级别，取值1.0则页面按实际尺寸显示，无任何缩放
    maximum-scale=1.0, minimum-scale=1.0;可视区域的缩放级别，
    maximum-scale用户可将页面放大的程序，1.0将禁止用户放大到实际尺寸之上。
	user-scalable:是否可对页面进行缩放，no 禁止缩放
</meta>

<link>

link标签中重要属性为rel 定义当前文档为被链接文档之间的关系

href 定义被连接文档的位置

hreflang 定义别链接文档中的文本语言

