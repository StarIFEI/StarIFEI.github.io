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

------------------------------------------------------

* ### HTML 标题  
__HTML 标题（Heading）是通过 &lt;h1&gt; - &lt;h6&gt; 等标签进行定义的。__  
* ### HTML 段落  
__HTML 段落是通过 &lt;p&gt; 标签进行定义的。__  
* ### HTML 链接  
__HTML 链接是通过 &lt; a &gt; 标签进行定义的。__   
~~~  
<a href="http://www.w3school.com.cn">This is a link</a>
~~~
* ### HTML 图像  
__HTML 图像是通过 &lt; img &gt; 标签进行定义的。__  
_注释：图像的名称和尺寸是以属性的形式提供的。_  
~~~  
<img src="w3school.jpg" width="104" height="142" />
~~~

---


## HTML 元素  
__HTML 文档是由 HTML 元素定义的。__
* ### HTML 元素语法  
  HTML 元素指的是从开始标签（start tag）到结束标签（end tag）的所有代码。  
  _注释：开始标签常被称为开放标签（opening tag），结束标签常称为闭合标签（closing tag）。_  
  
> * HTML 元素以开始标签起始  
> * HTML 元素以结束标签终止  
> * 元素的内容是开始标签与结束标签之间的内容  
> * 某些 HTML 元素具有空内容（empty content）  
> * 空元素在开始标签中进行关闭（以开始标签的结束而结束）  
> * 大多数 HTML 元素可拥有属性  

> 1. p元素定义了HTML文档段落  
> 2. body元素定义了HTML文档主体  
> 3. html元素定义了整个HTML文档  
<br/>  
> &lt;br/&gt;为空的 HTML 元素没有内容的 HTML 元素被称为空元素。空元素是在开始标签中关闭的。
> &lt;br/&gt;就是没有关闭标签的空元素（&lt;br/&gt;标签定义换行）。
> 在 XHTML、XML 以及未来版本的 HTML 中，所有元素都必须被关闭。
> 在开始标签中添加斜杠，比如 &lt;br/&gt;，是关闭空元素的正确方法，HTML、XHTML 和 XML > > 都接受这种方式。
> 即使 &lt;br/&gt; 在所有浏览器中都是有效的，但使用 &lt;br/&gt; 其实是更长远的保障。

* ### HTML 注释  
可以将注释插入HTML代码中，这样可以提高其可读性，使代码更易被人理解。浏览器会忽略注释，也不会显示它们。  
注释是这样写的：  
```
<!-- This is a comment -->
```

------------------------------------------------------------------

## HTML 属性  
* ### 属性实例  
HTML 链接由 &lt;a> 标签定义。链接的地址在 href 属性中指定：   
```
<a href="http://www.w3school.com.cn">This is a link</a>
```
> 更多 HTML 属性实例  
> 属性例子 1:    
> &lt;h1&amp; 定义标题的开始。   
```
<h1 align="center">拥有关于对齐方式的附加信息。
```
> TIY : 居中排列标题   
> 属性例子 2:    
> &lt;body&amp; 定义 HTML 文档的主体。   
```
<body bgcolor="yellow"> 拥有关于背景颜色的附加信息。
在 HTML 4.01 中，不赞成使用 body 元素的 bgcolor 属性；在 XHTML 1.0 Strict DTD 中，不支持 body 元素的 bgcolor 属性。请使用 CSS 代替。
CSS 语法：<body style="background-color:#E6E6FA">   
```
> TIY : 背景颜色  
> 属性例子 3:    
> &lt;table&amp; 定义 HTML 表格。    
```
<table border="1"> 拥有关于表格边框的附加信息。
```
    
&lt;hr/&gt;为水平分割线


[鸣谢](https://www.cnblogs.com/xudong-bupt/p/3909416.html)  
内容摘自——[W3chool](https://www.w3school.com.cn/html/html_examples.asp)  

<body>
    <input type="button" onclick="shareQQzone();" value="分享">
</body>

<script src="http://qzonestyle.gtimg.cn/qzone/app/qzlike/qzopensl.js#jsdate=20111201" charset="utf-8"></script>
<script>
    //QQ空间分享方法:这样写可以对分享事件进行绑定
    function shareQQzone(){
		//这里填写跳转的网站
        var _url = 'https://starifei.github.io/docs/html%E5%AD%A6%E4%B9%A0.html';
        var _showcount = '1'
		//分享链接后我的评论语句
        var _desc = '博客分享';
		//分享的描述
        var _summary = 'StarIFEI’s blog';
		//标题，设置的标题
        var _title = 'HTML学习';
		//设置名称，貌似没有什么用
        var _site = '没有显示';
		//添加的图片，最好是正方形的
        var _pic = 'https://img3.vilipix.com/picture/pages/regular/2021/07/09/21/21/92127758_p0_master1200.jpg';
		// 图片宽度，不理解
        var _width= '800px';
		// 图片高度，不理解
        var _height= '200px';
		//分享的链接，由上面属性拼接而成
        var _shareUrl = 'http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey?';
        _shareUrl += 'url=' + encodeURIComponent(_url||document.location);   //参数url设置分享的内容链接|默认当前页location
        _shareUrl += '&showcount=' + _showcount||0;      //参数showcount是否显示分享总数,显示：'1'，不显示：'0'，默认不显示
        _shareUrl += '&desc=' + encodeURIComponent(_desc||'分享的描述');    //参数desc设置分享的描述，可选参数
        _shareUrl += '&summary=' + encodeURIComponent(_summary||'分享摘要');    //参数summary设置分享摘要，可选参数
        _shareUrl += '&title=' + encodeURIComponent(_title||document.title);    //参数title设置分享标题，可选参数
        _shareUrl += '&site=' + encodeURIComponent(_site||'');   //参数site设置分享来源，可选参数
        _shareUrl += '&pics=' + encodeURIComponent(_pic||'');   //参数pics设置分享图片的路径，多张图片以＂|＂隔开，可选参数
        window.open(_shareUrl,'_blank','width='+_width+',height='+_height+',top='+(screen.height-_height)/2+',left='+(screen.width-_width)/2+',toolbar=no,menubar=no,scrollbars=no,resizable=1,location=no,status=0');
    }
</script>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;([返回上一级](../README.md))
<body style="background-color:#66CCFF">
