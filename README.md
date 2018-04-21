#初尝MarkDown
##我的认识
**MarkDown**是当下主流的文档排版工具,是开发者必备技能!

让我们开始学习吧....

![MarkDown Logo](http://upload-images.jianshu.io/upload_images/648466-85d39fd6031c3b2c.jpg?imageMogr2/auto-orient/strip%7CimageView2/1/w/300/h/300)

##学习使用
我将会把本次学习文档放入我的简书[VIC_LI](http://www.jianshu.com/users/94cc1a4dac92/latest_articles)

**学习工具** [MacDown]() 

![MacDown Logo](http://upload-images.jianshu.io/upload_images/1129706-6b034a6f98e09b05.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**相关目录跳转**
  ###这是一个跳转[**这是我的邮箱** Gmail](#My e_mail)

Font:*正常*  **加粗**  ***加粗倾斜*** 

**怎么去断行呢??**
点这里我告诉你[here](#Line Breaks)

<a name="Line Breaks"></a>***Line Breaks***
换行使用演示: `换行+空格=实现断行效果`

    我不想换行 I don't want to line break

    我想换行
    I don't want to line break

`和换行使用很类似的Header  实现小标题排版`

    Header
    ==========

    Header
    ----------

    #Header
    ##Header
    ###Header
    
   
 
**List**

* 前面会有小黑点 [别忘了* 后面的空格]()
* 和上面是并列的 都是一级list
 - `-`标志开始进入具体的二级list
 - 和上面的一样的 都是二级list
  - 三级list尝试 无效!
* 一级list又来了
   
 **Block**

 > [注意排版时需要和标题之间空一行]
 > `>`标记语法块
 > 只有一个`>`是最外围的语法块
 > > 两个`>`就是二级语法块
 > > > 三个`>`就是.....
 > > > > 四个有用吗  [可以有]()
 > > > > > 五个..
 > > > > > > 六个.....不试了够用了
 > > > > >  
 
     开始回归  ***秀断行***
 
 > > > > 继续
 > > > 好像不太对 
 > > 排版和我想的不一样
 > 查看文档  做不到block回归效果
 > 
 > 实现的大牛可以分享一下 求教!
 >
 > * 文档示例可以这样
 > * [`这样的链接也可以`][arbitrary_id]
 > - [这样的也可以][arbitrary_id]
                
 **宏**`名字不知道是什么 但是和宏的效果一样`
 
 [arbitrary_id]: http://macdown.uranusjr.com "Title"
 
 **很乱 Mark代码**
 
 ```
 > [注意排版时需要和标题之间空一行]
 > `>`标记语法块
 > 只有一个`>`是最外围的语法块
 > > 两个`>`就是二级语法块
 > > > 三个`>`就是.....
 > > > > 四个有用吗  [可以有]()
 > > > > > 五个..
 > > > > > > 六个.....不试了够用了
 > > > > >  
 
     开始回归  ***秀断行***
 
 > > > > 继续
 > > > 好像不太对 
 > > 排版和我想的不一样
 > 查看文档  做不到block回归效果
 > 
 > 实现的大牛可以分享一下 求教!
 >
 > * 文档示例可以这样
 > * [`这样的链接也可以`][arbitrary_id]
 > - [这样的也可以][arbitrary_id]
                
 **宏**`名字不知道是什么 但是和宏的效果一样`
 
 [arbitrary_id]: http://macdown.uranusjr.com "Title"
 ```
   
完美的分割线`***`

***

也可以是`---`

---


***源码展示***

* 可以是`` ` ``
 - 这样
 
  ```
  print('Hello world!')
  ```
  
* 也可以是`~`
 - 这样
 
 ```
 print('Hello world!')
 继续断行
 ```
##下面是比较复杂的表格展示和函数  
---
(**直接借鉴管网示例**)

#### Table

This is a table:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

You can align cell contents with syntax like this:

| Left Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |         $1600 |
| col 2 is      | centered        |           $12 |
| zebra stripes | are neat        |            $1 |


**内联 Inline**

The following is a list of optional inline markups supported:

Option name         | Markup           | Result if enabled     |
--------------------|------------------|-----------------------|
Intra-word emphasis | So A\*maz\*ing   | So A<em>maz</em>ing   |
Strikethrough       | \~~Much wow\~~   | <del>Much wow</del>   |
Underline [^under]  | \_So doge\_      | <u>So doge</u>        |
Quote [^quote]      | \"Such editor\"  | <q>Such editor</q>    |
Highlight           | \==So good\==    | <mark>So good</mark>  |
Superscript         | hoge\^(fuga)     | hoge<sup>fuga</sup>   |
Autolink            | http://t.co      | <http://t.co>         |
Footnotes           | [\^4] and [\^4]: | [^4] and footnote 4   |
   
   
### TeX-like Math Syntax

**数学式**

I can also render TeX-like math syntaxes, if you allow me to.[^math] I can do inline math like this: \\( 1 + 1 \\) or this (in MathML): <math><mn>1</mn><mo>+</mo><mn>1</mn></math>, and block math:

\\[
    A^T_S = B
\\]

or (in MathML)

<math display="block">
    <msubsup><mi>A</mi> <mi>S</mi> <mi>T</mi></msubsup>
    <mo>=</mo>
    <mi>B</mi>
</math>


**标注**

你这么说 [^无语]

呵呵一笑 [^ mark]
   
* 表示同意 [^ 默认]

   
[^无语]: If **Underlines** is turned on, `_this notation_` will render as underlined instead of emphasized 

[^ 默认]: If **Underline** is disabled `_this_` will be rendered as *emphasized* instead of being underlined.

[^ mark]: **Quote** replaces literal `"` characters with html `<q>` tags. **Quote** and **Smartypants** are syntactically incompatible. If both are enabled, **Quote** takes precedence. Note that **Quote** is different from *blockquote*, which is part of standard Markdown.

[^math]: Internet connection required.

下载Mac Down练习点击这里 <http://macdown.uranusjr.com/> **OR**  [here](http://macdown.uranusjr.com/)




**全篇源码**
```

#初尝MarkDown
##我的认识
**MarkDown**是当下主流的文档排版工具,是开发者必备技能!

让我们开始学习吧....

![MarkDown Logo](http://upload-images.jianshu.io/upload_images/648466-85d39fd6031c3b2c.jpg?imageMogr2/auto-orient/strip%7CimageView2/1/w/300/h/300)

##学习使用
我将会把本次学习文档放入我的简书[VIC_LI](http://www.jianshu.com/users/94cc1a4dac92/latest_articles)

**学习工具** MacDown 

![MacDown Logo](http://upload-images.jianshu.io/upload_images/1129706-6b034a6f98e09b05.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**相关目录跳转**

###这是一个跳转[**这是我的邮箱** Gmail](#My e_mail)


##<a name="My e_mail"></a>Gmail
***邮箱跳转***:Gmail: <vicLizq@gmail.com>

Font:*正常*  **加粗**  ***加粗倾斜*** 

**怎么去断行呢??**
点这里我告诉你[here](#Line Breaks)

<a name="Line Breaks"></a>***Line Breaks***
换行使用演示: `换行+空格=实现断行效果`

    我不想换行 I don't want to line break

    我想换行
    I don't want to line break

`和换行使用很类似的Header  实现小标题排版`

    Header
    ==========

    Header
    ----------

    #Header
    ##Header
    ###Header
    
   
 
**List**

* 前面会有小黑点 [别忘了* 后面的空格]()
* 和上面是并列的 都是一级list
 - `-`标志开始进入具体的二级list
 - 和上面的一样的 都是二级list
  - 三级list尝试 无效!
* 一级list又来了
   
 **Block**

     > [注意排版时需要和标题之间空一行]
 > `>`标记语法块
 > 只有一个`>`是最外围的语法块
 > > 两个`>`就是二级语法块
 > > > 三个`>`就是.....
 > > > > 四个有用吗  [可以有]()
 > > > > > 五个..
 > > > > > > 六个.....不试了够用了
 > > > > >  
 
     开始回归  ***秀断行***
 
 > > > > 继续
 > > > 好像不太对 
 > > 排版和我想的不一样
 > 查看文档  做不到block回归效果
 > 
 > 实现的大牛可以分享一下 求教!
 >
 > * 文档示例可以这样
 > * [`这样的链接也可以`][arbitrary_id]
 > - [这样的也可以][arbitrary_id]
                
 **宏**`名字不知道是什么 但是和宏的效果一样`
 
 [arbitrary_id]: http://macdown.uranusjr.com "Title"
 
 **很乱 Mark代码**
 
 ```

                 > [注意排版时需要和标题之间空一行]
                 > `>`标记语法块
                 > 只有一个`>`是最外围的语法块
                  > > 两个`>`就是二级语法块
                  > > > 三个`>`就是.....
                  > > > > 四个有用吗  [可以有]()
                  > > > > > 五个..
                  > > > > > > 六个.....不试了够用了
                  > > > > >  
 
                      开始回归  ***秀断行***
 
                  > > > > 继续
                  > > > 好像不太对 
                  > > 排版和我想的不一样
                  > 查看文档  做不到block回归效果
                  > 
                  > 实现的大牛可以分享一下 求教!
                  >
                  > * 文档示例可以这样
                  > * [`这样的链接也可以`][arbitrary_id]
                  > - [这样的也可以][arbitrary_id]

 **宏**`名字不知道是什么 但是和宏的效果一样`
 
 [arbitrary_id]: http://macdown.uranusjr.com "Title"
 ```
   
完美的分割线`***`

***

也可以是`---`

---


***源码展示***

* 可以是`` ` ``
 - 这样
 
  ```
      print('Hello world!')

  ```
  
* 也可以是`~`
 - 这样
 
 ```
       print('Hello world!')
       断行
 ```
##下面是比较复杂的表格展示和函数
#### Table

This is a table:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

You can align cell contents with syntax like this:

| Left Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |         $1600 |
| col 2 is      | centered        |           $12 |
| zebra stripes | are neat        |            $1 |


**内联 Inline**

The following is a list of optional inline markups supported:

Option name         | Markup           | Result if enabled     |
--------------------|------------------|-----------------------|
Intra-word emphasis | So A\*maz\*ing   | So A<em>maz</em>ing   |
Strikethrough       | \~~Much wow\~~   | <del>Much wow</del>   |
Underline [^under]  | \_So doge\_      | <u>So doge</u>        |
Quote [^quote]      | \"Such editor\"  | <q>Such editor</q>    |
Highlight           | \==So good\==    | <mark>So good</mark>  |
Superscript         | hoge\^(fuga)     | hoge<sup>fuga</sup>   |
Autolink            | http://t.co      | <http://t.co>         |
Footnotes           | [\^4] and [\^4]: | [^4] and footnote 4   |
   
   
### TeX-like Math Syntax

**数学式**

I can also render TeX-like math syntaxes, if you allow me to.[^math] I can do inline math like this: \\( 1 + 1 \\) or this (in MathML): <math><mn>1</mn><mo>+</mo><mn>1</mn></math>, and block math:

\\[
    A^T_S = B
\\]

or (in MathML)

<math display="block">
    <msubsup><mi>A</mi> <mi>S</mi> <mi>T</mi></msubsup>
    <mo>=</mo>
    <mi>B</mi>
</math>


**标注**

你这么说 [^无语]

呵呵一笑 [^ mark]
   
* 表示同意 [^ 默认]

   
[^无语]: If **Underlines** is turned on, `_this notation_` will render as underlined instead of emphasized 

[^ 默认]: If **Underline** is disabled `_this_` will be rendered as *emphasized* instead of being underlined.

[^ mark]: **Quote** replaces literal `"` characters with html `<q>` tags. **Quote** and **Smartypants** are syntactically incompatible. If both are enabled, **Quote** takes precedence. Note that **Quote** is different from *blockquote*, which is part of standard Markdown.

[^math]: Internet connection required.

下载Mac Down练习点击这里 <http://macdown.uranusjr.com/> **OR**  [here](http://macdown.uranusjr.com/)





```

##<a name="My e_mail"></a>Gmail
***邮箱跳转***:Gmail: <vicLizq@gmail.com>

MarkDown  借鉴管网学习    高手勿喷    欢迎交流学习!
**网页版和客户端实现效果不太一样.....**
![Stay Hungry. Stay Foolish](http://upload-images.jianshu.io/upload_images/1129706-45a0544d33528596.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)