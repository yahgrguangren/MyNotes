2024-02-25
# 标题(标题前加#+空格)
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
例如：[百度](https://www.baidu.com)

# 代码(三个小捺在波浪线键上)


```css
/* Custom Header Styles */

```

# 任务列表(减号+空格+中括号阔上一个空格或X+空格)
- [ ] 任务列表
- [x] 任务列表
- [?] 这也是一个已完成的项目（实际上你可以在其中使用任何字符）

# 流程图(!+一对中括号 括住文件名)

[在线markdown练习与学习](https://www.zybuluo.com/mdeditor)

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
```

==在文章结束的后面可以看到各个脚注的解释==[^5]在文章结束的后面可以看到各个脚注的解释

[^3]:
[^4]:一定要在段落后面释放脚注，否则脚注会失效！！！
[^5]:这里是角住的释放也是角注的内容
# 插入图片(![Engelbart]+!+两个方括号括住的图片名)
![Engelbart]![[Pasted Image 20240227224949_664.png]]


# 引用（\\-）
> 人类面临着越来越复杂和紧迫的问题，他们有效处理这些问题对社会的稳定和持续进步至关重要。

\- 道格·恩格尔巴特, 1961

# 高亮(用两对=号括起来)
使用两个等号来对文本进行高亮==文本==


[跳转到字体加粗](#字体加粗)

# 公式的书写（两个美元符号之间）

```math
$e^{ix} = cosx + isinx$
$c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}}$
$$△= \sqrt{b^{2}-4ac}/2$$
/*双美元号可以居中公式*/
```
$e^{ix} = cosx + isinx$
$$ c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}} $$
$c = \sqrt{a^{2}+b_{xy}^{2}+e^{x}}$

$$△= {(-b±\sqrt{b^{2}-4ac})}/2a$$

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
纯链接：<https://www.silinchen.com>
邮箱：<fake@example.com>

# URL 和电子邮件地址(放在`<>`之间)
```
文字链接：[我的个人网站](https://www.silinchen.com "学习、研究、分享")
纯链接：<https://www.markdownguide.org>
邮箱：<fake@example.com>
```

<https://www.markdownguide.org>
<fake@example.com>

## 使用背景色

<table><tr><td bgcolor=yellow ><font color=red>背景黄色，前景红色</font></td></tr></table>

```
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


```
> Dorothy followed her through many of the beautiful rooms in her castle.
/*强调*/
```
# 强调（`由>开始`）

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
