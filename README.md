mobileTech
==========

A useful tools or tips list for mobile web application developing

这个项目收集移动端开发所需要的一些资源与小技巧


一些非常重要的工具类网站

 [html5与css3技术应用评估](http://html5please.com/ "html5与css3技术应用评估")
 
 [各种奇妙的hack](http://browserhacks.com/ "各种奇妙的hack")
 
 [几乎所有设备的屏幕尺寸与像素密度表](http://en.wikipedia.org/wiki/List_of_displays_by_pixel_density "几乎所有设备的屏幕尺寸与像素密度表")
 
 [ios端移动设备参数速查](http://ivomynttinen.com/blog/the-ios-design-cheat-sheet-volume-2/ "ios端移动设备参数速查")
 
 [浏览器兼容表](http://www.quirksmode.org/compatibility.html "浏览器兼容表")
 
 [移动设备查询器](https://deviceatlas.com/device-data/devices "移动设备查询器")
 
 [移动设备适配库](http://51degrees.codeplex.com/ "移动设备适配库")
 
 
 [viewport与设备尺寸在线检测器](https://deviceatlas.com/device-data/devices "viewport与设备尺寸在线检测器")
 
 [html5移动端兼容性速查](http://mobilehtml5.org/ "html5移动端兼容性速查")
 
 [在线转换字体](http://www.fontsquirrel.com/tools/webfont-generator "在线转换字体")
 
 [css3选择器测试](http://tools.css3.info/selectors-test/test.html "css3选择器测试")
 
 [兼容性速查表](http://caniuse.com/ "兼容性速查表")
 
 [浏览器的一些独特参数](http://www.browserscope.org/ "浏览器的一些独特参数")
 
 [各种各样的媒体查询收集](http://nmsdvid.com/snippets/ "各种各样的媒体查询收集")
 
 [css3动画在线制作器](http://ecd.tencent.com/css3/tools.html "css3动画在线制作器")
 
 [css3渐变在线制作器](http://www.colorzilla.com/gradient-editor/ "css3渐变在线制作器")
 

[移动端手势表](http://ww1.sinaimg.cn/bmiddle/c2c57f68jw1e4fh7dmw12j20fi2w6qe1.jpg "移动端手势表")


[webkit独有的样式分析](http://ued.ctrip.com/blog/wp-content/webkitcss/ "webkit独有的样式分析")


##响应式测试工具

 [resize添加到收藏夹后，可直接在浏览器中出现各种分辨率的选择工具来查看不同分辨率下的页面效果](http://lab.maltewassermann.com/viewport-resizer/ "resize")
 [http://beta.screenqueri.es/](http://beta.screenqueri.es/ "resize")
 [http://responsivepx.com](http://responsivepx.com "resize")
 [http://www.responsinator.com/](http://www.responsinator.com/ "resize")
 [http://resizemybrowser.com/](http://resizemybrowser.com/ "resize")
  [https://quirktools.com/screenfly/](https://quirktools.com/screenfly/ "resize")

一篇webapp开发的最佳实践与中文总结
==========
<http://blog.forecast.io/its-not-a-web-app-its-an-app-you-install-from-the-web/>
<http://lyric.im/best-practice-for-web-app-development/>

本资料很多引用了指尖上的js系列，在此向作者表示感谢
==========

 [http://www.cnblogs.com/pifoo/archive/2011/05/23/webkit-touch-event-1.html](http://www.cnblogs.com/pifoo/archive/2011/05/23/webkit-touch-event-1.html "article1")
 
 [http://www.cnblogs.com/pifoo/archive/2011/05/22/webkit-touch-event-2.html](http://www.cnblogs.com/pifoo/archive/2011/05/22/webkit-touch-event-2.html "article2")
 
 [http://www.cnblogs.com/pifoo/archive/2011/05/22/webkit-touch-event-3.html](http://www.cnblogs.com/pifoo/archive/2011/05/22/webkit-touch-event-3.html "article3")


meta标签，这些meta标签在开发webapp时起到非常重要的作用

  <meta content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0" name="viewport" />
	<meta content="yes" name="apple-mobile-web-app-capable" />
	<meta content="black" name="apple-mobile-web-app-status-bar-style" />
	<meta content="telephone=no" name="format-detection" />

 

第一个meta标签表示：强制让文档的宽度与设备的宽度保持1:1，并且文档最大的宽度比例是1.0，且不允许用户点击屏幕放大浏览；
~~尤其要注意的是content里多个属性的设置一定要用分号+空格来隔开，如果不规范将不会起作用。~~

注意根据[public_00](http://www.weibo.com/avajayam "ava")提供的资料补充，content使用分号作为分隔，在老的浏览器是支持的，但不是规范写法。
规范的写法应该是使用逗号分隔，参考 
<http://developer.apple.com/library/safari/#documentation/appleapplications/reference/SafariHTMLRef/Articles/MetaTags.html>
<http://developer.android.com/guide/webapps/targeting.html>






其中：
* width - viewport的宽度
* height - viewport的高度
* initial-scale - 初始的缩放比例
* minimum-scale - 允许用户缩放到的最小比例
* maximum-scale - 允许用户缩放到的最大比例
* user-scalable - 用户是否可以手动缩放
第二个meta标签是iphone设备中的safari私有meta标签，它表示：允许全屏模式浏览；
第三个meta标签也是iphone的私有标签，它指定的iphone中safari顶端的状态条的样式；
第四个meta标签表示：告诉设备忽略将页面中的数字识别为电话号码

在设置了initial-scale=1 之后，我们终于可以以1:1 的比例进行页面设计了。
关于viewport，还有一个很重要的概念是：iphone 的safari 浏览器完全没有滚动条，而且不是简单的“隐藏滚动条”，
是根本没有这个功能。iphone 的safari 浏览器实际上从一开始就完整显示了这个网页，然后用viewport 查看其中的一部分。
当你用手指拖动时，其实拖的不是页面，而是viewport。浏览器行为的改变不止是滚动条，交互事件也跟普通桌面不一样。
(请参考：指尖的下JS 系列文章)

其中viewport相关的知识也可以参考我的文章
==========
[此像素非彼像素](http://www.w3cplus.com/css/A-pixel-is-not-a-pixel-is-not-a-pixel.html "pixel")

##点击与click事件

对于a标记的点击导航，默认是在onclick事件中处理的。而移动客户端对onclick的响应相比PC浏览器有着明显的几百毫秒延迟。

在移动浏览器中对触摸事件的响应顺序应当是： 

	ontouchstart -> ontouchmove -> ontouchend -> onclick

因此，如果确实要加快对点击事件的响应，就应当绑定ontouchend事件。

使用click会出现绑定点击区域闪一下的情况，解决：给该元素一个样式如下

	-webkit-tap-highlight-color: rgba(0,0,0,0);
	
如果不使用click，也不能简单的用touchstart或touchend替代，需要用touchstart的模拟一个click事件，并且不能发生touchmove事件，或者用zepto中的tap（轻击）事件。

	body
	{
	-webkit-overflow-scrolling: touch;
	}
	
用iphone或ipad浏览很长的网页滚动时的滑动效果很不错吧？不过如果是一个div，然后设置

	height:200px;overflow:auto;
	
的话，可以滚动但是完全没有那滑动效果，很郁闷吧？
我看到很多网站为了实现这一效果，用了第三方类库，最常用的是iscroll（包括新浪手机页，百度等）
我一开始也使用，不过自从用了-webkit-overflow-scrolling: touch;样式后，就完全可以抛弃第三方类库了，把它加在body{}区域，所有的overflow需要滚动的都可以生效了。

详见  [http://johanbrook.com/browsers/native-momentum-scrolling-ios-5/ ](http://johanbrook.com/browsers/native-momentum-scrolling-ios-5/  "css3渐变在线制作器")页面描述



	<link rel="apple-touch-icon-precomposed" href="http://www.xxx.com/App_icon_114.png" />
	<link rel="apple-touch-icon-precomposed" sizes="72x72" href="http://www.xxx.com/App_icon_72.png" />
	<link rel="apple-touch-icon-precomposed" sizes="114x114" href="http://www.xxx.com/App_icon_114.png" />
	
这个属性是当用户把连接保存到手机桌面时使用的图标，如果不设置，则会用网页的截图。有了这，就可以让你的网页像APP一样存在手机里了

	<link rel="apple-touch-startup-image" href="/img/startup.png" />
	
这个是APP启动画面图片，用途和上面的类似，如果不设置，启动画面就是白屏，图片像素就是手机全屏的像素

	<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
	
这个描述是表示打开的web app的最上面的时间、信号栏是黑色的，当然也可以设置其它参数，详细参数说明在：

[http://developer.apple.com/library/safari/#documentation/appleapplications/reference/SafariHTMLRef/Articles/MetaTags.html ](http://developer.apple.com/library/safari/#documentation/appleapplications/reference/SafariHTMLRef/Articles/MetaTags.html  "css3渐变在线制作器")里

	<meta name="apple-touch-fullscreen" content="yes" />
	<meta name="apple-mobile-web-app-capable" content="yes" />
 

这2个描述也很有用的，如果没有它，你的web app会用safari浏览器打开，有了它，就会用独立进程的无地址栏的打开，完全可以和普通的APP比拟了

下面还有个不错的css，是用来区分视网膜屏幕的，这样你可以在iphone这样的手机里载入2x的图片，就不会模糊了

	@media only screen and (-webkit-min-device-pixel-ratio:1.5),only screen and (min--moz-device-pixel-ratio:1.5),only screen and (min-device-pixel-ratio:1.5),only screen and (min-resolution:200dpi)
	{
	#logo{background-image: url(logo@2x.png);}
	}
 

##样式表:

	<link rel=”apple-touch-startup-image” href=”startup.png” /> // 设置开始页面图片
	<link rel=”apple-touch-icon” href=”iphon_tetris_icon.png”/> // 在设置书签的时候可以显示好看的图标
	<link rel="stylesheet" media="all and (orientation:portrait)" href="portrait.css">    // 肖像模式样式
	<link rel="stylesheet" media="all and (orientation:landscape)"href="landscape.css"   // 风景模式样式

	//竖屏时使用的样式
	<style media="all and (orientation:portrait)" type="text/css">
	#landscape { display: none; }
	</style>

	//横屏时使用的样式
	<style media="all and (orientation:landscape)" type="text/css">
	#portrait { display: none; }
	</style>

##手机浏览器常用手势动作监听封装(配合zepto,来自mansonchor)
<http://wo.poco.cn/manson/post/id/268780>
##事件 ： (请参考：指尖的下JS 系列文章)

##手势事件
* touchstart            //当手指接触屏幕时触发
* touchmove           //当已经接触屏幕的手指开始移动后触发
* touchend             //当手指离开屏幕时触发
* touchcancel

##触摸事件
* gesturestart          //当两个手指接触屏幕时触发
* gesturechange      //当两个手指接触屏幕后开始移动时触发
* gestureend

##屏幕旋转事件
* onorientationchange    

##检测触摸屏幕的手指何时改变方向
* orientationchange      

##touch事件支持的相关属性
* touches
* targetTouches
* changedTouches
* clientX　　　　// X coordinate of touch relative to the viewport (excludes scroll offset)
* clientY　　　　// Y coordinate of touch relative to the viewport (excludes scroll offset)
* screenX　　　 // Relative to the screen
* screenY 　　  // Relative to the screen
* pageX　　 　　// Relative to the full page (includes scrolling)
* pageY　　　　 // Relative to the full page (includes scrolling)
* target　　　　 // Node the touch event originated from
* identifier　　   // An identifying number, unique to each touch event
 

* 屏幕旋转事件：onorientationchange
添加屏幕旋转事件侦听，可随时发现屏幕旋转状态（左旋、右旋还是没旋）。例子：

##判断屏幕是否旋转
	function orientationChange() {
		switch(window.orientation) {
		　　case 0:
				alert("肖像模式 0,screen-width: " + screen.width + "; screen-height:" + screen.height);
				break;
		　　case -90:
				alert("左旋 -90,screen-width: " + screen.width + "; screen-height:" + screen.height);
				break;
		　　case 90:
				alert("右旋 90,screen-width: " + screen.width + "; screen-height:" + screen.height);
				break;
		　　case 180:
			　　alert("风景模式 180,screen-width: " + screen.width + "; screen-height:" + screen.height);
			　　break;
		};<br>};
##添加事件监听
	addEventListener('load', function(){
		orientationChange();
		window.onorientationchange = orientationChange;
	});
 

##隐藏地址栏 & 处理事件的时候，防止滚动条出现：

	// 隐藏地址栏  & 处理事件的时候 ，防止滚动条出现
	addEventListener('load', function(){
			setTimeout(function(){ window.scrollTo(0, 1); }, 100);
	});
##双手指滑动事件：

	// 双手指滑动事件
	addEventListener('load',　　function(){ window.onmousewheel = twoFingerScroll;},
		false              // 兼容各浏览器，表示在冒泡阶段调用事件处理程序 (true 捕获阶段)
	);
	function twoFingerScroll(ev) {
		var delta =ev.wheelDelta/120;              //对 delta 值进行判断(比如正负) ，而后执行相应操作
		return true;
	};
##判断是否为iPhone：

	// 判断是否为 iPhone ：
	function isAppleMobile() {
		return (navigator.platform.indexOf('iPad') != -1);
	};
##localStorage:
	var v = localStorage.getItem('n') ? localStorage.getItem('n') : "";   // 如果名称是  n 的数据存在 ，则将其读出 ，赋予变量  v  。
	localStorage.setItem('n', v);                                           // 写入名称为 n、值为  v  的数据
	localStorage.removeItem('n');                                           // 删除名称为  n  的数据
##使用特殊链接：
如果你关闭自动识别后 ，又希望某些电话号码能够链接到 iPhone 的拨号功能 ，那么可以通过这样来声明电话链接 ,

	<a href="tel:12345654321">打电话给我</a>
	<a href="sms:12345654321">发短信</a>
或用于单元格：
	<td onclick="location.href='tel:122'">
##自动大写与自动修正
要关闭这两项功能，可以通过autocapitalize 与autocorrect 这两个选项：

	<input type="text" autocapitalize="off" autocorrect="off" />
 
##WebKit CSS:
①“盒模型”的具体描述性质的包围盒块内容，包括边界，填充等等。

	-webkit-border-bottom-left-radius: radius;
	-webkit-border-top-left-radius: horizontal_radius vertical_radius;
	-webkit-border-radius: radius;      //容器圆角
	-webkit-box-sizing: sizing_model; 边框常量值：border-box/content-box
	-webkit-box-shadow: hoff voff blur color; //容器阴影（参数分别为：水平X 方向偏移量；垂直Y 方向偏移量；高斯模糊半径值；阴影颜色值）
	-webkit-margin-bottom-collapse: collapse_behavior; 常量值：collapse/discard/separate
	-webkit-margin-start: width;
	-webkit-padding-start: width;
	-webkit-border-image: url(borderimg.gif) 25 25 25 25 round/stretch round/stretch;
	-webkit-appearance: push-button;   //内置的CSS 表现，暂时只支持push-button
 

②“视觉格式化模型”描述性质，确定了位置和大小的块元素。

	direction: rtl
	unicode-bidi: bidi-override; 常量：bidi-override/embed/normal
 

③“视觉效果”描述属性，调整的视觉效果块内容，包括溢出行为，调整行为，能见度，动画，变换，和过渡。

	clip: rect(10px, 5px, 10px, 5px)
	resize: auto; 常量：auto/both/horizontal/none/vertical
	visibility: visible; 常量: collapse/hidden/visible
	-webkit-transition: opacity 1s linear; 动画效果 ease/linear/ease-in/ease-out/ease-in-out
	-webkit-backface-visibility: visibler; 常量：visible(默认值)/hidden
	-webkit-box-reflect: right 1px; 镜向反转
	-webkit-box-reflect: below 4px -webkit-gradient(linear, left top, left bottom,
	from(transparent), color-stop(0.5, transparent), to(white));
	-webkit-mask-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0,0,0,1)), to(rgba(0,0,0,0)));;   //CSS 遮罩/蒙板效果
	-webkit-mask-attachment: fixed; 常量：fixed/scroll
	-webkit-perspective: value; 常量：none(默认)
	-webkit-perspective-origin: left top;
	-webkit-transform: rotate(5deg);
	-webkit-transform-style: preserve-3d; 常量：flat/preserve-3d; (2D 与3D)
 

④“生成的内容，自动编号，并列出”描述属性，允许您更改内容的一个组成部分，创建自动编号的章节和标题，和操纵的风格清单的内容。

	content: “Item” counter(section) ” “;
	This resets the counter.
	First section
	>two section
	three section
	counter-increment: section 1;
	counter-reset: section;
 

⑤“分页媒体”描述性能与外观的属性，控制印刷版本的网页，如分页符的行为。

	page-break-after: auto; 常量：always/auto/avoid/left/right
	page-break-before: auto; 常量：always/auto/avoid/left/right
	page-break-inside: auto; 常量：auto/avoid
 

⑥“颜色和背景”描述属性控制背景下的块级元素和颜色的文本内容的组成部分。

	-webkit-background-clip: content; 常量：border/content/padding/text
	-webkit-background-origin: padding; 常量：border/content/padding/text
	-webkit-background-size: 55px; 常量：length/length_x/length_y
 

⑦ “字型”的具体描述性质的文字字体的选择范围内的一个因素。报告还描述属性用于下载字体定义。

	unicode-range: U+00-FF, U+980-9FF;
⑧“文本”描述属性的特定文字样式，间距和自动滚屏。

	text-shadow: #00FFFC 10px 10px 5px;
	text-transform: capitalize; 常量：capitalize/lowercase/none/uppercase
	word-wrap: break-word; 常量：break-word/normal
	-webkit-marquee: right large infinite normal 10s; 常量：direction(方向) increment(迭代次数) repetition(重复) style(样式) speed(速度);
	-webkit-marquee-direction: ahead/auto/backwards/down/forwards/left/reverse/right/up
	-webkit-marquee-incrementt: 1-n/infinite(无穷次)
	-webkit-marquee-speed: fast/normal/slow
	-webkit-marquee-style: alternate/none/scroll/slide
	-webkit-text-fill-color: #ff6600; 常量：capitalize, lowercase, none, uppercase
	-webkit-text-security: circle; 常量：circle/disc/none/square
	-webkit-text-size-adjust: none; 常量:auto/none;
	-webkit-text-stroke: 15px #fff;
	-webkit-line-break: after-white-space; 常量：normal/after-white-space
	-webkit-appearance: caps-lock-indicator;
	-webkit-nbsp-mode: space; 常量： normal/space
	-webkit-rtl-ordering: logical; 常量：visual/logical
	-webkit-user-drag: element; 常量：element/auto/none
	-webkit-user-modify: read- only; 常量：read-write-plaintext-only/read-write/read-only
	-webkit-user-select: text; 常量：text/auto/none
 

⑨“表格”描述的布局和设计性能表的具体内容。

	-webkit-border-horizontal-spacing: 2px;
	-webkit-border-vertical-spacing: 2px;
	-webkit-column-break-after: right; 常量：always/auto/avoid/left/right
	-webkit-column-break-before: right; 常量：always/auto/avoid/left/right
	–webkit-column-break-inside: logical; 常量：avoid/auto
	-webkit-column-count: 3; //分栏
	-webkit-column-rule: 1px solid #fff;
	style:dashed,dotted,double,groove,hidden,inset,none,outset,ridge,solid
 

⑩“用户界面”描述属性，涉及到用户界面元素在浏览器中，如滚动文字区，滚动条，等等。报告还描述属性，范围以外的网页内容，如光标的标注样式和显示当您按住触摸触摸
目标，如在iPhone上的链接。

	-webkit-box-align: baseline,center,end,start,stretch 常量：baseline/center/end/start/stretch
	-webkit-box-direction: normal;常量：normal/reverse
	-webkit-box-flex: flex_valuet
	-webkit-box-flex-group: group_number
	-webkit-box-lines: multiple; 常量：multiple/single
	-webkit-box-ordinal-group: group_number
	-webkit-box-orient: block-axis; 常量：block-axis/horizontal/inline-axis/vertical/orientation
	–webkit-box-pack: alignment; 常量：center/end/justify/start
 

动画过渡
这是 Webkit 中最具创新力的特性：使用过渡函数定义动画。

	-webkit-animation: title infinite ease-in-out 3s;
	animation 有这几个属性：
	-webkit-animation-name： //属性名，就是我们定义的keyframes
	-webkit-animation-duration：3s //持续时间
	-webkit-animation-timing-function： //过渡类型：ease/ linear(线性) /ease-in(慢到快)/ease-out(快到慢) /ease-in-out(慢到快再到慢) /cubic-bezier
	-webkit-animation-delay：10ms //动画延迟(默认0)
	-webkit-animation-iteration-count： //循环次数(默认1)，infinite 为无限
	-webkit-animation-direction： //动画方式：normal(默认 正向播放)； alternate(交替方向，第偶数次正向播放，第奇数次反向播放)
 

这些同样是可以简写的。但真正让我觉的很爽的是keyframes，它能定义一个动画的转变过程供调用，过程为0%到100%或from(0%)到to(100%)。简单点说，只要你有想法，你想让元素在这个过程中以什么样的方式改变都是很简单的。

	-webkit-transform: 类型（缩放scale/旋转rotate/倾斜skew/位移translate）
	scale(num,num) 放大倍率。scaleX 和 scaleY(3)，可以简写为：scale(* , *)
	rotate(*deg) 转动角度。rotateX 和 rotateY，可以简写为：rotate(* , *)
	Skew(*deg) 倾斜角度。skewX 和skewY，可简写为：skew(* , *)
	translate(*,*) 坐标移动。translateX 和translateY，可简写为：translate(* , *)。
 
 
##利用media query监听

media query相信大部分人已经使用过了。其实javascript可以配合media query这么用：

	var mql = window.matchMedia("(orientation: portrait)");
	mql.addListener(handleOrientationChange);
	handleOrientationChange(mql); 
	function handleOrientationChange(mql) {
	  if (mql.matches) {
	    alert('The device is currently in portrait orientation ')
	  } else {
	    alert('The device is currently in landscape orientation')
	  }}

我个人理解，是借助了media query接口做的事件监听，所以很强大！

##锁定 viewport

	ontouchmove="event.preventDefault()" //锁定viewport，任何屏幕操作不移动用户界面（弹出键盘除外）。
 

##被点击元素的外观变化，可以使用样式来设定：

	-webkit-tap-highlight-color: 颜色
 

##侦测iPhone/iPod
开发特定设备的移动网站，首先要做的就是设备侦测了。下面是使用Javascript侦测iPhone/iPod的UA，然后转向到专属的URL。

	if((navigator.userAgent.match(/iPhone/i)) || (navigator.userAgent.match(/iPod/i))) {
	　　if (document.cookie.indexOf("iphone_redirect=false") == -1) {
	　　　　window.location = "http://m.example.com";
	　　}
	}
 

虽然Javascript是可以在水果设备上运行的，但是用户还是可以禁用。它也会造成客户端刷新和额外的数据传输，所以下面是服务器端侦测和转向：

	if(strstr($_SERVER['HTTP_USER_AGENT'],'iPhone') || strstr($_SERVER['HTTP_USER_AGENT'],'iPod')) {
	　　header('Location: http://yoursite.com/iphone');
	　　exit();
	}
##阻止旋转屏幕时自动调整字体大小

	html, body, form, fieldset, p, div, h1, h2, h3, h4, h5, h6 {-webkit-text-size-adjust:none;}
 

##iPhone才识别的CSS
如果不想设备侦测，可以用CSS媒体查询来专为iPhone/iPod定义样式。

	@media screen and (max-device-width: 480px) {}
##缩小图片
网站的大图通常宽度都超过480像素，如果用前面的代码限制了缩放，这些图片在iPhone版显示显然会超过屏幕。好在iPhone机能还够，我们可以用CSS让iPhone自动将大图片缩小显示。


	@media screen and (max-device-width: 480px){
	　　img{max-width:100%;height:auto;}
	}
 

##模拟:hover伪类
因为iPhone并没有鼠标指针，所以没有hover事件。那么CSS :hover伪类就没用了。但是iPhone有Touch事件，onTouchStart 类似 onMouseOver，onTouchEnd 类似 onMouseOut。所以我们可以用它来模拟hover。使用Javascript：

	var myLinks = document.getElementsByTagName('a');
	for(var i = 0; i < myLinks.length; i++){
	　　myLinks[i].addEventListener(’touchstart’, function(){this.className = “hover”;}, false);
	　　myLinks[i].addEventListener(’touchend’, function(){this.className = “”;}, false);
	}
然后用CSS增加hover效果：

	a:hover, a.hover { /* 你的hover效果 */ }

这样设计一个链接，感觉可以更像按钮。并且，这个模拟可以用在任何元素上。

##flexbox布局模板

 [flex模板](http://jsbin.com/ibuwol/2/edit "article5")
 
 [深入了解flex布局](http://www.w3cplus.com/blog/666.html "article6")
 
 
 
 ##利用高质量图片优化retina屏幕的显示(来自大漠)
 
 

 [经典的文章](http://miekd.com/articles/using-css-sprites-to-optimize-your-website-for-retina-displays/ "article5")

 [使用CSS3的background-size优化苹果的Retina屏幕的图像显示](http://www.w3cplus.com/css/css-background-size-graphics.html "article5") 

 [使用css sprites来优化你的网站在Retina屏幕下显示](http://www.w3cplus.com/css/using-css-sprites-to-optimize-your-website-for-retina-displays.html "article5") 
  
  [一个案例](http://alexthorpe.com/uncategorized/css-sprites-for-retina-display-devices/683/ "article5") 
 

##安卓中viewport的width大于device-width时文字无故折行

<http://www.iunbug.com/archives/2013/04/23/798.html>



##active的兼容(来自薛端阳)

今天发现，要让a链接的Css active伪类生效，只需要给这个a链接的touch系列的任意事件touchstart/touchend绑定一个空的匿名方法即可hack成功

	<style>
	a {
	color: #000;
	}
	a:active {
	color: #fff;
	}
	</style>
	<a herf=”asdasd”>asdasd</a>
	<script>
	var a=document.getElementsByTagName(‘a’);
	for(var i=0;i<a.length;i++){
	a[i].addEventListener(‘touchstart’,function(){},false);
	}
	</script>

##消除transition闪屏

两个方法

	-webkit-transform-style: preserve-3d;
	/*设置内嵌的元素在 3D 空间如何呈现：保留 3D*/
	-webkit-backface-visibility:?hidden;
	/*（设置进行转换的元素的背面在面对用户时是否可见：隐藏）*/
	
##消除ie10里面的那个叉号
[http://msdn.microsoft.com/en-us/library/windows/apps/hh767361.aspx](http://msdn.microsoft.com/en-us/library/windows/apps/hh767361.aspx "article4")

	input:-ms-clear{display:none;}
	
##关于ios与os端字体的优化(横竖屏会出现字体加粗不一致等)
[http://blog.sina.com.cn/s/blog_6da647a601011u4v.html](http://blog.sina.com.cn/s/blog_6da647a601011u4v.html "article5")
[http://stackoverflow.com/questions/3220662/uiwebview-font-is-thinner-in-portrait-than-landscape](http://stackoverflow.com/questions/3220662/uiwebview-font-is-thinner-in-portrait-than-landscape "article5")
 

##js事件
click 事件普遍 300ms 的延迟
在手机上绑定click 事件，会使得操作有300ms 的延迟，体验并不是很好。
开发者大多数会使用封装的 tap 事件来代替click 事件，所谓的 tap 事件由 touchstart 事件 + touchmove 判断 + touchend 事件封装组成

##ios点击会慢300ms

 [https://developers.google.com/mobile/articles/fast_buttons?hl=de-DE](https://developers.google.com/mobile/articles/fast_buttons?hl=de-DE "article5")
 [http://stackoverflow.com/questions/12238587/eliminate-300ms-delay-on-click-events-in-mobile-safari](http://stackoverflow.com/questions/12238587/eliminate-300ms-delay-on-click-events-in-mobile-safari "article5")

使用css3动画的时尽量利用3D加速，从而使得动画变得流畅。动画过程中的动画闪白可以通过backface-visibility 隐藏。

	-webkit-transform-style: preserve-3d;
	-webkit-backface-visibility: hidden;
 

##常见的IPHONE 和 Android屏幕参数。

* 设备	分辨率	设备像素比率
* Android LDPI	320×240	0.75
* Iphone 3 & Android MDPI	320×480	1
* Android HDPI	480×800	1.5
* Iphone 4	960×640	2.0

Iphone 4的一个 CSS 像素实际上表现为一块 2×2 的像素。所以图片像是被放大2倍一样，模糊不清晰。

解决办法：

1、页面引用


	<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 0.75)" href="ldpi.css" />
	<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 1.0)" href="mdpi.css" />
	<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 1.5)" href="hdpi.css" />
	<link rel="stylesheet" media="screen and (-webkit-device-pixel-ratio: 2.0)" href="retina.css" />
 
2、CSS文件里

	#header {
		background:url(mdpi/bg.png);
	}

	@media screen and (-webkit-device-pixel-ratio: 1.5) {
		/*CSS for high-density screens*/
		#header {
			background:url(hdpi/bg.png);
		}
	}
	
##ie10的特殊鼠标事件

[http://www.mansonchor.com/blog/blog_detail_73.html](http://www.mansonchor.com/blog/blog_detail_73.html "article5")

##不让android识别邮箱

	<meta content="email=no" name="format-detection" />
	
##禁止ios弹出各种操作窗口

	-webkit-touch-callout:none
##禁止用户选中文字

	-webkit-user-select:none
	
##动画效果中，使用translate比使用定位性能高

<http://paulirish.com/2012/why-moving-elements-with-translate-is-better-than-posabs-topleft/>

##拿到滚动条

	window.scrollY
	window.scrollX
 
 比如要绑定一个touchmove的事件，正常的情况下类似这样(来自呼吸二氧化碳)
 
	$('div').on('touchmove', function(){
	//.….code
	{});
	
而如果中间的code需要处理的东西多的话，fps就会下降影响程序顺滑度，而如果改成这样

	$('div').on('touchmove', function(){
	setTimeout(function(){
	//.….code
	},0);
	{});
	
把代码放在setTimeout中，会发现程序变快.

##关于ios系统中，webapp启动图片在不同设备上的适应性设置

http://stackoverflow.com/questions/4687698/mulitple-apple-touch-startup-image-resolutions-for-ios-web-app-esp-for-ipad/10011893#10011893

##关于ios系统中，中文输入法输入英文时，字母之间可能会出现一个六分之一空格(焦点科技葛亮)
可以通过正则去掉 

	this.value = this.value.replace(/\u2006/g, '');
##关于android webview中，input元素输入时出现的怪异情况
见图
![怪异图](http://cdn.bielousov.com/wp-content/uploads/2012/08/android-input-label-text-issue.png)

Android web视图,至少在HTC EVO和三星的Galaxy Nexus中，文本输入框在输入时表现的就像占位符。情况为一个类似水印的东西在用户输入区域，一旦用户开始输入便会消失(见图片)。
在android的默认样式下当输入框获得焦点后,若存在一个绝对定位或者fixed的元素，布局会被破坏,其他元素与系统输入字段会发生重叠(如搜索图标将消失为搜索字段),可以观察到布局与原始输入字段有偏差(见截图)。
这是一个相当复杂的问题，以下简单布局可以重现这个问题:

	<label for="phone">Phone: *</label>
	<input type="tel" name="phone" id="phone" minlength="10" maxlength="10" inputmode="latin digits" required="required" />
	
解决方法

	-webkit-user-modify: read-write-plaintext-only
	
详细参考<http://www.bielousov.com/2012/android-label-text-appears-in-input-field-as-a-placeholder/>
注意，该属性会导致中文不能输入词组，只能单个字。感谢鬼哥与飞（游勇飞）贡献此问题与解决方案

另外，在position:fixed后的元素里，尽量不要使用输入框。更多的bug可参考
<http://www.cosdiv.com/page/M0/S882/882353.html>
=======
依旧无法解决（摩托罗拉ME863手机），则使用input:text类型而非password类型，并设置其设置  -webkit-text-security: disc; 隐藏输入密码从而解决。


##JS动态生成的select下拉菜单在Android2.x版本的默认浏览器里不起作用

解决方法删除了overflow-x:hidden; 然后在JS生成下来菜单之后focus聚焦，这两步操作之后解决了问题。(来自岛都-小Qi)

参考<http://stackoverflow.com/questions/4697908/html-select-control-disabled-in-android-webview-in-emulator>

##andriod上去掉语音输入按钮


	input::-webkit-input-speech-button {display: none}
	
	
	
##移动浏览器篇
	
【UC浏览器】video标签脱离文档流

场景：<video>标签的父元素(祖辈元素)设置transform样式后，<video>标签会脱离文档流。

测试环境：UC浏览器 8.7/8.6 + Android 2.3/4.0 。

Demo：<http://t.cn/zj3xiyu>

解决方案：不使用transform属性。translate用top、margin等属性替代。

 

【UC浏览器】video标签总在最前

场景：<video>标签总是在最前（可以理解为video标签的z-index属性是Max）。

测试环境：UC浏览器 8.7/8.6 + Android 2.3/4.0 。

 

【UC浏览器】position:fixed 属性在UC浏览器的奇葩现象

场景：设置了position: fixed 的元素会遮挡z-index值更高的同辈元素。

　　　在8.6的版本,这个情况直接出现。

　　　在8.7之后的版本,当同辈元素的height大于713这个「神奇」的数值时,才会被遮挡。

测试环境：UC浏览器 8.8_beta/8.7/8.6 + Android 2.3/4.0 。

Demo：<http://t.cn/zYLTSg6>

 

【QQ手机浏览器】不支持HttpOnly

场景：带有HttpOnly属性的Cookie，在QQ手机浏览器版本从4.0开始失效。JavaScript可以直接读取设置了HttpOnly的Cookie值。

测试环境：QQ手机浏览器 4.0/4.1/4.2 + Android 4.0 。

 

【MIUI原生浏览器】浏览器地址栏hash不改变

场景：location.hash 被赋值后，地址栏的地址不会改变。

　　　但实际上 location.href 已经更新了，通过JavaScript可以顺利获取到更新后的地址。

　　　虽然不影响正常访问，但用户无法将访问过程中改变hash后的地址存为书签。

测试环境：MIUI 4.0

 

【Chrome Mobile】fixed元素无法点击

 场景：父元素设置position: fixed;

　　　子元素设置position: absolute;

　　　此时，如果父元素/子元素还设置了overflow: hidden 则出现“父元素遮挡该子元素“的bug。

　　　视觉(view)层并没有出现遮挡，只是无法触发绑定在该子元素上的事件。可理解为：「看到点不到」。

补充： 页面往下滚动，触发position: fixed;的特性时，才会出现这个bug，在最顶不会出现。

测试平台： 小米1S，Android4.0的Chrome18

demo： <http://maplejan.sinaapp.com/demo/fixed_chromemobile.html>

解决办法： 把父元素和子元素的overflow: hidden去掉。

以上来源于  <http://www.cnblogs.com/maplejan/archive/2013/04/26/3045928.html>





##库的使用实践

#zepto.js

 [zepto的一篇使用注意点讲解](http://chaoskeh.com/blog/some-experience-of-using-zepto.html "zepto")
 
 [zepto的著名的tap“点透”bug](http://blog.youyo.name/archives/zepto-tap-click-through-research.html "zepto")

#iscroll4

 iscroll4的几个bug(来自<http://www.mansonchor.com/blog/blog_detail_64.html>内有详细讲解)
 
1.滚动容器点击input框、select等表单元素时没有响应】

	onBeforeScrollStart: function (e) { e.preventDefault(); }

改为

	onBeforeScrollStart: function (e) { var nodeType = e.explicitOriginalTarget © e.explicitOriginalTarget.nodeName.toLowerCase():(e.target © e.target.nodeName.toLowerCase():'');if(nodeType !='select'&& nodeType !='option'&& nodeType !='input'&& nodeType!='textarea') e.preventDefault(); }

2.往iscroll容器内添加内容时，容器闪动的bug


源代码的

	has3d = 'WebKitCSSMatrix' in window && 'm11' in new WebKitCSSMatrix()

改成

	has3d = false
	
在配置iscroll时，useTransition设置成false

3.过长的滚动内容，导致卡顿和app直接闪退

1)不要使用checkDOMChanges。虽然checkDOMChanges很方便，定时检测容器长度是否变化来refresh，但这也意味着你要消耗一个Interval的内存空间
2)隐藏iscroll滚动条，配置时设置hScrollbar和vScrollbar为false。
3)不得已的情况下，去掉各种效果，momentum、useTransform、useTransition都设置为false

4.左右滚动时，不能正确响应正文上下拉动


iscroll的闪动问题也与渲染有关系，可以参考
 [运用webkit绘制渲染页面原理解决iscroll4闪动的问题](http://www.iunbug.com/archives/2012/09/19/411.html "iscroll4")






