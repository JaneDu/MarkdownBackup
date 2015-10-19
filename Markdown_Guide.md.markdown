### 认识 Markdown 

 - 一种轻量级的标记语言，易读易写；
 - 将输入的文本轻松转换成 HTML ，易于发布到网络；
 - 使你专注于写作而非排版，所见即所得；
 - 兼容 HTML ，Markdown的格式语法只涵盖纯文本可以涵盖的范围，如果某些功能 Markdown 不具备，你可以直接用HTML来编写，因为 Markdown 两种格式都能理解。

### 常用 Markdown 编辑器

> 只介绍了典型几个编辑器，更多好用的编辑器下文有链接可以点击查看
* Windows：[MarkdownPad][1]
* Mac：[Mou][2]
* Linux：[ReText][3]
* Web在线版：[小书匠编辑器][4]


### Markdown 帮助文档

> 相比于 Markdown 的官方文档，个人觉得 Markdown 编辑器（比如我自己用的[小书匠编辑器][5]）自带的语法手册，对语法的讲解更简洁、明了。
* [Markdown设计者John Gruber所写的语法说明][6]
* [Markdown语法说明（简体中文版）][7]
* [简单的Mrkdown指南][8]
* [GitHub Flavored Markdown][9]

### 简单语法介绍

#### **标题**

\# 一级标题
\## 二级标题
\### 三级标题
\#### 四级标题
\##### 五级标题
\###### 六级标题

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

-------------------
#### **斜体**
\*斜体*
*斜体*
-------------------
#### **粗体**
\*\*粗体**
**粗体**
-------------------
#### **有序列表**
 1. List 1
 2. List 2
 3. List 3  

------------------
#### **无序列表**
\* List 1
\* List 2
\* List 3
或者
\- List 1
\- List 2
\- List 3
* List 1
* List 2
* List 3

-----------------
#### **引用**
\> 引用文字
> 引用文字

-----------------
#### **插入链接**
\[baidu](www.baidu.com)

[baidu](www.baidu.com)

-----------------

#### **插入图片**
\!\[The IT Crowd](./images/it_crowd.png )

![The IT Crowd](./images/it_crowd.png )

------------------
#### **表格**
> Markdown 的表格稍稍麻烦，复杂的表格利用其他制表软件绘制，再保存成图片格式载入也是可以的。注意冒号:的作用是定义左对齐，居中对齐，还是右对齐；更多表格的用法说明请参考[GitHub Flavored Markdown][10]

\| Left-Aligned  | Center Aligned  | Right Aligned |
\| :------------ |:---------------:| -----:|
\| col 3 is      | some wordy text | $1600 |
\| col 2 is      | centered        |   $12 |
\| zebra stripes | are neat        |    $1 |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

----------------
#### **分割线**
\***
\****
\* * * *
\---
***

#### **代码框**
行的开头空4个空格，表示程序代码：

def hello()
&emsp;&emsp;print("hello world") 


    def hello()
        print("hello world")   
内嵌代码用一对\`或三个\`\`\`包起来表示: 

`var x = "hello world"`

```
name <- c("Jen","Mei", "July");
age <- c(21,22,23);
data.frame(name, age);
```
-------------------

### 更多使用
* 可以利用反斜杠 \ 来插入一些在语法中有其它意义的符号，比如反引号`，星号*等；
* 段落定义中如何产生缩进：
  半方大的空白用\&ensp;或\&#8194;
  全方大的空白\&emsp;或\&#8195;
  不断行的空白格\&nbsp;或\&#160;
* 将 Markdown 编辑器和印象笔记绑定起来，对我来说实在太好用；
* 一时忘记了 Markdown 的语法也没关系，编辑器上图形化的菜单栏很好用![enter description here][11]
* 更多的文本功能，比如修改字体及颜色，需要会一些CSS知识，可花时间看看[<font color=#ff0000>CSS教程</font>][12]


### 更多阅读
* [为什么我们要学习Markdown的三个理由][13]
* [好用的Markdown编辑器一览][14]
* [马克飞象，一款专为印象笔记打造的Markdown编辑器][15]
  


  [1]: http://markdownpad.com/
  [2]: http://25.io/mou/
  [3]: http://sourceforge.net/p/retext/home/ReText/
  [4]: http://soft.xiaoshujiang.com/
  [5]: http://soft.xiaoshujiang.com/
  [6]: http://daringfireball.net/projects/markdown/
  [7]: http://wowubuntu.com/markdown/index.html
  [8]: http://www.applecho.com/markdown-guide/#help
  [9]: https://help.github.com/articles/github-flavored-markdown/
  [10]: https://help.github.com/articles/github-flavored-markdown/
  [11]: ./images/menu.png "menu.png"
  [12]: http://w3school.com.cn/css/index.asp
  [13]: http://news.cnblogs.com/n/139649/
  [14]: http://www.williamlong.info/archives/4319.html
  [15]: https://maxiang.io/