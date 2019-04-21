# HTML

## 什么是html
超文本标记语言 hyper text markup language

## 干什么
承载内容（页面中展示的内容）

## 标签（元素）

标签名，属性，内容

## 标签分类


*双标签（有开始标签和结束标签）

*单标签（只有开始标签没有结束标签）

编辑时候的样式和最终浏览器显示的样式没关系

有些标签有属性有些没有
## 注释
!--注释内容--
* ctrl+/   行注释
* ctrl+shift+/   段注释
## 标题标签

双标签 h1~h6
## 文字
b strong 加粗

i em 斜体

s del 删除标签

strong>b em>i
## 区段标签

br 单标签  换行

hr单标签 表示水平线 （属性：width size color）

p双标签  表示段落，在浏览器显示是不按照编写的格式展示

pre双标签  
* 元素可定义预格式化的文本。在浏览器中显示时，按照编写的格式显示。元素可定义预格式化的文本
         被包含在pre元素中的文本通常都有保留空格符和换行符的功能。
## 列表
* 无序列表 ul>li
* 有序列表 ol>li
## 万能标签
* div (division)
 ## 图片 img 单标签
 
  1.src 图片地址
  
  
  * 同级
  
   ** 绝对路径:从根目录或者盘符开始，按照目录结构指导文件或者互联网上的一个独立地址。任何地方都可引入文件。
  
  img src="D:\wamp\www\timg.jpg"
  
  ** 相对路径：相对于当前的html文件。路径依赖于相对位置。
  
   img src="./timg.jpg"
   
   * 同级目录
   
   img src="./images/timg.jpg"
   
   * 上级目录
   
   img scr="../img/timg.jpg"
   
   * 上上级目录
   
   img scr="../../img/timg.jpg"
   
  2.alt图片加载失败提示
   
  3.title 鼠标移入时提示

## 快捷键
* 创建标签 tagname+tab
* 若干相同元素 tagname*5(复制5个一样的)
* 父子parent>son  如ol>li
* 复制光标所在行 ctrl+d