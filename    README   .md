# Lesson10-周四（7.22）
##问题回复
1.用户名输错了，但是不提示
1）打开chrome的控制台console，看里面有没有自己的代码报错
2）如果有报错，还是代码有问题，排错。
3）如果没有报错，还是代码有问题，一行行检查代码
2.点击左侧超链接后，没有在左侧显示网页，而是在左侧显示了
在超链接中要加入target="rightFrame"
3.在gethub上面提交的时候，显示文件数量限制是100
分不同的时间多次上传，码云限制的是20个文件。
4.后台开发技术清单
目前大型系统后台，Java的天下
5.我在当前模板商定以自己的样式可以么？
完全可以。但可能会导致和原来的风格不统一，因此：
最好不要改变美工样式、不要添加自己的特殊的样式，一律使用美工做好的样式。
6.在当前项目里，能不能使用boostrap？
能用，但不建议用。在本项目中。样式是美工起的，他的风格是统一的：
美工没用使用boostrap的样式，如果我们使用了ba样式了，会导致系统
界面风格不统一，开发上是不允许的。
7.到处excle和Echarts怎么弄？
导出需要Java后端支持：需要专门血洗Echarts的使用
##提交
1.课内代码、笔记、作业：提交到码云平台自己的目录
2.项目原型，打包发给学委。
# Lesson9-周三（7.21）
## 昨日问题总结
1.没有样式了 三个目录没有复制进来，样式的话是因为CSS没有复制进来
2.点击链接，新弹出窗口 浏览器换成Chrome，升级Chrome，下载最新版的Chrome
3.用的模板不能自适应 本次使用的模板不是基于Bootstrap的。
# Lesson8-周二（7.20）
## 工作任务：开发《UOLab联合开放实验室管理系统》项目原型（界面）
提供美工做的模板
学会如何在模板基础上改，把项目功能放在模板上
 在暑假期间完成开发，开学时提交
组织待定
 对未来的作用
 大二第二学期，做java web项目：一定会用到这次学的技术
 大三第一学期，做SSM框架的项目：也会用到这次学的项目
做java研发工程师、web前端开发工程师，一定会用
# Lesson7-周一(7.19)
## 总结
1. 正则表达式格式 regExp = /^[0-9]{2,6}$/
	[0-9]是数字范围 
	{2,6}是数字位数

## JS表单验证
	公司开发中要使用正则表达式、JS函数、DOM

# Lesson-周六（7.17）
## 一、昨天问题回复
1. 我的图片在本地可以显示的，到了github上就不能显示了？
   -可能1：图片没有上传到github，把这个图片上传上去
   -可能2：图片已经上传，但是github上图片的路径和代码里不一致（主因）
   -可能3：图片已经上传，但是github没有反应过来，稍等再刷新

## 二、JaveScript的重大作用？
1. 对于Jave研发工程师，JaveScript是必须的，要能熟练开发。
2. 对于Web前端开发工程师，JaveScript必须要深入、精通。这个岗位使用的开发语言
        就是JaveScript。
3. 大数据工程、爬虫工程师等：JaveScript也是需要掌握的。

## 三、JaveScript语言和C语言有关系嘛？
1. 没有任何关系，是俩种独立的语言。
2. 不同的编程语言，他们语法有一定的相似度。相似不代表有关系。

## 四、不同的编程语言的应用场景（领域）
1. C语言（强调算法、数据结构）
 面向过程的。主要用于：智能设备上的软件开发（嵌入式）、操作系统底层开发、算法dd。 安卓手机的底层就是C开发的、
 Windows的底层也用C开发。偏底层应用
2. C++语言
 面向对象的。主要用于：图形界面软件开发（美图秀秀、PS、酷狗音乐等）、通信软件（qq）、游戏、控制软件（带有图形界面的控制软件）
 STM32开发（嵌入式）
