#Responsive CSS Timeline

## Live Demo
### [Responsive CSS Timeline](http://bglky.me/timeline "Responsive CSS Timeline")
![](http://7xwdhu.com1.z0.glb.clouddn.com/TimeLine_page.PNG)

## Introduction
查阅了网上的Timeline插件，大部分都比较臃肿，而且还要带上JQuery。幸运发现了 [Vertical Timeline](http://tympanus.net/Blueprints/VerticalTimeline/ "Vertical Timeline") ，它的界面让我眼前一亮。仔细的体验后发现，需内嵌了字体和图标，以及IE8、IE7下界面有点乱（其实是用了一些HTML5和高级CSS，要不是为了兼容性，我也喜欢这种）。本着简洁、美观、兼容性强的目标，参考它的界面设计，自己写了一个，不内嵌字体和图标，在IE8、IE7下能优雅降级。

## Quick Start

引入bglky_timeline.css文件
```html
<link rel="stylesheet" href="css/bglky_timeline.css" />
```

timeline代码结构
```html
<ul class="zbg-timeline">
	<li>
		<div class="zbg-tl-order">1</div>
		<div class="zbg-tl-time"><span>2016/07/13</span><span>20:43</span></div>
		<div class="zbg-tl-content">
			<h2>标题</h2>
			<p>内容......</p>
		</div>
	</li>
</ul>
```
