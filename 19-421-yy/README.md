
[yy的主页](https://github.com/1404117061)



 # 我学markdown的过程



@[toc]
## 1、标题
一个<kbd> #  </kbd>表示一级标题，俩个<kbd>##</kbd>表示二级标题，以此类推
（注意#后面有空格）
## 2、文本样式
1. **加粗**：使用一对<kbd>** </kbd>或者一对<kbd>__</kbd> 
2. *斜体*：使用一对<kbd>* </kbd>或者一对<kbd>_</kbd> 
3. ~~删除线~~：使用一对<kbd>~~ </kbd>
4. 角标：
 -  上角标：
    使用一对<kbd>^</kbd>括起来的内容是上角标。如：
    <kbd>2\^8\^</kbd>会产生这样的效果:2^8^
 - 下角标
    使用一对<kbd>~</kbd>括起来的内容，如：
	<kbd> h\~2~o </kbd>会产生这样的效果：h~2~o
5. 注脚
  使用<kbd>[^x] </kbd>（X代指数字）表示一个注脚，使用“[^X]:”给出注解的解释。如：
  “yy”[^x]

6. ==标记文本==
  
## 3、列表
  - **无序列表**
    使用<kbd>-</kbd>、<kbd>+</kbd>、<kbd>*</kbd>（三者功能相同）表示其后是一个列表，符号后同样需要追加空格。如：
    - 列表1
    + 列表2
    * 列表3
  - **有序列表**
    使用<kbd>X.</kbd>（X代指数字）表示其后是一个有序列表，<kbd>.</kbd>后需追加空格。如：
   1. 列表1
    2. 列表2
    3. 列表3
- **代办事项**
使用<kbd>[]</kbd>表示一个方框(一对方括号间有一个空格)，使用<kbd>[X]</kbd>表示一个被勾选的方框（x不区分大小写）。如：
- [ ]  6点起床
 - [x] 7点起床
 
 ##  4、引用
 使用<kbd>></kbd>可以引用文本。如：
 >这是一个引用实例

## 5、插入
**1.插入链接**
格式如下：
>[描述文件]（网址）

例如：
[4399小游戏](www.4399.com)

**2.插入图片**
格式如下：
>![描述文字]（图片地址）
注意：要想使图片带尺寸，则在图片的地址的最后
加上 =(a)x(a),其实a为数字，想要居中，则使用#pic_center


如:
![图片](https://img-blog.csdnimg.cn/20191123001300200.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3l1eXUxNDA0MTE3MDYx,size_16,color_FFFFFF,t_70#pic_center)
**3.插入代码**
使用一对<kbd> ```</kbd>括起来的内容为一段代码，如：
```python

class Person:
	name='yy'

yy=Person()
print(yy.name+'最帅')

```
## 6、表格
1. 例如使用下面的格式：

| 科目 | 分数 | 排名 |
|--------|--------:|:-------|
| 语文  | 90 | 1  | 

居中：<kbd>------</kbd>
向左对齐：<kbd>:--------</kbd>
向右对齐：<kbd>-----:</kbd>

## 7、其他：
**1. 设置字体大小、颜色、种类**
>格式：\<font size=x color=a face ="字体种类">这是一句话\<font>
>其中：x为数字，a为颜色
  
  例如：
<kbd>  \<font size=3 color=red face="宋体">这是一句话\<font></kbd>
 <font size=3 color=red face="宋体">这是一句话<font>

**2.下划线效果**
 >\<ins> 句子\</ins>
 
 例如：
 <kbd>  \<ins>句子\</ins> </kbd>
 效果如下：
<ins>下划线效果</ins>

**3.设置背景颜色**
<table>
<tr>
<td bgcolor=gree>
一段有背景色的文字
</tr>
</td>
</table>

**4.文本对齐**
1. 左对齐：
例如：
>\<p align="left">向左对齐\</p>

会产生这样的效果：
><p align="letfr">向左对齐</p>




2. 向右对齐：
>\<p align=right>向右对齐\</p>

会产生这样的效果：
><p align=right>右对齐</p>

3. 居中对齐
例如：
>\<p align="center">居中对齐\</p>

效果如下：
><p align="center">居中对齐</p>

**5.换行**
(1) \<br>
(2)连续俩个空格+<kbd>Enter</kbd>

**6.分割线**
一行使用3个<kbd>*</kbd>

**7.特殊符号**
对于markdown中的语法符号，使用<kbd>\ </kbd>可以显示符号本身

**8.生成目录**
在文档中增加”[TOC]“（[TOC]需独占一行才能生效）即可自动给文档生成目录

**9.空格**
①全角空格：\&emsp;
②半角空格：\&ensp;


<br>
<br>
<br>
<br>
<br>

# 我的学习经历
 &emsp;&emsp;各位学长学姐，你们好，以上内容，全是自己敲出来的，就是我学习到的markdown的语法（手动滑稽），算是成品展示吧，下面我稍微介绍一下我的markdown的学习经历：<br>
&emsp;&emsp;刚开始的时候的时候，我通过b站去了解，什么是markdown，然后发现，markdown其实很简单，就像是数学公式一样，只需要知道怎么用，就能很流畅的使用markdown了。最初，我通过找视频，去学习，后来，我直接去网上搜索markdown的基础语法，然后照着语法去写，就能写出现在的内容了
  
  
  
  # java环境配置：<br>
  1. 在官网上面下载jdk
  2. 讲jdk存放在c盘里的Program Files里
  3. 打开我的电脑，点击属性，再找到环境变量，由于我将jdk装在c盘，所以在用户变量里添加变量名为JAVA_HOME，变量值为C:\Program Files\Java\jdk1.8.0_231的路径
  4. 在path中添加%JAVA_HOME%\bin
  5. 打开cmd，输入java -version，检验是否安装成功<br>
  
  ![路径](https://img-blog.csdnimg.cn/20191123193046885.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3l1eXUxNDA0MTE3MDYx,size_16,color_FFFFFF,t_70)
  
  ![java](https://img-blog.csdnimg.cn/2019112319333665.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3l1eXUxNDA0MTE3MDYx,size_16,color_FFFFFF,t_70)
  
  
  # 虚拟机环境配置<br>
  虚拟机的话，我选择的是Vm VirtualBox，然后我下载了ubuntu
  1. 安装Vm VirtualBox
  2. 点击新建，给虚拟机赋予名字，如：pyvip，然后选择类型，和版本，如类型：linux，版本：unbuntu（64-bit）
  3. 给虚拟机分配内存
  4. 使用以后虚拟硬盘文件，找到自己的ubuntu的文件的路径
  5. 点击创建，就完成啦<br>
  这是虚拟机打开后的界面：
  ![虚拟机内的界面](https://img-blog.csdnimg.cn/20191123194905601.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3l1eXUxNDA0MTE3MDYx,size_16,color_FFFFFF,t_70)
  ![我的虚拟机](https://img-blog.csdnimg.cn/20191123194907551.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3l1eXUxNDA0MTE3MDYx,size_16,color_FFFFFF,t_70)
  