3. java语言（不太强调算法）
 面向对象的。主要用于：基于B/S结构的大型管理信息系统开发（12306、教务系统、四六级报名系统）
 大数据开发（Hadoop）、安卓手机应用开发、智能电子设备软件开发（数字电视机顶盒）
4. Pathon语言、
 Pathon2和Pathon3。 胶水语言，什么都能干，全能型选手。主要用于：
 信息安全编程、爬虫、大数据分析、AI等
5. JaveScript
 面向对象的、脚本语言，运行在浏览器上。主要：网页上的动态效果、网页和用户的交互等

- 编程语言没有好坏之分，根据应用的场景，选择不同的语言。
- 在公司里，做啥的就是做啥的。精细化分工。
- 算法：在公司里，有专门的"算法工程师"，数学功底深厚

## 五、JaveScript是什么？
脚本语言，运行在浏览器中，也就是运行在客户机中。各种浏览器都能执行JS，
但是不同的浏览器对JS的支持程度不尽相同。进行浏览器的兼容性测试。
JaveScript不是W3C的标准，由欧洲计算机制造商协会。
HTML、CSS、JS都是由浏览器执行的。

## 六、上网的过程，前端代码的执行过程
1. B/S结构：Browser/Server， 浏览器/服务器结构
   有浏览器就能用
2. C/S结构：Client/Server， 客户机/服务器结构。如：QQ，需要在自己电脑上安装的
3. 单机软件：如：Word，在自己电脑上安，只能自己用。
4. 上网过程分析：上12306为例 
   -输入网址，敲下回车；浏览器向12306的服务器发出请求
   - 响应：服务器收到浏览器请求后，服务器会把保存在服务器上的网页源码，发回给浏览器
   -浏览器在收到源码后，对源码执行，产生最终的显示效果

## 七、JaveScript学习重要提醒
1. JS调试比较麻烦：JS程序的调试要利用Chrome或Firefox的控制台
2. 写JS程序一定要细心，一旦写错，排错真的比较难（初学者）

## 八、Chrome调试(Chrome的控制台console）
1. 鼠标点击（不推荐，不专业）
2. F12（有的同学需要同时按下键盘上的Fn）
3. 使用快捷键：Ctrl+Shirt+I
4. 打开控制台后，调试JS用Console； 调试显示效果等：用Elements

## 九、JaveScript学习重点（公司公司开发重点）
1. 语法（if、for等）
2. 函数
3. 事件
4. 正则表达式与表单验证
5. DOM

## 十、JS输出（便于调试JS代码）
1. alert（）
2. console.log（）
- 补充：JS代码放在什么地方？
  网页内部：单独的.JS文件中 

## 十一、JS语法
1. JS是弱类型语言（没有类型）
2. JS中变量的定义可以用var也可不用
3. JS语言大小写敏感（严格区分大小写）
4. 语句的结尾分号可以写，也可不写
5. JS函数用function，函数名程序员自定、函数的形参由程序员自定，JS中的函数没有返回类型（因为JS是弱类型语言）
- 编程的时候，不要上来就写代码，先整理思路，确定实现步骤；
- 把实现步骤，写成代码

## 十二、排错（大学学习中最麻烦的地方、开发中最要的地方）
1. 写代码容易，排错费劲
2. 仔细分析自己的代码，看哪里写错了，这个过程可能较长，但我们要经历
  经历了，涨经验了，下次同样的错就容易排除了。
3. 排错能力是大学生一定解决的！如何提升该能力？ 多写代码，多出错，累经验。
排错需要经验。公司招聘：要求有项目开发经验。
4. 大家不要放弃！


# Lesson5-周五（7.16）
## 一、Bootstrap表格
## 二、 任务：个人存款计算软件界面
## 三、 任务：个人社保计算软件界面
  为JS提供帮助，后面我们要写JS代码实现计算过程


