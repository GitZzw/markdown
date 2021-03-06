> # 参考：[链接](https://www.jianshu.com/p/335db5716248)

**富文本编辑器:office word**

**Markdown：一种通过标记字符，对内容进行样式更改的语法**

常见的富文本编辑器中，如果我想要加粗一段话，需要用鼠标选择对应的文本，然后选择加粗选项或Ctrl+B ；但在 Markdown 编辑器中，我只需要在需要加粗的文本开头和结尾加上两个*即可，例如：**加粗这段话**


Markdown 基础用法
# 标题
Markdown支持6种级别的标题，对应html标签 h1 ~ h6
# h1
## h2
### h3
#### h4
##### h5
###### h6


# 段落及区块引用

**Markdown分段** 前后至少保留一个空行即可

> **Markdown高亮显示** >用于段首进行强调


# 插入链接或图片

**引用图片和链接的唯一区别就是在最前方添加一个感叹号**

[点击跳转至百度](http://www.baidu.com)

![图片](https://upload-images.jianshu.io/upload_images/703764-605e3cc2ecb664f6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


# 列表

> Markdown支持有序列表和无序列表两种形式：

> 无序列表使用*或+或-标识,有序列表使用数字加.标识，例如：1.

对于有序列表，Markdown将只关注你的第一个项目的数字编号。例如：如果第一个项目编号是3，以此类推，第二个项目应该是4，最终将显示为3、4、5。而如果你指定了第一个编号，后面的编号指定错误也没有关系，Markdown将只在乎你的第一个项目编号。


* 黄瓜
* 玉米
* 茄子

+ 黄瓜
+ 玉米
+ 茄子

- 黄瓜
- 玉米
- 茄子

1. 黄瓜
2. 玉米
3. 茄子

> 注意事项:如果在单一列表项中包含了多个段落，为了保证渲染正常，*与段落首字母之间必须保留四个空格；
          如果在列表中加入了区块引用，区域引用标记符也需要缩进4个空格
          
          
# 分隔线 
> 排版漂亮，可加入分隔线,Markdown加入分隔线非常简单，使用下面任意一种形式都可以
***
---


# 强调
> 希望对某一部分文字进行强调，使用*或_包裹即可。使用单一符号标记的效果是斜体，使用两个符号标记的效果是加粗

*这里是斜体*
_这里是斜体_

**这里是加粗**
__这里是加粗__


# 高级用法
## 插入代码
> 使用反引号`(英文模式esc下一个键)进行包裹即可。如果是行内代码引用，使用单个反引号进行包裹


**这是一段`var x = 3`行内代码**
>一整段代码，需要至少使用**两个以上**反引号进行包裹


```int a=0;

  int b=0;
```


## 插入表格
> 表格是Markdown语法中比较复杂的一个，其语法如下：
三个短斜杠左右的冒号用于控制对齐方式，只放置左边冒号表示文字居左，只放置右边冒号表示文字居右，如果两边都放置冒号表示文字居中

表头|条目一|条目二
:---:|:---:|:---:
项目|项目一|项目二


## 给文字上色
> Markdown的最初目标就是为纯写作而生的。因此，它并没有考虑文字颜色这一点
> 先用Markdown编辑完成
> 导出为html，在需要上色的部分手动添加标签<font color='#ff0000'></font>保存即可
