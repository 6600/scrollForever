# scrollForever
一个支持连续无缝滚动和非连续滚动的插件
A simple jQuery plugin that quicky builds scrolling element forever

插件概述
scrollForever 是一个支持连续无缝滚动和非连续滚动的插件，支持向上和向左滚动，你可以自由设置滚动间隔和速度等

插件特色
快速部署

只需要引入插件，并在底部添加相应的代码即可

功能齐全

你能想到的，这个插件都能帮你做到，熟悉参数帮助你更快的上手

代码精简

只要2k的代码就能完成无缝滚动，包括连续滚动和非连续滚动

快速部署

只需要引入插件，并在底部添加相应的代码即可

功能齐全

你能想到的，这个插件都能帮你做到，熟悉参数帮助你更快的上手

代码精简

只要2k的代码就能完成无缝滚动，包括连续滚动和非连续滚动

演示例子
默认连续滚动默认连续滚动默认连续滚动
设置不连续滚动
设置不连续滚动
设置不连续滚动
无缝滚动插件版无缝向左1无缝向左2无缝向上间断向左间断向上

使用方法
JsHTMLCSS
<script type="text/javascript" src="js/jquery.js"></script>
<script type="text/javascript" src="scrollForever.js"></script>
<script type="text/javascript">
$(function(){
$("#a1").scrollForever();
})
</script>
参数介绍
参数名	默认值	描述
continuous	true	是否连续
placeholder	0	非连续滚动时每次的滑动距离，可以自定义，如果没有自定义则根据子元素和滚动数量来决定
dir	'left'	滚动方面，可以为left和top
container	'ul'	外层元素
innner	'li'	子元素
speed	1000	非连续滚动速度
delayTime	0	滚动间隔，非连续滚动为2000ms,连续滚动为20ms,可以自定义
num	1	非连续一次滚动的数量