# Lesson4-周四（7.15）
## 昨日技术总结
1. css选择器（标记、id、class）
2. CSS代码放的位置
3. 边框样式（文本框变红）
4. 工作后，网页界面是由美工（UI)来做，我们在他的基础上开发后端程序
5. 我怎么样把自己做的网页，有一个网址，别人用这个网址就能看到我的网页？

## 一、CSS显示
1. dispiay：隐藏后，释放区域
2. visibility：隐藏后，不释放区域
面试题：上面的俩个有何区别？

## 二、CSS浮动（float）
1. 网页美工必须精通。
2. 主要用于：网页布局（CSS+DIV）
3. CSS+DIV做网页布局离不开浮动，要理解浮动的意思；
   看网页效果，返回来理解用意。

## 三、Bootstrap技术
### 1.Bootstrap介绍
- Twitter公司发明的技术
- 用Bootstrap做的网页，能够自动适应屏幕大小（自适应，响应式）
- 移动优先（Bootstrap伴随智能手机而来）
- Bootstrap技术是基于：HTML/CSS/JavaScript
- Bootstrap本质：写好的CSS样式库（拿来就用-拿来主义）
- Bootstrap不是编程语言，是一种技术

### 2. Bootstrap如何使用
 - 把Bootstrap文件从官网下载下来，复制到自己的项目里
 - 直接使用CDN（内容分发网络，其实就是：放在公网上的文件）
        如果使用CDN方式，自己的电脑必须联网。

### 3.如何学Bootstrap？
- 看官方文档

### 4.Bootstrap工作原理是啥？
- 网格系统（屏幕分成12列,使用着可以自己需要组合这些列）
- 使用Bootstrap后，CSS样式就不用我们自己写了；直接用即可

### 5.如何在github上搭建静态网站
- 注册github账号
- 创建一个项目
- 把写好的网页上传到项目中
- 在设置中找到pageas，点击main，点save

# Lesson3-周三（7.14）
## 一、css是什么？
  1. 层叠式样式表，简称为样式。(Cascading Style Sheets)
  2. 由W3C制定的标准，最新版CSS3
  3. css是由浏览器执行
  4. 作用：美化网页（HTML不具备这个功能）

## 二、css选择器（*****）
1. 标记选择器
2. id选择器
3. class选择器
这三种选择器必须会用！！

## 三、CSS代码放置的位置
1. 页内样式：放在head之间，用style标记
2. 行内样式：放在标记的style属性里，行内样式优先级最高
3. 外部样式：放在独立的.CSS文件中，在网页上用link引入

## 四、开发常用样式
1. 背景颜色
2. 文本样式（color、text-align、text-decoration）
3. 字体样式（font-family、font-size）
 网页上的文字默认是16px； 在工程上，网页上的文字一般是12px或14px
4. 链接样式（a：hover）
5. 表格样式（细线表格border-collapse
6. 边框样式（边框变红border：1px solid red）

## 五、CSS盒子模型
1. 与网页布局密切相关
2. 美工必须精通
3. 开发工程师理解并会用
4. 重要：外边距margin、内边距padding；内外边距是相对的，看站在
哪一方的来说。边距有四个方向。上下左右

## 六、登录网页
1. 用到了盒子模型（内部外部边距等）
2. HTML表单元素（用户名，密码，登录按钮）


# Lesson2-周二（7.13）
## 总结
  1. HTML只能做网页结构，大小写不区分，由游览器执行
  2. 开发重点：表单、表格、超链接、图片、列表、iframe
  3. 学到什么程度就达标了？ 能把2"写"出来
  4. 对开发人员的用途：做项目的界面。
## 一、昨天问题总结 
1. 在HB中Markdown 显示混乱
    （HB并不是专业的Markdown工具，对MD的支持有限，如果提交到码云了，还乱，此时
 就是代码问题。）
2. HTML不区分大小写。
   
