[2024-02-25](色彩值列表)
# <font color="#938953">标题(标题前加#+空格)</font>
# 标题-1
## 标题-2
### 标题-3
#### 标题-4
##### 标题-5
###### 标题-6

# 字体加粗
# 字体加粗(前后双星号)
**字体加粗**
# 字体加斜(前后单星号)
*字体加粗*
# 字体加删除线(前后双波浪线)
~~字体加删除线~~

# 有序列表(数字+点+空格)
1. 有序列表1
2. 有序列表2
3. 有序列表3
# 无序列表(星号+空格 或 减号+空格)

* 无序列表1
* 无序列表2
* 无序列表3
# 两种列表均可以通过TAB键控制它的缩进
# 有序列表
1. 有序列表1
	1. 有序列表2
		1. 有序列表3
# 无序列表

* 无序列表1
	* 无序列表2
		* 无序列表3

# 引用(一个>+空格)
> 我的一个引用

# 段落(使用分割线三个英文减号---)
---
# 使用链接(英文的一对中括号+一对小括号[这里是链接的名字] (这是链接的地址))
```
[百度](https://www.baidu.com)
```
例如：[百度](https://www.baidu.com)

# 代码(三个小捺在波浪线键上)


```css
/* Custom Header Styles */

```

# 任务列表(减号+空格+中括号阔上一个空格或X+空格)
```
- [ ] 任务列表
- [x] 任务列表
- [?] 这也是一个已完成的项目（实际上你可以在其中使用任何字符）
```
- [ ] 任务列表
- [x] 任务列表
- [?] 这也是一个已完成的项目（实际上你可以在其中使用任何字符）

# 流程图(!+一对中括号 括住文件名)

[在线markdown练习与学习](https://www.zybuluo.com/mdeditor)

flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op




![[Drawing 2024-02-26 08.38.07.excalidraw]]


# 脚注（一个[+^+数字+]）

脚注的用法很简单，只需要在段落中需要插入脚注的地方标注一个符号，再在段落后对这个符号进行解释即可。比如这是一个简单的脚注，[^1] 这是一个长一些的脚注。[^长脚注]

[^1]: 
[^长脚注]:长脚注

段落后的空行表明上一个段落结束！！[^3]这是第3个脚注
段落后的空行表明上一个段落结束！！[^4]这是第4个脚注

```
==在文章结束的后面可以看到各个脚注的解释==
/*背景是使用了css中的定义*/
[^5]:这里是角住的释放也是角注的内容
```

==在文章结束的后面可以看到各个脚注的解释==[^5]在文章结束的后面可以看到各个脚注的解释

[^3]:
[^4]:一定要在段落后面释放脚注，否则脚注会失效！！！
[^5]:这里是角住的释放也是角注的内容
# 插入图片(!+两个方括号括住的图片名)
![[团圆.jpg|300]]

```
![[团圆.jpg|300]]
```
# 引用（\\-）
> 人类面临着越来越复杂和紧迫的问题，他们有效处理这些问题对社会的稳定和持续进步至关重要。

\- 道格·恩格尔巴特, 1961

# 高亮(用两对=号括起来)
使用两个等号来对文本进行高亮==文本==

```跳转
[跳转到字体加粗](#字体加粗)
```
[跳转到字体加粗](#字体加粗)

# 公式的书写（两个美元符号之间）

```math
$e^{ix} = cosx + isinx$
$c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}}$
$$△= {(-b±\sqrt{b^{2}-4ac})}/2a$$
$$f(x) = \int_{-\infty}^{x} e^{-t^2} dt$$
$$ X= \sqrt[5]{123+y+z}$$
$$ Y(x)= \left\{\begin{aligned} a\\b\\c\\78 \end{aligned}\right.$$

/*双美元号可以居中公式*/
```
$e^{ix} = cosx + isinx$
$$ c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}} $$
$c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}}$

$$△= {(-b±\sqrt{b^{2}-4ac})}/2a$$


$$f(x) = \int_{-\infty}^{x} e^{-t^2} dt$$


$$ X= \sqrt[5]{123+y+z}$$

