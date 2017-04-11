# login

background-image:url();
background-repeat:no-repeate;
background-attachment:fixed;
background-position:left center;
background-size:100px;
background-color:red;
一定要注意书写顺序，否则很可能无正常效果
多个背景图片可以用  逗号  分开写




<' background-image '>：
指定对象的背景图像。可以是真实图片路径或使用渐变创建的“背景图像”
<' background-position '>：
指定对象的背景图像位置。
<' background-size '>：
指定对象的背景图像的尺寸大小。
<' background-repeat '>：
指定对象的背景图像如何铺排填充。
<' background-attachment '>：
指定对象的背景图像是随对象内容滚动还是固定的。
<' background-origin '>：
指定对象的背景图像显示的原点。
<' background-clip '>：
指定对象的背景图像向外裁剪的区域。
<' background-color '>：
指定对象的背景颜色。

缩写方式
background:url(test1.jpg) no-repeat scroll 10px 20px/50px 60px content-box padding-box,
	   url(test1.jpg) no-repeat scroll 10px 20px/70px 90px content-box padding-box,
	   url(test1.jpg) no-repeat scroll 10px 20px/110px 130px content-box padding-box #aaa;