## 二、HTML表格
```html
 <table></table>表格标记
 <tr></tr>表格行
 <td></td>表格列
 在<table>里放<tr>,在<tr>里放<td>
 合并单元格使用：<td colspan="2"></td>
 ```
 
## 三、HTML的超链接
1. 链接可以到自己的网页，也可以是外部网站
2. 语法
```html
 <a href=""></a>
 ```
 
## 四、HTML图片
1. 语法
```html
   <img src="" width="" height="">
```
2.图片带链接
在超链接标记<a>中放入<img>

## 五、HTML列表
```html
 有序列表<ol></ol> 无序列表<ul></ul> 列表项<li></li>
 
## 六、标题
HTML中共有6级标题，h1-h6

## 七、段落和DIV块
段落p：会自动换行
块div：会自动换行
span：不会自动换行
label：不会自动换行

## 八、HTML颜色
颜色有俩种：用颜色名；颜色的值（主要），是16进制，以#开头
颜色是由三种色调配而成：RGB(red、green、blue)
- 做网页的在公司里是谁？ 网页美工或UI工程师；我们开发人员是用他的
做好的。我们不去做网页，更不会去做网页。我们需要能看懂他们的。

## 九、字体符号
面试题：HEML中的空格怎么表示？&nbsp;
- HTML是W3C的标准，但W3C不是强制标准，每个浏览器对它的支持
程序都不尽相同，而且HTML语法比较宽松。浏览器是执行网页代码的。
## 十、iframe（常用）

## 高频面试题：post和get有什么区别？
1. post方式提交表单，表单数据在地址栏不显示，比较安全
   get方式提交表单，数据会显示在地址栏上，不安全。
2. post提交数据，数据量大小不限；get一般最大为2k，一般使用post

# Lesson1-周一（7.12）
## 问题总结 
  通过今天的学习，也是明白html网页的建立的方式，感觉自己也是
  需要花一些时间来多打多写才可以掌握，觉得今天这些东西蛮实用的，
 自己可以做一个简易网页。
## 一、Markdown学习
1. Markdown是什么？
  写软件文档用的，软件工程师标配。
 它有自己的语法， 但非常简单。
 浏览器就能识别Markdown代码
 
2. 什么时候用？
 写专业软件文档用；github或gitee上写文档用；
日常写笔记。总结或写书

## 二、HTML介绍
1. HTML是什么？What（推荐使用5W1H学习法）
   叫做：超文本标记语言。最新版本：HTML5，简称H5
   HTML代码由谁执行？浏览器。主流的五大浏览器：
   Chrome、Firefox。Opera、Safari、Edge；
   建议；从现在停止使用360、qq等等浏览器。
   
2. 为什么用它？Why  
   要做Web项目，界面必须得用它。
   
3.谁来用？who？
后端开发人员一定要会、Web前端开发工程师、网页美工（UI）

4.什么时候用？When
做项目需要时候就用。

5.用在哪里？Where
 用在网页上，搭建网页结构或元素。

6.怎么用？How
  按教程学，在项目中实战使用。通过实际使用来学。   
 
### 三、HTML标准
    HTML是由W3C制定的国际标准。W3C：国际万维网组织
     最新版：HEML5
     
##  四、HTML表单开发（*****）
0.表单怎么写？
```
<form></form>
```
1.文本框怎么写？
```html
   <input type="text">
```
2.密码框怎么写？
```
   <input type="password">
```
3.单选按钮怎么写？
```
   <inpue type="radio">
```
4.下拉选择怎么写？
```
   <select></select>
```
5.复选框怎么写？
```
   <input type="checkbox">
```
6.文本域怎么写？
```
   <textarea></textarea>
```
7.文件上传怎么写？
```
   <input type="file">
```
8.提交按钮怎么写？
```
   <input type="submit" value="提交">
```
9.重置按钮怎么写？
```
   <input type="reset"value="清空重填">
```
10.如何跳转网页？  
```
   <action="receive.html">
``` 