#html学习#
<table><tr><td bgcolor=gray> 
　　HTML全称为HypeText Markup Language,译为超文本标记语言，它不是一种编程语言，而是一种描述性的标记语言，用于描述超文本中内容的显示方式。
<table><tr><td bgcolor=bbbddd> 
![](http://i.imgur.com/LI7aFfv.png) 
</tr></table>
    1. < html> 与 < /html> 之间的文本描述网页，放在开头，并没有实质性的功能，只是一个形式标记。

	2. < head>与< /head>也称头标记，一般放在< html>里，其作用是放置关于此html文件的信息，如提供索引、定义CSS样式等。
		
	3. < title>与< /title>称为标题标记，包含在< head>标记内，他的作用是设定网页标题。
		
	4. < body>与< /body>称为主体标记，网页所要显示的内容都放在这个标记下，他是html文件的重点所在，他不仅是一个形式标记，他本身也可以控制网页的背景颜色或背景图像。
		
    5. < font color=# face="字体" size="数字">与< /font>嵌在body标签内，可以控制文字的颜色，字体和大小，color后可填颜色单词，也可填#加RGB颜色，常用的颜色名称有black，gray（深灰），silver(浅灰)，green，purple（紫），yellow，red，white.
			
    6. < img src="带扩展名的图像名称" width="宽度" height="长度" alt="替换图像的文本">是图片插入的标记，他有一个src属性，用于指明图像文件的位置，又由于一些原因导致图片无法正常显示，所以为图片设置一个替换文本。
		
	7. < !--注释 -->是注释标记。
		
	8. < h1> 与 < /h1> 之间的文本被显示为标题。
		    
	9. < p> 与 < /p> 之间的文本被显示为段落。
		
	10. 在html文件里，不管多少空格都被视为一个空格，换行（回车）键也是无效的，如果需要换行则需要标记。
			
	11. < br>与< /br>为换行标记，可用于段内换行，即break的缩写。
		
    12. < b>与< /b>之间的文本被加粗。
			
    13. < i>< /i>之间的文本为斜体。
		
    14. < table>< /table>标记用来定义一个表格。
    
    15. < blockquote>与< /blockquote>设置文字段落的缩进，比如显示引用的内容。
    
	16. < ul>与< /ul>设置无序列表，即每个列项的前面有一个圆点符号，其中每一个列表项使用< li>< /li>
	
	17. < ol>与< /ol>设置有序列表，即每个列项的前面用数字标识，其中每一个列表项使用< li>< /li>
			
    18. < h1 align="center"(right,left)>< /h1>align属性用来控制标题的显示位置，这个属性也可以用在段落< p>上。
    
	19. < body text="#000000" bgcolor="#808080">设置文字以及背景的颜色。

	
	20. < u>与< /u>文字以下划线的方式显示。
	
	21. < s>与< /s>文字加下删除线的方式显示。
	
	22. < big>与< /big>文字以放大方式显示。
	
	23. < small>与< /small>文字以缩小方式显示。
	
	24. < strong>与< /strong>文字以加强强调方式显示。
	
	25. < em>与< /em>文字以强调方式显示。
	
	26. < address>与< /adress>用来显示电子邮箱地址或网址。
	
	27. < code>与< /code>用来说明代码与指令。
	
	28. < sub>与< /sub>为下标标记，用于将数字缩小后显示于下方。
	
	29. < sup>与< /sup>为上标标记，用于将数字缩小后显示于上方。

	30. 特殊符号的表示方法：&lt； 表示小于，&gt；表示大于，&copy；表示版权符号，&nbsp；表示空格，&divide；表示除号，&permil；表示千分号，&harr；表示双向的箭头。在DW中输入&会有提示，要记住几个常用的。
	
	31. < a href="#目标名称">链接文字< /a>与< a name="目标名称">链接目标文字< /a>表示设置页面内部的特定目标的超链接，如在页面底部设置返回顶部的超链接,同理也可以设置页面之间的超链接。
	
	32. < img src="图片名称" border="边界值（0）" usemap="#map1(热点区域的名字)">
	    < map name="Map1">
        < area shape="poly" coords="23,12,45,67,97" href="hah.jpg">   
        此三行可用于建立热点区域，给图片上想要的位置建立超链接，其热点区域可以通过dw工具来划分，href 表示链接的地址，shape属性为控制划分区域的形状，其设置值有三个，rect（矩形），circle（圆形），poly(多边形)，如果是矩形，coords属性中要填入四个数字，分别代表左，上，右，下，来确定选定的区域，单位是像素。
		
<table><tr><td bgcolor=bbbddd> 
![](http://i.imgur.com/JKSyjRB.png)
</tr></table>
    　　网页主要由3个部分组成：结构（Structure）,表现（Presentation）和行为（Behavior），“结构”决定了网页是什么；“表现”决定了网页看起来是什么样子；“行为”决定了网页做什么。不严谨地说，“结构”、“表现”、“行为”分别对应三种技术，即(x)html、CSS、JavaScript，也就是说，(x)html用来决定网页的结构和内容，CSS用来设定网页的表现形式JavaScript用来控制网页的行为。三者关系如图1.4所示。
![](http://i.imgur.com/FULMmBa.png)

    主流显示分辨率在1024*768
![](http://i.imgur.com/o8YHbDf.png)



</tr></table>