---
title: "Руководство по Roll20 от Паланта"
permalink: /roll20-guide/bookmarklets/
excerpt: "Как удобно использовать Roll20 при игре в D&D 5e онлайн"
output: true
toc: true
---

## Что такое букмарклет

~~~
javascript:alert("Hi, I'm a Bookmarklet!");
~~~
~~~
javascript:(function(){$("#floatingtoolbar").css("display",function(i,o){return ('block' === o ? 'none' : 'block');});})();
~~~
~~~
javascript:(function(){$("#zoomslider").css("display","none");$("#floatingtoolbar").css("display","none");$("#sidebarcontrol").click();$("#playerzone").css("display","none");})();
~~~

~~~
javascript:(function(){ var links=$('#libraryview .library-container').map(function(idx,block){ var $block=$(block), img=$block.find('img'),name=$block.find('.library-labelcontainer span').text(), ext = img.attr('src').match(/\b(?:thumb|max|original)\b\.(\w*)/)[1]; return $('<a style="border:1px solid #999;float:left;display:block;width:52px;height:52px;" href="'+img.attr('src').replace(/\b(?:thumb|max)\b/,'original')+'" download="'+name+'.'+ext+'"><img class="UserLibraryImage" style="max-width:50px;max-height:50px;" src="'+img.attr('src').replace(/\b(?:thumb|max)\b/,'original')+'"></a>').click(function(){$(this).css('opacity',0.5);});}).toArray(); $('<div style="position:absolute;width:100%;height:100%;overflow-y:auto;top:0;left0;z-index:1000000;background-color: #ccc;"></div>').html(links).appendTo('body');}());


~~~

~~~

javascript:(function(){ "use strict"; $('body').keydown(function(e) { var n,o,t; if( e && e.altKey && (48 <= e.keyCode) && (58 >= e.keyCode) ){ n=e.keyCode - ( 48===e.keyCode ? 38 : 49 ); o=$('#secondary-toolbar ul.mode.tokenactions'); if(o && 'none' !== o.css('display')) { t=o.children()[0].children[n]; if(t) { t.click(); } } } }); }());
~~~


[Aaron Enhancement Pack](https://app.roll20.net/forum/post/2344777/slug%7D)

