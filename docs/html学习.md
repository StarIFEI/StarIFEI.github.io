# HTML 网页学习  
([返回上一级](../README.md))  

---

## 基础语法  
~~~  
<html>
<body>
  
<h1>我的第一个标题</h1>
  
<p>我的第一个段落。</p>
  
</body>
</html>
~~~  
~~~
<html>与</html> 之间的文本描述网页  
<body>与</body> 之间的文本是可见的页面内容  
<h1>与</h1> 之间的文本被显示为标题  
<p>与</p> 之间的文本被显示为段落  
~~~  

HTML 标签是由尖括号包围的关键词，比如 &lt; html &gt;  
HTML 标签通常是'成对'出现的，比如 &lt; b &gt; 和 &lt; /b &gt;  
标签对中的第一个标签是开始标签，第二个标签是结束标签  
开始和结束标签也被称为开放标签和闭合标签  
  
---
  
### HTML 标题  
__HTML 标题（Heading）是通过 &lt;h1&gt; - &lt;h6&gt; 等标签进行定义的。__  
### HTML 段落  
__HTML 段落是通过 &lt;p&gt; 标签进行定义的。__  
### HTML 链接  
__HTML 链接是通过 &lt; a &gt; 标签进行定义的。__   
~~~  
<a href="http://www.w3school.com.cn">This is a link</a>
~~~  

### HTML 图像  
__HTML 图像是通过 &lt; img &gt; 标签进行定义的。__  
_注释：图像的名称和尺寸是以属性的形式提供的。_  
~~~  
<img src="w3school.jpg" width="104" height="142" />
~~~

---  


## HTML 元素  
__HTML 文档是由 HTML 元素定义的。__
### HTML 元素语法  
HTML 元素指的是从开始标签（start tag）到结束标签（end tag）的所有代码。  
_注释：开始标签常被称为开放标签（opening tag），结束标签常称为闭合标签（closing tag）。_  

* HTML 元素以开始标签起始
* HTML 元素以结束标签终止
* 元素的内容是开始标签与结束标签之间的内容
* 某些 HTML 元素具有空内容（empty content）
* 空元素在开始标签中进行关闭（以开始标签的结束而结束）
* 大多数 HTML 元素可拥有属性  
  
* p元素定义了HTML文档段落
* body元素定义了HTML文档主体
* html元素定义了整个HTML文档
<br/>  
> &lt;br/&gt;为空的 HTML 元素没有内容的 HTML 元素被称为空元素。空元素是在开始标签中关闭的。
> &lt;br/&gt;就是没有关闭标签的空元素（&lt;br/&gt;标签定义换行）。
> 在 XHTML、XML 以及未来版本的 HTML 中，所有元素都必须被关闭。
> 在开始标签中添加斜杠，比如 &lt;br/&gt;，是关闭空元素的正确方法，HTML、XHTML 和 XML > > 都接受这种方式。
> 即使 &lt;br/&gt; 在所有浏览器中都是有效的，但使用 &lt;br/&gt; 其实是更长远的保障。
  
### HTML 注释  
可以将注释插入 HTML代码中，这样可以提高其可读性，使代码更易被人理解。浏览器会忽略注释，也不会显示它们。  
注释是这样写的：  
~~~
<!-- This is a comment -->
~~~  
  
***  
  
属性
&lt;hr/&gt;为水平分割线
  
[鸣谢](https://www.cnblogs.com/xudong-bupt/p/3909416.html)  
  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;([返回上一级](../README.md))
