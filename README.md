# HTML基础
## 目录
###### 学习整理1.0
1、[常用的标签01-复习：i](https://echo002.github.io/HTML/01HTML%E5%9F%BA%E7%A1%80%E5%85%A5%E9%97%A8/demo01/demo01.html)
##### 
	1、h1最重要，仅次于title只能写一个h1；一般页面标题只使用h1 h2 h3、其他的不予考虑;
	h1将影响搜索引擎的显示依次不重要
	2、浏览器中两个及以上的空格、换行都会当成一个空格来计算，需要用br来表示换行、hr表示换行水平线（自结束）
	3、段落标签用于表示内容中的一个段落，独占一行
2、[图片标签-复习：i](https://echo002.github.io/HTML/01HTML%E5%9F%BA%E7%A1%80%E5%85%A5%E9%97%A8/demo02/demo02.html)
#####
	1、利用img标签（自结束）来应用一个图片
	属性：
		src:设置一个外部图片的路径
		<../返回上一级目录（返回几级写几次）>
		alt:设置在图片不能显示时的描述（搜索引擎通过此识别），否则不会显示
		width、height:修改图片的高度和宽度、只设置一个的话等比例缩小 同时指定需拉伸（）不建议设置
	2、图片的格式：
		JPEG（JPG）支持的颜色多，可压缩，不透明，一般用来保存照片
		GIF支持的颜色少，只支持简单的透明（直线的透明），支持动态图
		PNG支持颜色多并且支持复杂透明
		图片使用原则
		效果不一致使用效果好的；效果一致使用小的
3、[常用的标签02-复习：i](https://echo002.github.io/HTML/01HTML%E5%9F%BA%E7%A1%80%E5%85%A5%E9%97%A8/demo03/demo03.html)
#####	
	1、meta的作用
		charset:设置字符集
		name、content:关键字,搜索引擎据此判断信息，不会影响排名
4、[xHTML语法规范-复习：i](https://echo002.github.io/HTML/01HTML%E5%9F%BA%E7%A1%80%E5%85%A5%E9%97%A8/demo04/demo04.html)
#####
	见网页
5、[内联框架-复习：i](https://echo002.github.io/HTML/01HTML%E5%9F%BA%E7%A1%80%E5%85%A5%E9%97%A8/demo05/demo05.html)
#####	
	1、使用内联框架可以引入一个外部的页面（iframe）
		src:指向外部页面
		现实中不推荐 内联框架的内容不会被搜索引擎和检索
		参数：width、height、name
	2、如何表示上级目录 
		../表示源文件所在目录的上一级目录
		../../表示源文件所在目录的上上级目录，以此类推。
	本实例将链接到02图片标签
6、[超链接-复习：i](https://echo002.github.io/HTML/01HTML%E5%9F%BA%E7%A1%80%E5%85%A5%E9%97%A8/demo06/demo06.html)
#####
	1、使用a标签来创建一个超链接
		href:指向链接跳转的目标地址，也可以写一个相对路径
		target:指定打开链接的位置
		可选值：_self当前页打开
			   _blank新的窗口中打开链接
		可以设置为一个内联框架的name属性值，链接将会在内联框架中打开
	2、center标签中的内容，会默认在页面居中显示（不推荐）
	3、创建超链接地址时，如果地址不确定，可以先使用#来代替（点击后跳转到当前页面的顶部）
7、CSS简介