$$ Y(x)= \left\{\begin{aligned} a\\b\\c\\78 \end{aligned}\right.$$

# 波浪号

```
$$40\degree \sim \sim \sim 360\degree$$
/*/sim代表波浪号*/
```
$$40\degree \sim \sim \sim 360\degree$$
# 大型括号

```
$$ z= \left\{ \left[ \left( \begin{aligned} 
a=&1 \\ 
&b=2 \\ 
c=&3 \\
\end{aligned} \right) \right] \right\} $$

```
$$ z= \left\{ \left[ \left( \begin{aligned} 
a=&1 \\ 
&b=2 \\ 
c=&3 \\
\end{aligned} \right) \right] \right\} $$

# 约等于

```
$$\pi \approx 3.14$$
$$\XYZ \approx 100.123$$
```
$$\pi \approx 3.14$$
$$XYZ \approx 100.123+x$$

# 矩阵
## 1. 基本语法

- 数学公式放在 `$$` 之间。
- 起始标记 `\begin{matrix}`，结束标记 `\end{matrix}` 。
- 每一行末尾标记 `\\`，行间元素之间用 `&` 分隔。

```text
$$\begin{matrix}
0&1&1\\
1&1&0\\
1&0&1\\
\end{matrix}$$
```

$$\begin{matrix}
0&1&1\\
1&1&0\\
1&0&1\\
\end{matrix}$$


## 2. 矩阵边框

- 在起始、结束标记用下列词替换 `matrix`
- `pmatrix`：小括号边框
- `bmatrix`：中括号边框
- `Bmatrix`：大括号边框
- `vmatrix`：单竖线边框
- `Vmatrix`：双竖线边框

```小括号边框
$$\begin{pmatrix}
0&1&1\\
1&1&0\\
1&0&1\\
\end{pmatrix}$$
```

$$\begin{pmatrix}
0&1&1\\
1&1&0\\
1&0&1\\
\end{pmatrix}$$

```中括号边框
$$\begin{bmatrix}
0&1&2\\
3&4&5\\
a&b&c\\
\end{bmatrix}$$
```
$$\begin{bmatrix}
0&1&2\\
3&4&5\\
a&b&c\\
\end{bmatrix}$$

```大括号边框
$$\begin{Bmatrix}
1&2&3\\
2&3&4\\
a&b&c\\
\end{Bmatrix}$$
```
$$\begin{Bmatrix}
1&2&3\\
2&3&4\\
a&b&c\\
\end{Bmatrix}$$

```单竖线边框
$$\begin{vmatrix}
1&2&3\\
2&3&4\\
a&b&c\\
\end{vmatrix}$$
```

$$\begin{vmatrix}
1&2&3\\
2&3&4\\
a&b&c\\
\end{vmatrix}$$

```双竖线边框
$$\begin{Vmatrix}
1&2&3\\
2&3&4\\
a&b&c\\
\end{Vmatrix}$$
```

$$\begin{Vmatrix}
1&2&3\\
2&3&4\\
a&b&c\\
\end{Vmatrix}$$

## 3. 省略元素

- 横省略号：`\cdots`
- 竖省略号：`\vdots`
- 斜省略号：`\ddots`

```省略元素
$$\begin{bmatrix}
{a_{11}}&{a_{12}}&{\cdots}&{a_{1n}}\\
{a_{21}}&{a_{22}}&{\cdots}&{a_{2n}}\\
{\vdots}&{\vdots}&{\ddots}&{\vdots}\\
{a_{m1}}&{a_{m2}}&{\cdots}&{a_{mn}}\\
\end{bmatrix}$$
```

$$\begin{bmatrix}
{a_{11}}&{a_{12}}&{\cdots}&{a_{1n}}\\
{a_{21}}&{a_{22}}&{\cdots}&{a_{2n}}\\
{\vdots}&{\vdots}&{\ddots}&{\vdots}\\
{a_{m1}}&{a_{m2}}&{\cdots}&{a_{mn}}\\
\end{bmatrix}$$

## 4. 阵列

- 需要array环境：起始、结束处以{array}声明
- 对齐方式：在{array}后以{}逐行统一声明
- 左对齐：`l`；居中：`c`；右对齐：`r`
- 竖直线：在声明对齐方式时，插入 `|` 建立竖直线
- 插入水平线：`\hline`

```阵列
$$\begin{array}{c|lll}
{↓}&{a}&{b}&{c}\\
\hline
{R_1}&{c}&{b}&{a}\\
{R_2}&{b}&{c}&{c}\\
\end{array}$$
```

$$\begin{array}{c|lll}
{↓}&{a}&{b}&{c}\\
\hline
{R_1}&{c}&{b}&{a}\\
{R_2}&{b}&{c}&{c}\\
\end{array}$$

## 5. 方程组

 需要cases环境：起始、结束处以{cases}声明


```方程组
$$\begin{cases}
a_1x+b_1y+c_1z=d_1\\
a_2x+b_2y+c_2z=d_2\\
a_3x+b_3y+c_3z=d_3\\
\end{cases}
$$
```

$$\begin{cases}
a_1x+b_1y+c_1z=d_1\\
a_2x+b_2y+c_2z=d_2\\
a_3x+b_3y+c_3z=d_3\\
\end{cases}$$


# Latex公式

```Latex公式
$$\sum_{i=1}^n a_i=0$$ 
$$\sum^n_{i=1} a_i=0$$

$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$

$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$

```

$$\sum_{i=1}^n a_i=0$$
 $$\sum^n_{i=1} a_i=0$$

$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$

$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$



# 转义字符（\\+转义字符）
`\+转义字符`

**例如：**
\*
\{}
\#
\!

<font color=#008000 size=8>中文</font> 
# <font color=red size=6>链接</font>

文字链接：[我的个人网站](https://www.silinchen.com "学习、研究、分享")
纯链接：<https://1.1.1.1/>
邮箱：<fake@example.com>

# URL 和电子邮件地址(放在`<>`之间)
```
文字链接：[我的个人网站](https://www.silinchen.com "学习、研究、分享")
纯链接：<https://www.markdownguide.org>
邮箱：<fake@example.com>
```

<https://www.markdownguide.org>
<fake@example.com>
 [https://www.coze.com](https://www.coze.com/)
## 使用背景色

<table><tr><td bgcolor=yellow ><font color=red>背景黄色，前景红色</font></td></tr></table>

```使用背景色
<table><tr><td bgcolor=yellow><font color=red>背景黄色，前景红色</font></td></tr></table>
/*obsidian只能支持html的部分标签*/
```

<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=4>我是黑体，绿色，尺寸为4</font>
<font color=#008000 size=5>在文中其他任意地方定义链接地址, title 可选。一般定义在使用到超链接的段落后面，或集中在文件结尾:</font>

```字体
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=4>我是黑体，绿色，尺寸为4</font>
<font color=#008000 size=5>在文中其他任意地方定义链接地址, title 可选。一般定义在使用到超链接的段落后面，或集中在文件结尾:</font>

```



# 强调（`由>开始`）

```
> Dorothy followed her through many of the beautiful rooms in her castle.
/*强调*/
```

> Dorothy followed her through many of the beautiful rooms in her castle.

# 嵌套块引用

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


# 与其他元素的块引用

```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```
> #### The quarterly results look great!
>
>-  Revenue was off the chart.
>-  Profits were higher than ever.
>
>  *Everything* is going according to **plan**.


# 1. <font color=green size=5>标题带色</font>

```
# 1. <font color=green size=5>标题带色</font>
/*标题带色*/
```

# 2.文字居中

 <p style="text-align:center;color:#1e819e;font-size:1.3em;font-weight: bold;">
第一行文字居中显示
<br/>
第二行文字居中显示
</p>

```
 <p style="text-align:center;color:#1e819e;font-size:1.3em;font-weight: bold;">
第一行文字居中显示
<br/>
第二行文字居中显示
</p>
```
<p style="text-align:center;color:#FFB6C1;font-size:1.1em;">
文字居中显示
</p>
```
<p style="text-align:center;color:#FFB6C1;font-size:1.1em;">
文字居中显示
</p>
```
<p style="text-align:right;color:#FFB6C1;font-size:1.2em;">
文字右对齐显示
</p>

```
<p style="text-align:right;color:#FFB6C1;font-size:1.2em;">
文字右对齐显示
</p>
```

<p style="text-align:left;color:#FFB6C1;font-size:1.2em;">
文字左对齐显示
</p>

```
<p style="text-align:left;color:#FFB6C1;font-size:1.2em;">
文字左对齐显示
</p>

```
# Editing toolbar插件改变背景与前景色

<span style="background:#ff4d4f"><font color="#f79646"><font color="#c3d69b">标题带色</font></font></span>


# 图片的缩放排版

```
![[团圆.jpg|200]]
嵌入图片：![团圆].(图片的网址)
/*竖线后面的数字为缩放比例*/
```

![[团圆.jpg|200]]![[团圆.jpg|200]]![[团圆.jpg|200]]![[团圆.jpg|200]]![[团圆.jpg|200]]![[团圆.jpg|200]]


# MP3、MP4的插入

```
![[Voice-1.mp3]]
```

![[Voice-1.mp3]]




![[1-日志/Untitled Diagram.svg]]