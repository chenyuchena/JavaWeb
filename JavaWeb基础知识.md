<h1 align = "center">JavaWeb</h1>

## 一、Web前端

Web标准：

- HTML：负责网页的结构
- CSS：负责网页的表现
- JS：负责网页的行为

### 1、HTML ( HyperText Markup Language)

超文本标记语言

超文本：超越了文本的限制，比普通文本更强大。除了文字信息，还可以定义图片、音频、视频等内容。

标记语言：由标签构成的语言。

HTML标签都是预定义好的。例如：使用<a>展示超链接，使用<img>展示图片，<video>展示视频。HTML代码直接在浏览器中运行，HTML标签由浏览器解析。

HTML结构标签：

```
<html>
	<head>
		   <title>标题</title>
	</head>
	<body>

	</body>
</html>
```

特点：

- HTML标签不区分大小写

- HTML标签属性值单双引号都可以
- HTML语法松散



标题标签

- 标签：<h1>…</h1>（h1 → h6 重要程度依次降低）
- 注意：HTML标签都是预定义好的，不能自己随意定义

水平线标签 ： <hr>

图片标签 

```
<img src="…" width="…" height="…">
```

- 绝对路径：绝对磁盘路径（D:/xxxx）、绝对网络路径（https://xxxx）
- 相对路径：从当前文件开始查找。 （./ : 当前目录, ../ : 上级目录）



CSS引入方式

```
行内样式：<h1 style="...">
内嵌样式：<style> … </style>
外联样式：xxx.css     <link href="...">
```

颜色表示

```
关键字: red、green . . .
rgb表示法：rgb(255,0,0)、rgb(134,100,89) 
十六进制: #ff0000、#cccccc、#ccc
```

颜色属性

```
color: 设置文本内容的颜色
```



<span> 标签

- <span> 是一个在开发网页时大量会用到的没有语义的布局标签
- 特点：一行可以显示多个(组合行内元素)，宽度和高度默认由内容撑开

CSS选择器

- 元素选择器：标签名 { … }
- id选择器：#id属性值 { … }
- 类选择器：.class属性值 { … }
- 优先级：id选择器 > 类选择器 > 元素选择器

CSS属性

- color：设置文本的颜色
- font-size：字体大小 （注意：记得加px）



超链接

```
标签：<a>
属性：
	href：指定资源访问的url
	target：指定在何处打开资源链接
		_self：默认值，在当前页面打开
		_blank：在空白页面打开
```

CSS属性

- text-decoration：规定添加到文本的修饰，none表示定义标准的文本。
- color：定义文本的颜色



CSS盒子模型

​		组成：内容（content）、内边距（padding）、边框（border）、外边距（margin）

CSS属性

```
width：设置宽度
height：设置高度
border：设置边框的属性，如：1px solid #000；
padding：内边距
margin：外边距

注意：如果只需要设置某一个方位的边框、内边距、外边距，可以在属性名后加上 –位置，如：padding-top、padding-left、padding-right …
```



表格标签

```
<table>：定义表格
<tr>：定义表格中的行，一个 <tr> 表示一行
<th>：表示表头单元格，具有加粗居中效果
<td>：表示普通单元格
```

表单标签

```
表单标签：<form>    
表单属性:
action：表单数据提交的url地址
method：表单提交方式
```

表单项标签

```
<input> 的type属性：text、password、radio（单选）、checkbox（多选）、file、date、datetime-local（本地时间）、time、number、hidden、button、submit
<select> 定义下拉列表
<textarea> 定义文本域
```



### 2、CSS (cascading Style Sheet) 

层叠样式表，用于控制页面的样式（表现）。

### 3、JS (JavaScript)

