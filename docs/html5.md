####一.html5的优势

1.	更简单的但是更强的表现能力
2.	减少对外部插件的依赖(Flash)
3.	本地存储
4.	等等。。。

####二.更简单的头标签

html4的头部标签:

	<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
	
	<html xmlns="http://www.w3.org/1999/xhtml">
	
	<body>
		xxx
	</body>
	</html>
	
	
html5的头部标签:	

	<!DOCTYPE html>
	<html>
	<body>
		xxxx
	</body>
	</html>
	
我们网站已经支持HTML5了：curl "www.alibaba.com"

####三.更富表现力的标签

######(一).视频 video
	<video src="movie.ogg" controls="controls"/>
参看basic.html

######(二).表单输入项
表单的输入框增加了多种类型，轻松实现之前使用javascript才能实现的功能。

1.	email
2.	url
3.	range
4.	number
5.	date

######(三).表单属性
对于输入框来说：可以添加required
	
	required="required" 
属性，来使表单必填。

也可以添加placeholder属性，来显示默认提示 

	placeholder="Search W3School" 

####四.客户端存储
HTML5之前客户端存储只能通过cookie实现，但是cookie会随每次请求发给客户端，造成网络开销。

HTML5提供了两种类型的本地存储:

1.	localStorage 没有时间限制的存储
2.	sessionStorage 会话级别的本地存储

两者均可通过key value形式访问，API如下：

	localStorage.setItem("key","value");
	localStorage.getItem("key");
	localStorage.removeItem("key");
	localStorage.clear();
	
可以通过开发者工具查看localStorage中的数据。

localStorage的大小限制是5M。

####五.等等
Google It