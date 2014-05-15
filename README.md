#mobileTech

A useful tools or tips list for mobile web application developing

这个项目收集移动端开发所需要的一些资源与小技巧


##工具类网站

 [HTML5 与 CSS3 技术应用评估](http://html5please.com/ "html5与css3技术应用评估")
 
 [各种奇妙的hack](http://browserhacks.com/ "各种奇妙的hack")
 
 [几乎所有设备的屏幕尺寸与像素密度表](http://en.wikipedia.org/wiki/List_of_displays_by_pixel_density "几乎所有设备的屏幕尺寸与像素密度表")
 
 [移动设备参数表](http://screensiz.es/phone "移动设备参数表")
 
 [ios端移动设备参数速查](http://ivomynttinen.com/blog/the-ios-design-cheat-sheet-volume-2/ "ios端移动设备参数速查")
 
 [浏览器兼容表](http://www.quirksmode.org/compatibility.html "浏览器兼容表")
 
 [移动设备查询器](https://deviceatlas.com/device-data/devices "移动设备查询器")
 
 [移动设备适配库](http://51degrees.codeplex.com/ "移动设备适配库")
 
 [移动设备适配库2](http://detectmobilebrowsers.com/ "移动设备适配库2")
 
 [viewport与设备尺寸在线检测器](https://deviceatlas.com/device-data/devices "viewport与设备尺寸在线检测器")
 
 [html5 移动端兼容性速查](http://mobilehtml5.org/ "html5移动端兼容性速查")
 
 [在线转换字体](http://www.fontsquirrel.com/tools/webfont-generator "在线转换字体")
 
 [css3 选择器测试](http://tools.css3.info/selectors-test/test.html "css3选择器测试")
 
 [兼容性速查表](http://caniuse.com/ "兼容性速查表")
 
 [浏览器的一些独特参数](http://www.browserscope.org/ "浏览器的一些独特参数")
 
 [各种各样的媒体查询收集](http://nmsdvid.com/snippets/ "各种各样的媒体查询收集")
 
 [css3 动画在线制作器](http://ecd.tencent.com/css3/tools.html "css3动画在线制作器")
 
 [css3 渐变在线制作器](http://www.colorzilla.com/gradient-editor/ "css3渐变在线制作器")
 

[移动端手势表](http://ww1.sinaimg.cn/bmiddle/c2c57f68jw1e4fh7dmw12j20fi2w6qe1.jpg "移动端手势表")


[webkit独有的样式分析](http://ued.ctrip.com/blog/wp-content/webkitcss/ "webkit独有的样式分析")

[HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)

[HTML5 POLYFILLS](http://html5polyfill.com/ "HTML5 POLYFILLS")


##响应式测试工具

Firefox 浏览器内置了 `自定义设计视图` 的功能，可以通过 `Firefox->Web 开发者->自定义设计视图`（或者摁下 `Shift + Ctrl + m` ）。相比网络工具，运行更加流畅，无需联网。

[判断 iPad 和 iPhone 的版本和状态的 CSS 媒体查询代码](http://yujiangshui.com/document/css-media-queries-for-ipads-and-iphones-chinese-version/)

[Viewport Resizer](http://lab.maltewassermann.com/viewport-resizer/ "resize")

[http://beta.screenqueri.es/](http://beta.screenqueri.es/ "resize")

[http://responsivepx.com](http://responsivepx.com "resize")

[http://www.responsinator.com/](http://www.responsinator.com/ "resize")

[http://resizemybrowser.com/](http://resizemybrowser.com/ "resize")

[https://quirktools.com/screenfly/](https://quirktools.com/screenfly/ "resize")

媒体查询常用样式表：

	<link rel="stylesheet" media="all and (orientation:portrait)" href="portrait.css">    // 竖放加载
	<link rel="stylesheet" media="all and (orientation:landscape)"href="landscape.css">   // 横放加载

	//竖屏时使用的样式
	<style media="all and (orientation:portrait)" type="text/css">
		#landscape { display: none; }
	</style>

	//横屏时使用的样式
	<style media="all and (orientation:landscape)" type="text/css">
		#portrait { display: none; }
	</style>

##Web app 开发的最佳实践与中文总结

[It’s not a web app. It’s an app you install from the web.](http://blog.forecast.io/its-not-a-web-app-its-an-app-you-install-from-the-web/)

[当前 WEB APP 开发的最佳实践](http://lyric.im/best-practice-for-web-app-development/)


##来自[maxzhang](https://github.com/maxzhang "ava")的一些移动端经验总结干货


[移动Web单页应用开发实践——页面结构化](https://github.com/maxzhang/maxzhang.github.com/issues/8 "ava")

[移动Web产品前端开发口诀——“快”](https://github.com/maxzhang/maxzhang.github.com/issues/1 "ava")

[移动Web开发，4行代码检测浏览器是否支持position:fixed](https://github.com/maxzhang/maxzhang.github.com/issues/7 "ava")

[使用border-image实现类似iOS7的1px底边](https://github.com/maxzhang/maxzhang.github.com/issues/4 "ava")

[移动端web页面使用position:fixed问题总结](https://github.com/maxzhang/maxzhang.github.com/issues/2 "ava")

[移动Web开发实践——解决position:fixed自适应BUG](https://github.com/maxzhang/maxzhang.github.com/issues/11 "ava")

[移动手机浏览器m3u8格式视频流播放支持程度测试](https://github.com/maxzhang/maxzhang.github.com/issues/19 "ava")


##本资料很多引用了指尖上的js系列

 [指尖下的js ——多触式web前端开发之一：对于Touch的处理](http://www.cnblogs.com/pifoo/archive/2011/05/23/webkit-touch-event-1.html "article1")
 
 [指尖下的js ——多触式web前端开发之二：处理简单手势](http://www.cnblogs.com/pifoo/archive/2011/05/22/webkit-touch-event-2.html "article2")
 
 [指尖下的js —— 多触式web前端开发之三：处理复杂手势](http://www.cnblogs.com/pifoo/archive/2011/05/22/webkit-touch-event-3.html "article3")


meta标签，这些meta标签在开发webapp时起到非常重要的作用

	<meta content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0" name="viewport" />
	<meta content="yes" name="apple-mobile-web-app-capable" />
	<meta content="black" name="apple-mobile-web-app-status-bar-style" />
	<meta content="telephone=no" name="format-detection" />


第一个meta标签表示：强制让文档的宽度与设备的宽度保持1:1，并且文档最大的宽度比例是1.0，且不允许用户点击屏幕放大浏览；
尤其要注意的是content里多个属性的设置一定要用分号+空格来隔开，如果不规范将不会起作用。

注意根据 [public_00](http://www.weibo.com/avajayam "ava") 提供的资料补充，content 使用分号作为分隔，在老的浏览器是支持的，但不是规范写法。

规范的写法应该是使用逗号分隔，参考 [Safari HTML Reference - Supported Meta Tags](http://developer.apple.com/library/safari/#documentation/appleapplications/reference/SafariHTMLRef/Articles/MetaTags.html) 和 [Android - Supporting Different Screens in Web Apps](http://developer.android.com/guide/webapps/targeting.html)


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

更详细的 viewport 相关的知识也可以参考

[此像素非彼像素](http://www.w3cplus.com/css/A-pixel-is-not-a-pixel-is-not-a-pixel.html "pixel")

##移动 Web 开发经验技巧
###点击与click事件

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
	
用iphone或ipad浏览很长的网页滚动时的滑动效果很不错吧？不过如果是一个div，然后设置 `height:200px;overflow:auto;`的话，可以滚动但是完全没有那滑动效果，很郁闷吧？

我看到很多网站为了实现这一效果，用了第三方类库，最常用的是iscroll（包括新浪手机页，百度等）
我一开始也使用，不过自从用了`-webkit-overflow-scrolling: touch;`样式后，就完全可以抛弃第三方类库了，把它加在body{}区域，所有的overflow需要滚动的都可以生效了。

###页面描述


	<link rel="apple-touch-icon-precomposed" href="http://www.xxx.com/App_icon_114.png" />
	<link rel="apple-touch-icon-precomposed" sizes="72x72" href="http://www.xxx.com/App_icon_72.png" />
	<link rel="apple-touch-icon-precomposed" sizes="114x114" href="http://www.xxx.com/App_icon_114.png" />
	

这个属性是当用户把连接保存到手机桌面时使用的图标，如果不设置，则会用网页的截图。有了这，就可以让你的网页像APP一样存在手机里了

	<link rel="apple-touch-startup-image" href="/img/startup.png" />
	
这个是APP启动画面图片，用途和上面的类似，如果不设置，启动画面就是白屏，图片像素就是手机全屏的像素

	<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
	
这个描述是表示打开的web app的最上面的时间、信号栏是黑色的，当然也可以设置其它参数，详细参数说明请参照：[Safari HTML Reference - Supported Meta Tags](https://developer.apple.com/library/safari/documentation/appleapplications/reference/SafariHTMLRef/Articles/MetaTags.html)

	<meta name="apple-touch-fullscreen" content="yes" />
	<meta name="apple-mobile-web-app-capable" content="yes" />
 

这两个描述也很有用的，如果没有它，你的web app会用safari浏览器打开，有了它，就会用独立进程的无地址栏的打开，完全可以和普通的APP比拟了

下面还有个不错的css，是用来区分视网膜屏幕的，这样你可以在iphone这样的手机里载入2x的图片，就不会模糊了

	@media only screen and (-webkit-min-device-pixel-ratio:1.5),
	only screen and (min--moz-device-pixel-ratio:1.5),
	only screen and (min-device-pixel-ratio:1.5),
	only screen and (min-resolution:200dpi)
	{
		#logo{background-image: url(logo@2x.png);}
	}

###锁定 viewport

	ontouchmove="event.preventDefault()" //锁定viewport，任何屏幕操作不移动用户界面（弹出键盘除外）。


###利用 Media Query监听

Media Query 相信大部分人已经使用过了。其实 JavaScript可以配合 Media Query这么用：

	var mql = window.matchMedia("(orientation: portrait)");
	mql.addListener(handleOrientationChange);
	handleOrientationChange(mql); 
	function handleOrientationChange(mql) {
	  if (mql.matches) {
	    alert('The device is currently in portrait orientation ')
	  } else {
	    alert('The device is currently in landscape orientation')
	  }}

借助了 Media Query 接口做的事件监听，所以很强大！

也可以通过获取 CSS 值来使用 Media Query 判断设备情况，详情请看：[JavaScript 依据 CSS Media Queries 判断设备的方法](http://yujiangshui.com/use-javascript-css-media-queries-detect-device-state/)。


###rem最佳实践

rem是非常好用的一个属性，可以根据html来设定基准值，而且兼容性也很不错。不过有的时候还是需要对一些莫名其妙的浏览器优雅降级。以下是两个实践

1. <http://jsbin.com/vaqexuge/4/edit>  这有个demo，发现chrome当font-size小于12时，rem会按照12来计算。因此设置基准值要考虑这一点
2. 可以用以下的代码片段保证在低端浏览器下也不会出问题

	
	html { font-size: 62.5%; } 
	body { font-size: 14px; font-size: 1.4rem; } /* =14px */
	h1   { font-size: 24px; font-size: 2.4rem; } /* =24px */
 

###被点击元素的外观变化，可以使用样式来设定：

	-webkit-tap-highlight-color: 颜色
 

###检测判断 iPhone/iPod
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
###阻止旋转屏幕时自动调整字体大小

	html, body, form, fieldset, p, div, h1, h2, h3, h4, h5, h6 {-webkit-text-size-adjust:none;}
 

###模拟:hover伪类
因为iPhone并没有鼠标指针，所以没有hover事件。那么CSS :hover伪类就没用了。但是iPhone有Touch事件，onTouchStart 类似 onMouseOver，onTouchEnd 类似 onMouseOut。所以我们可以用它来模拟hover。使用Javascript：

	var myLinks = document.getElementsByTagName('a');
	for(var i = 0; i < myLinks.length; i++){
	　　myLinks[i].addEventListener(’touchstart’, function(){this.className = “hover”;}, false);
	　　myLinks[i].addEventListener(’touchend’, function(){this.className = “”;}, false);
	}
然后用CSS增加hover效果：

	a:hover, a.hover { /* 你的hover效果 */ }

这样设计一个链接，感觉可以更像按钮。并且，这个模拟可以用在任何元素上。

###Flexbox 布局

 [Flex 模板和实例](http://jsbin.com/ibuwol/2/edit "article5")
 
 [深入了解 Flexbox 伸缩盒模型](http://www.w3cplus.com/blog/666.html "article6")
 
 [CSS Flexbox Intro](http://yehao.diandian.com/post/2013-09-15/40052216426)

<http://www.w3.org/TR/css3-flexbox/>
 
###处理 Retina 双倍屏幕
 
 

 [（经典）Using CSS Sprites to optimize your website for Retina Displays](http://miekd.com/articles/using-css-sprites-to-optimize-your-website-for-retina-displays/ "article5")

 [使用CSS3的background-size优化苹果的Retina屏幕的图像显示](http://www.w3cplus.com/css/css-background-size-graphics.html "article5") 

 [使用 CSS sprites 来优化你的网站在 Retina 屏幕下显示](http://www.w3cplus.com/css/using-css-sprites-to-optimize-your-website-for-retina-displays.html "article5") 
  
 [（案例）CSS IMAGE SPRITES FOR RETINA (HIRES) DEVICES](http://alexthorpe.com/uncategorized/css-sprites-for-retina-display-devices/683/ "article5") 
 

###Android上当viewport的width大于device-width时出现文字无故折行的解决办法

<http://www.iunbug.com/archives/2013/04/23/798.html>

###如何实现打开已安装的app，若未安装则引导用户安装?

来自 <http://gallery.kissyui.com/redirectToNative/1.2/guide/index.html> kissy mobile
通过iframe src发送请求打开app自定义url scheme，如taobao://home（淘宝首页） 、etao://scan（一淘扫描）);
如果安装了客户端则会直接唤起，直接唤起后，之前浏览器窗口（或者扫码工具的webview）推入后台；
如果在指定的时间内客户端没有被唤起，则js重定向到app下载地址。
大概实现代码如下	

	goToNative:function(){
	
		if(!body) {
                setTimeout(function(){
                    doc.body.appendChild(iframe);
                }, 0);
            } else {
                body.appendChild(iframe);
            }
	
	setTimeout(function() {
                doc.body.removeChild(iframe);
                gotoDownload(startTime);//去下载，下载链接一般是itunes app store或者apk文件链接
                /**
                 * 测试时间设置小于800ms时，在android下的UC浏览器会打开native app时并下载apk，
                 * 测试android+UC下打开native的时间最好大于800ms;
                 */
            }, 800);
	}

			
需要注意的是 如果是android chrome 25版本以后，在iframe src不会发送请求，
原因如下<https://developers.google.com/chrome/mobile/docs/intents> ，通过location href使用intent机制拉起客户端可行并且当前页面不跳转。

	window.location = 'intent://' + schemeUrl + '#Intent;scheme=' + scheme + ';package=' + self.package + ';end';

	
###active的兼容(来自薛端阳)

今天发现，要让a链接的CSS active伪类生效，只需要给这个a链接的touch系列的任意事件touchstart/touchend绑定一个空的匿名方法即可hack成功

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

###消除transition闪屏


两个方法：使用css3动画的时尽量利用3D加速，从而使得动画变得流畅。动画过程中的动画闪白可以通过 backface-visibility 隐藏。

	-webkit-transform-style: preserve-3d;
	/*设置内嵌的元素在 3D 空间如何呈现：保留 3D*/
	-webkit-backface-visibility: hidden;
	/*（设置进行转换的元素的背面在面对用户时是否可见：隐藏）*/

 
###测试是否支持svg图片

	document.implementation.hasFeature("http:// www.w3.org/TR/SVG11/feature#Image", "1.1")

###安卓手机点击锁定页面效果问题

有些安卓手机，页面点击时会停止页面的javascript，css3动画等的执行，这个比较蛋疼。不过可以用阻止默认事件解决。详细见
<http://stackoverflow.com/questions/10246305/android-browser-touch-events-stop-display-being-updated-inc-canvas-elements-h>

	function touchHandlerDummy(e)
	{
	    e.preventDefault();
	    return false;
	}
	document.addEventListener("touchstart", touchHandlerDummy, false);
	document.addEventListener("touchmove", touchHandlerDummy, false);
	document.addEventListener("touchend", touchHandlerDummy, false);

	
###消除ie10里面的那个叉号
[IE Pseudo-elements](http://msdn.microsoft.com/en-us/library/windows/apps/hh767361.aspx "article4")

	input:-ms-clear{display:none;}
	
###关于ios与os端字体的优化(横竖屏会出现字体加粗不一致等)
[mac下网页中文字体优化](http://blog.sina.com.cn/s/blog_6da647a601011u4v.html "article5")

[UIWebView font is thinner in portrait than landscape](http://stackoverflow.com/questions/3220662/uiwebview-font-is-thinner-in-portrait-than-landscape "article5")
 

###隐藏地址栏 & 处理事件的时候，防止滚动条出现：

	// 隐藏地址栏  & 处理事件的时候 ，防止滚动条出现
	addEventListener('load', function(){
			setTimeout(function(){ window.scrollTo(0, 1); }, 100);
	});

###判断是否为iPhone：

	// 判断是否为 iPhone ：
	function isAppleMobile() {
		return (navigator.platform.indexOf('iPad') != -1);
	};
###localStorage:

	var v = localStorage.getItem('n') ? localStorage.getItem('n') : "";   // 如果名称是  n 的数据存在 ，则将其读出 ，赋予变量  v  。
	localStorage.setItem('n', v);                                           // 写入名称为 n、值为  v  的数据
	localStorage.removeItem('n');                                           // 删除名称为  n  的数据
###使用特殊链接：
如果你关闭自动识别后 ，又希望某些电话号码能够链接到 iPhone 的拨号功能 ，那么可以通过这样来声明电话链接 ,

	<a href="tel:12345654321">打电话给我</a>
	<a href="sms:12345654321">发短信</a>
或用于单元格：

	<td onclick="location.href='tel:122'">

###自动大写与自动修正
要关闭这两项功能，可以通过autocapitalize 与autocorrect 这两个选项：

	<input type="text" autocapitalize="off" autocorrect="off" />
 

###不让 Android 识别邮箱

	<meta content="email=no" name="format-detection" />
	
###禁止 iOS 弹出各种操作窗口

	-webkit-touch-callout:none
###禁止用户选中文字

	-webkit-user-select:none
	
###动画效果中，使用 translate 比使用定位性能高

[Why Moving Elements With Translate() Is Better Than Pos:abs Top/left](http://paulirish.com/2012/why-moving-elements-with-translate-is-better-than-posabs-topleft/)

###拿到滚动条

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

###关于 iOS 系统中，Web APP 启动图片在不同设备上的适应性设置

<http://stackoverflow.com/questions/4687698/mulitple-apple-touch-startup-image-resolutions-for-ios-web-app-esp-for-ipad/10011893#10011893>

###关于 iOS 系统中，中文输入法输入英文时，字母之间可能会出现一个六分之一空格
可以通过正则去掉 

	this.value = this.value.replace(/\u2006/g, '');

###关于android webview中，input元素输入时出现的怪异情况
见下图

![怪异图](http://cdn.bielousov.com/wp-content/uploads/2012/08/android-input-label-text-issue.png)

Android Web 视图,至少在 HTC EVO 和三星的 Galaxy Nexus 中，文本输入框在输入时表现的就像占位符。情况为一个类似水印的东西在用户输入区域，一旦用户开始输入便会消失(见图片)。

在 Android 的默认样式下当输入框获得焦点后，若存在一个绝对定位或者 fixed 的元素，布局会被破坏，其他元素与系统输入字段会发生重叠(如搜索图标将消失为搜索字段)，可以观察到布局与原始输入字段有偏差(见截图)。

这是一个相当复杂的问题，以下简单布局可以重现这个问题:

	<label for="phone">Phone: *</label>
	<input type="tel" name="phone" id="phone" minlength="10" maxlength="10" inputmode="latin digits" required="required" />
	
解决方法

	-webkit-user-modify: read-write-plaintext-only
	
详细参考<http://www.bielousov.com/2012/android-label-text-appears-in-input-field-as-a-placeholder/>
注意，该属性会导致中文不能输入词组，只能单个字。感谢鬼哥与飞（游勇飞）贡献此问题与解决方案

另外，在position:fixed后的元素里，尽量不要使用输入框。更多的bug可参考
<http://www.cosdiv.com/page/M0/S882/882353.html>

依旧无法解决（摩托罗拉ME863手机），则使用input:text类型而非password类型，并设置其设置  -webkit-text-security: disc; 隐藏输入密码从而解决。


###JS动态生成的select下拉菜单在Android2.x版本的默认浏览器里不起作用

解决方法删除了overflow-x:hidden; 然后在JS生成下来菜单之后focus聚焦，这两步操作之后解决了问题。(来自岛都-小Qi)

参考<http://stackoverflow.com/questions/4697908/html-select-control-disabled-in-android-webview-in-emulator>

###Andriod 上去掉语音输入按钮


	input::-webkit-input-speech-button {display: none}
	
##移动开发事件

[手机浏览器常用手势动作监听封装](http://wo.poco.cn/manson/post/id/268780)

###手势事件
* touchstart            //当手指接触屏幕时触发
* touchmove           //当已经接触屏幕的手指开始移动后触发
* touchend             //当手指离开屏幕时触发
* touchcancel

###触摸事件
* gesturestart          //当两个手指接触屏幕时触发
* gesturechange      //当两个手指接触屏幕后开始移动时触发
* gestureend

###屏幕旋转事件
* onorientationchange    

###检测触摸屏幕的手指何时改变方向
* orientationchange      

###touch事件支持的相关属性
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

###判断屏幕是否旋转

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
		};};

###添加事件监听
	addEventListener('load', function(){
		orientationChange();
		window.onorientationchange = orientationChange;
	});
 

###双手指滑动事件：

	// 双手指滑动事件
	addEventListener('load',　　function(){ window.onmousewheel = twoFingerScroll;},
		false              // 兼容各浏览器，表示在冒泡阶段调用事件处理程序 (true 捕获阶段)
	);
	function twoFingerScroll(ev) {
		var delta =ev.wheelDelta/120;              //对 delta 值进行判断(比如正负) ，而后执行相应操作
		return true;
	};


###JS 单击延迟
click 事件因为要等待单击确认，会有 300ms 的延迟，体验并不是很好。

开发者大多数会使用封装的 tap 事件来代替click 事件，所谓的 tap 事件由 touchstart 事件 + touchmove 判断 + touchend 事件封装组成。

 [Creating Fast Buttons for Mobile Web Applications](https://developers.google.com/mobile/articles/fast_buttons?hl=de-DE "article5")

 [Eliminate 300ms delay on click events in mobile Safari](http://stackoverflow.com/questions/12238587/eliminate-300ms-delay-on-click-events-in-mobile-safari "article5")

##WebKit CSS:
[携程 UED 整理的 Webkit CSS 文档](http://ued.ctrip.com/blog/wp-content/webkitcss/index.html) ，全面、方便查询，下面为常用属性。

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
 
	
##常见的 iPhone 和 Android 屏幕参数。

* 设备	     分辨率	    设备像素比率
* Android LDPI	320×240	0.75
* Iphone 3 & Android MDPI	320×480	1
* Android HDPI	480×800	1.5
* Iphone 4	960×640	2.0

iPhone 4的一个 CSS 像素实际上表现为一块 2×2 的像素。所以图片像是被放大2倍一样，模糊不清晰。

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
	
##IE10 的特殊鼠标事件

[IE10 事件监听](http://www.mansonchor.com/blog/blog_detail_73.html "article5")

##iOS 输入框最佳实践

[Mobile-friendly input of a digits + spaces string (a credit card number)](http://stackoverflow.com/questions/11219242/mobile-friendly-input-of-a-digits-spaces-string-a-credit-card-number)

[HTML5 input type number vs tel](http://stackoverflow.com/questions/8216278/html5-input-type-number-vs-tel)

[iPhone: numeric keyboard for text input](http://stackoverflow.com/questions/6178556/iphone-numeric-keyboard-for-text-input)

[Text Programming Guide for iOS - Managing the Keyboard](https://developer.apple.com/library/ios/documentation/StringsTextFonts/Conceptual/TextAndWebiPhoneOS/KeyboardManagement/KeyboardManagement.html)
	
[HTML5 inputs and attribute support](http://www.miketaylr.com/code/input-type-attr.html)


##往返缓存问题

点击浏览器的回退，有时候不会自动执行js，特别是在mobilesafari中。这与**往返缓存(bfcache)**有关系。有很多hack的处理方法，可以参考

<http://stackoverflow.com/questions/24046/the-safari-back-button-problem>

<http://stackoverflow.com/questions/11979156/mobile-safari-back-button>

##iOS 6 跟 iPhone 5 的那些事


###IP5 的媒体查询

	@media (device-height: 568px) and (-webkit-min-device-pixel-ratio: 2) {
	
	/* iPhone 5 or iPod Touch 5th generation */
	
	}
###使用媒体查询，提供不同的启动图片：

	<link href="startup-568h.png" rel="apple-touch-startup-image" media="(device-height: 568px)">
	<link href="startup.png" rel="apple-touch-startup-image" sizes="640x920" media="(device-height: 480px)">
###拍照上传

	<input type=file accept="video/*">
	<input type=file accept="image/*">

不支持其他类型的文件 ，如音频，Pages文档或PDF文件。 也没有getUserMedia摄像头的实时流媒体支持。


###可以使用的 HTML5 高级 api

* multipart POST 表单提交上传
* XMLHttpRequest 2 AJAX 上传（甚至进度支持）
* 文件 API ，在 iOS 6 允许 JavaScript 直接读取的字节数和客户端操作文件。

###智能应用程序横幅

有了智能应用程序横幅，当网站上有一个相关联的本机应用程序时，Safari浏览器可以显示一个横幅。 如果用户没有安装这个应用程序将显示“安装”按钮，或已经安装的显示“查看”按钮可打开它。

在 iTunes Link Maker 搜索我们的应用程序和应用程序ID。

	<meta name="apple-itunes-app" content="app-id=9999999">

可以使用 app-argument 提供字符串值，如果参加iTunes联盟计划，可以添加元标记数据 

	<meta name="apple-itunes-app" content="app-id=9999999, app-argument=xxxxxx">

	<meta name="apple-itunes-app" content="app-id=9999999, app-argument=xxxxxx, affiliate-data=partnerId=99&siteID=XXXX">

横幅需要156像素（设备是312 hi-dpi）在顶部，直到用户在下方点击内容或关闭按钮，你的网站才会展现全部的高度。 它就像HTML的DOM对象，但它不是一个真正的DOM。 

CSS3 滤镜

	-webkit-filter: blur(5px) grayscale (.5) opacity(0.66) hue-rotate(100deg);

交叉淡变

	background-image: -webkit-cross-fade(url("logo1.png"), url("logo2.png"), 50%);

Safari中的全屏幕

除了chrome-less 主屏幕meta标签，现在的iPhone和iPod Touch（而不是在iPad）支持全屏幕模式的窗口。 没有办法强制全屏模式，它需要由用户启动（工具栏上的最后一个图标）。需要引导用户按下屏幕上的全屏图标来激活全屏效果。 可以使用onresize事件检测是否用户切换到全屏幕。

支持requestAnimationFrameAPI

支持image-set,retina屏幕的利器

	-webkit-image-set(url(low.png) 1x, url(hi.jpg) 2x)

应用程序缓存限制增加至25MB。


Web View（pseudobrowsers，PhoneGap/Cordova应用程序，嵌入式浏览器） 上Javascript运行比Safari慢3.3倍（或者说，Nitro引擎在Safari浏览器是Web应用程序是3.3倍速度）。

autocomplete属性的输入遵循DOM规范

来自DOM4的Mutation Observers已经实现。 您可以使用WebKitMutationObserver构造器捕获DOM的变化

Safari不再总是对用 -webkit-transform:preserve-3d 的元素创建硬件加速

支持window.selection 的Selection API

Canvas更新 ：createImageData有一个参数，现在有两个新的功能做好准备，用webkitGetImageDataHD和webkitPutImageDataHD提供高分辨率图像 。

更新SVG处理器和事件构造函数


##IOS7的大更新

[iOS 7 的 Safari 和 HTML5：问题，变化和新 API](http://jinlong.github.io/blog/2013/09/23/safari-ios7-html5-problems-apis-review/#jtss-tsina)(张金龙翻译)

[iOS 7 的一些坑(英文)](http://www.sencha.com/blog/the-html5-scorecard-the-good-the-bad-and-the-ugly-in-ios7 "ios7的一些bug")

[ios7的一些坑2(英文)](http://www.mobilexweb.com/blog/safari-ios7-html5-problems-apis-review "ios7的一些bug")



##webview相关

#Cache开启和设置

	browser.getSettings().setAppCacheEnabled(true);
	browser.getSettings().setAppCachePath("/data/data/[com.packagename]/cache");
	browser.getSettings().setAppCacheMaxSize(5*1024*1024); // 5MB

#LocalStorage相关设置

	browser.getSettings().setDatabaseEnabled(true);
	browser.getSettings().setDomStorageEnabled(true);
	String databasePath = browser.getContext().getDir("databases", Context.MODE_PRIVATE).getPath();
	browser.getSettings().setDatabasePath(databasePath);//Android　webview的LocalStorage有个问题，关闭APP或者重启后，就清楚了，所以需要browser.getSettings().setDatabase相关的操作，把LocalStoarge存到DB中
 
	myWebView.setWebChromeClient(new WebChromeClient(){
	　　　 @Override
	　　　 public void onExceededDatabaseQuota(String url, String databaseIdentifier, long currentQuota, long estimatedSize, long totalUsedQuota, WebStorage.QuotaUpdater quotaUpdater)
	　　　 {
	　　　　　　　 quotaUpdater.updateQuota(estimatedSize * 2);
	　　　 }
	}

#浏览器自带缩放按钮取消显示

	browser.getSettings().setBuiltInZoomControls(false);

#几个比较好的实践

使用localstorage缓存html

使用lazyload，还要记得lazyload占位图虽然小，但是最好能提前加载到缓存

延时加载执行js

主要原因就在于Android Webview的onPageFinished事件，Android端一般是用这个事件来标识页面加载完成并显示的，也就是说在此之前，会一直loading，但是Android的OnPageFinished事件会在Javascript脚本执行完成之后才会触发。如果在页面中使用JQuery，会在处理完DOM对象，执行完$(document).ready(function() {});事件自会后才会渲染并显示页面。


##移动端调适篇

###手机抓包与配host

在PC上，我们可以很方便地配host，但是手机上如何配host，这是一个问题。

这里主要使用fiddler和远程代理，实现手机配host的操作，具体操作如下：

首先，保证PC和移动设备在同一个局域网下；

PC上开启fiddler，并在设置中勾选“allow remote computers to connect”

1. 首先，保证PC和移动设备在同一个局域网下；

2. PC上开启fiddler，并在设置中勾选“allow remote computers to connect”
![fiddler](https://github.com/hoosin/mobile-web-favorites/raw/master/img/01.png)

3. 手机上设置代理，代理IP为PC的IP地址，端口为8888（这是fiddler的默认端口）。通常手机上可以直接设置代理，如果没有，可以去下载一个叫ProxyDroid的APP来实现代理的设置。

4. 此时你会发现，用手机上网，走的其实是PC上的fiddler，所有的请求包都会在fiddler中列出来，配合willow使用，即可实现配host，甚至是反向代理的操作。

也可以用CCProxy之类软件，还有一种方法就是买一个随身wifi，然后手机连接就可以了！

###高级抓包

[iPhone上使用Burp Suite捕捉HTTPS通信包方法](http://danqingdani.blog.163.com/blog/static/1860941952012112353515306/?suggestedreading&wumii "iPhone上使用Burp Suite捕捉HTTPS通信包方法")

[mobile app 通信分析方法小议（iOS/Android)](http://danqingdani.blog.163.com/blog/static/1860941952012101331848980/ "mobile app 通信分析方法小议（iOS/Android)")

[实时抓取移动设备上的通信包(ADVsock2pipe+Wireshark+nc+tcpdump)](http://danqingdani.blog.163.com/blog/static/1860941952012111954741585/ "实时抓取移动设备上的通信包(ADVsock2pipe+Wireshark+nc+tcpdump)")


###静态资源缓存问题

一般用代理软件代理过来的静态资源可以设置nocache避免缓存，但是有的手机比较诡异，会一直缓存住css等资源文件。由于静态资源一般都是用版本号管理的，我们以charles为例子来处理这个问题

charles 选择静态的html页面文件-saveResponse。之后把这个文件保存一下，修改一下版本号。之后继续发请求，
刚才的html页面文件 右键选择 --map local 选择我们修改过版本号的html文件即ok。这其实也是fiddler远程映射并修改文件的一个应用场景。

##移动浏览器篇


###微信浏览器

因为微信浏览器屏蔽了一部分链接图片，所以需要引导用户去打开新页面，可以用以下方式判断微信浏览器的ua

	function is_weixn(){
	    var ua = navigator.userAgent.toLowerCase();
	    if(ua.match(/MicroMessenger/i)=="micromessenger") {
	        return true;
	    } else {
	        return false;
	    }
	}
	
后端判断也很简单，比如php

	function is_weixin(){
	    if ( strpos($_SERVER['HTTP_USER_AGENT'], 'MicroMessenger') !== false ) {
	            return true;
	    }  
	    return false;
	}



	
###【UC浏览器】video标签脱离文档流

场景：<video>标签的父元素(祖辈元素)设置transform样式后，<video>标签会脱离文档流。

测试环境：UC浏览器 8.7/8.6 + Android 2.3/4.0 。

Demo：<http://t.cn/zj3xiyu>

解决方案：不使用transform属性。translate用top、margin等属性替代。

 

###【UC浏览器】video标签总在最前

场景：<video>标签总是在最前（可以理解为video标签的z-index属性是Max）。

测试环境：UC浏览器 8.7/8.6 + Android 2.3/4.0 。

 

###【UC浏览器】position:fixed 属性在UC浏览器的奇葩现象

场景：设置了position: fixed 的元素会遮挡z-index值更高的同辈元素。

　　　在8.6的版本,这个情况直接出现。

　　　在8.7之后的版本,当同辈元素的height大于713这个「神奇」的数值时,才会被遮挡。

测试环境：UC浏览器 8.8_beta/8.7/8.6 + Android 2.3/4.0 。

Demo：<http://t.cn/zYLTSg6>

 

###【QQ手机浏览器】不支持HttpOnly

场景：带有HttpOnly属性的Cookie，在QQ手机浏览器版本从4.0开始失效。JavaScript可以直接读取设置了HttpOnly的Cookie值。

测试环境：QQ手机浏览器 4.0/4.1/4.2 + Android 4.0 。

 

###【MIUI原生浏览器】浏览器地址栏hash不改变

场景：location.hash 被赋值后，地址栏的地址不会改变。

　　　但实际上 location.href 已经更新了，通过JavaScript可以顺利获取到更新后的地址。

　　　虽然不影响正常访问，但用户无法将访问过程中改变hash后的地址存为书签。

测试环境：MIUI 4.0

 

###【Chrome Mobile】fixed元素无法点击

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

###zepto.js

 [zepto的一篇使用注意点讲解](http://chaoskeh.com/blog/some-experience-of-using-zepto.html "zepto")
 
 [zepto的著名的tap“点透”bug](http://blog.youyo.name/archives/zepto-tap-click-through-research.html "zepto")
 
 [zepto源码注释](http://www.cnblogs.com/sky000/archive/2013/03/29/2988952.html "zepto")
 
###使用zeptojs内嵌到android webview影响正常滚动时
<https://github.com/madrobby/zepto/blob/master/src/touch.js> 去掉61行,其实就是使用原生的滚动

###iscroll4

 iscroll4 的几个bug(来自 <http://www.mansonchor.com/blog/blog_detail_64.html> 内有详细讲解)
 
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

1. 不要使用checkDOMChanges。虽然checkDOMChanges很方便，定时检测容器长度是否变化来refresh，但这也意味着你要消耗一个Interval的内存空间
2. 隐藏iscroll滚动条，配置时设置hScrollbar和vScrollbar为false。
3. 不得已的情况下，去掉各种效果，momentum、useTransform、useTransition都设置为false

4.左右滚动时，不能正确响应正文上下拉动


iscroll的闪动问题也与渲染有关系，可以参考
 [运用webkit绘制渲染页面原理解决iscroll4闪动的问题](http://www.iunbug.com/archives/2012/09/19/411.html "iscroll4")
[iscroll4升级到5要注意的问题](http://blog.csdn.net/gcz564539969/article/details/9156141 "iscroll5")


###iscroll或者滚动类框架滚动时不点击的方法

可以使用以下的解决方案(利用data-setapi)

	<a ontouchmove="this.s=1" ontouchend="this.s || window.open(this.dataset.href),this.s=0" target="_blank" data-href="http://www.hao123.com/topic/pig">黄浦江死猪之谜</a>

也可以用这种方法


		$(document).delegate('[data-target]', 'touchmove', function () {
			$(this).attr('moving','moving');

		})
		

		$(document).delegate('[data-target]', 'touchend', function () {
			if ($(this).attr('moving') !== 'moving') {
			 //做你想做的。。
				$(this).attr('moving', 'notMoving');
			} else {
				$(this).attr('moving', 'notMoving');
			}

		})



##移动端字体问题

[知乎专栏 - [无线手册-4] dp、sp、px傻傻分不清楚[完整]](http://zhuanlan.zhihu.com/zhezhexiong/19565895)

[Resolution Independent Mobile UI](http://www.sencha.com/blog/resolution-independent-mobile-ui)

[Pixel density, retina display and font-size in CSS](http://stackoverflow.com/questions/12058574/pixel-density-retina-display-and-font-size-in-css)

[Device pixel density tests](http://bjango.com/articles/min-device-pixel-ratio/)


##跨域问题 

手机浏览器也是浏览器，在ajax调用外部api的时候也存在跨域问题。当然利用 PhoneGap 打包后，由于协议不一样就不存在跨域问题了。
但页面通常是需要跟后端进行调试的。一般会报类似

	XMLHttpRequest cannot load XXX
	Origin null is not allowed by Access-Control-Allow-Origin.

以及

	XMLHttpRequest cannot load http://. Request header field Content-Type is not allowed by Access-Control-Allow-Headers."

这时候可以让后端加上两个http头

	Access-Control-Allow-Origin "*"
	Access-Control-Allow-Headers "Origin, X-Requested-With, Content-Type, Accept"

第一个头可以避免跨域问题，第二个头可以方便ajax请求设置content-type等配置项

这个会存在一些安全问题，可以参考这个问题的讨论 <http://www.zhihu.com/question/22992229>

##PhoneGap 部分

###Should not happen: no rect-based-test nodes found 
在 Android 项目中的 assets 中的 HTML 页面中加入以下代码，便可解决问题

	window,html,body{
	    overflow-x:hidden !important;
	    -webkit-overflow-scrolling: touch !important;
	    overflow: scroll !important;
	}
	
参考：

<http://stackoverflow.com/questions/12090899/android-webview-jellybean-should-not-happen-no-rect-based-test-nodes-found>

###拿联系人的时候报 ContactFindOptions is not defined

出现这个问题可能是因为 Navigator 取 contacts 时绑定的 window.onload

注意使用 PhoneGap 的 API 时，一定要在 devicereay 事件的处理函数中使用 API

	document.addEventListener("deviceready", onDeviceReady, false);
	
	    function onDeviceReady() {    
	        callFetchContacts();
	    }
	
	function callFetchContacts(){
	    var options = new ContactFindOptions();
	    options.multiple = true;
	    var fields       = ["displayName", "name","phoneNumbers"];
	    navigator.contacts.find(fields, onSuccess, onError,options);  
	    }
