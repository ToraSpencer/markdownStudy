# **markdown笔记**


## markdown基本信息
*	是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
*	Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。
*	Markdown 编写的文档后缀为 .md, .markdown。



***
***
***
# Typora使用Tips


## Typora快捷键

**进入/退出源码模式**		 Ctrl+/
**页面放大**		ctrl + shift + + 
**页面缩小**		ctrl + shift + -

## Typora其他操作
*	右键 → 插入，可以插入图片表格等对象。









***
***
***
# 基本语法

*这是一行斜体文字*

**这是一行加粗文字**

~~删除线演示~~


* 这是一个要点
  * 这是一个次级要点
  	* 这是一个次次级要点	



[这是一个链接](https://www.bilibili.com/)








***
***
***
# HTML 元素
* 不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。
* 目前支持的 HTML 元素有：<kbd> <b> <i> <em> <sup> <sub> 等 
*	使用<kbd>来显示键盘文本<kbd>Ctrl</kbd>，<kbd>Alt</kbd>，<kbd>Shift</kbd>
*	`这是一个标签`
*	<font color=#0099ff size=7 face="黑体">HTML实现的7号蓝色黑体字</font>







***
***
***
# 数学

***

* 插入数学公式时，可以使用两个美元符 $$ 包裹 TeX 或 LaTeX 格式的数学公式来实现，如：


$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
{\style{visibility:hidden}{(x+1)(x+1)}}
$$
$ E = mc^2 $
$ \boxed{E=mc^2} $
$ c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}} $



## Tex基本语法
*	这是一条行内数学公式 $ a+b $
*	这是一条居中数学公式
$$
a+b
$$
*	公式内换行用\\\
$$
1+2+3\\
	=3+3
$$
* 下标：				$ x_i $

* 上标：				$ x^2 $

* 多重上下标：     $ x^ {y^z}$

* 分式：				$ \frac{x+y}{y+z} $

* 积分：				$ \int_a^b f(x)$

* 各种帽子：		$ \dot{A},\hat{A}, \widehat{A}, \tilde{A}, \widetilde{A}, \bar{A}, \overbrace{A}, \underbrace{A}, \overset{a}{b}, \underset{a}{b}, \overleftarrow{A}, \overrightarrow{A} $

* 常用符号：		$ \leftarrow, \Leftarrow, \Leftrightarrow $

* 希腊字母：
$$
\alpha , \beta , \gamma , \delta , \epsilon , \zeta , \eta , \theta	\\
\iota , \kappa , \lambda , \mu , \nu , \xi , \omicron , \pi			\\
\rho , \sigma , \tau , \upsilon , \phi , \chi , \psi , \omega		\\
\varepsilon , \vartheta , \varkappa , \varpi , \varrho , \varsigma , \varphi		\\
\Alpha , \Beta , \Gamma , \Delta , \Epsilon , \Zeta , \Eta , \Theta	
$$

  

## 运算符
$$
\cdot \times \int \sum \pm
$$



 ## 矩阵

*	矩阵
$$
\begin{bmatrix} 0 & -i \\ i & 0 \end{bmatrix}\\
$$
*	矩阵公式
$$
\begin{bmatrix} 1 & 0 \\ 0 & 1\end{bmatrix}
\begin{bmatrix} 1 & 2 \\ 3 & 4\end{bmatrix}
=\begin{bmatrix} 1 & 2 \\ 3 & 4\end{bmatrix}
$$
*	行列式
$$
\begin{vmatrix} a & b \\ c & d \end{vmatrix}
$$
*	范数
$$
\begin{Vmatrix} i & 0 \\ 0 & -i \end{Vmatrix}
$$


## 公式格式
### 对齐
*	使用aligned关键字，在需要对齐的字符前面加上"&"
$$
\begin{aligned}
&A.\ 1&B.\ 2\\
&C.\ 3&D.\ 4
\end{aligned}
$$

$$
\begin{aligned}
令A_1&=\lbrace 取到的零件来自甲机床\rbrace\\ A_2&=\lbrace取到的零件来自乙机床\rbrace\\ B&=\lbrace取到的零件是废品\rbrace 
\end{aligned}
$$


# 图片
*	直接
![](.\images\tiger.jpg)

*	指定尺寸、对齐。
 <img src=".\\images\\tiger.jpg" width = "300" height = "200" alt="图片名称" align= 'right' />

 *	指定比例
 <img src=".\\images\\tiger.jpg" width = "50%" height = "50%" alt="图片名称" />