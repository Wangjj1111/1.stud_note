[TOC]
---
#Markdown教程
##0.Markdown标题
使用 # 号可表示 1-6 级标题，一级标题对应一个 # 号，二级标题对应两个 # 号，以此类推。
##1.Markdown段落
###1.1字体
Markdown可以使用以下几种字体。*斜体文本*、_斜体文本_、**粗体文本**、__粗体文本__、***粗斜体文本***、___粗斜体文本___
###1.2分割线
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。
###1.3删除线
如果段落上的文字要添加删除线，只需要在文字的两端加上两个波浪线 ~~ 即可，eg:
~~abcd~~
###1.4下划线
下划线可以通过 HTML 的 <> 标签来实现：
###1.5脚注
脚注是对文本的补充说明。
[^要标注的文本]
创建类似这样[^RUNOOB]
[^RUNOOB]:菜鸟教程
##2.Markdown列表
Markdown 支持有序列表和无序列表。
无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记（在visualstudio code上不能行的通）
##3.Markdown区块
Markdown 区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号：
> 区块引用
> 菜鸟教程
> 学的不仅是技术更是梦想
##4.Markdown代码
如果是段落上的一个函数或片段的代码可以用反引号把它包起来（`），例如：
`printf()`函数
代码区块使用 4 个空格或者一个制表符（Tab 键）。(无效)
    <php
    echo>
你也可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）：
```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
``` 
##5.Markdown链接
[链接名称](链接地址)
或者<链接地址>
这是一个链接[菜鸟教程](https://www.runoob.com)
链接也可以用变量来代替，文档末尾附带变量地址：
这个链接用 1 作为网址变量 [Google][1]
这个链接用 runoob 作为网址变量 [Runoob][runoob]
然后在文档的结尾为变量赋值（网址）

  [1]: http://www.google.com/
  [runoob]: http://www.runoob.com/
##6.Markdown图片

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)  
##7.Markdown表格
Markdown 制作表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
###7.1对齐方式
我们可以设置表格的对齐方式：
-: 设置内容和标题栏居右对齐。
:- 设置内容和标题栏居左对齐。
:-: 设置内容和标题栏居中对齐。
| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
##8.高级技巧
###8.1支持的 HTML 元素
不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。目前支持的 HTML 元素有
``` <b> <i> <em> <sup> <sub> <br>等 ，如：```
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
###8.2转义
Markdown 使用了很多特殊符号来表示特定的意义，如果需要显示特定的符号则需要使用转义字符，Markdown 使用反斜杠转义特殊字符：
**文本加粗** 
\*\* 正常显示星号 \*\*
###8.3公式
当你需要在编辑器中插入数学公式时，可以使用两个美元符 $$ 包裹 TeX 或 LaTeX 格式的数学公式来实现。提交后，问答和文章页会根据需要加载 Mathjax 对数学公式进行渲染。如：(失败)
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$