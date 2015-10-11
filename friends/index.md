---
layout: page
<!--title: Theme-->
tags: [about, Jekyll, theme, responsive]
modified: 2014-08-08T20:53:07.573882-04:00
comments: true
---


## Some other style blogs:


<a markdown="0" href="http://markyun.github.io/" class="btn">马云云</a>
<a markdown="0" href="http://qiudeqing.com/article.html" class="btn">qiudeqing</a>
<a markdown="0" href="http://lingyu.wang/#/category/JS技术" class="btn">lingyu.wang</a>
<a markdown="0" href="http://ecomfe.github.io/" class="btn">ecomfe官网</a>
<a markdown="0" href="http://blog.smdcn.net/" class="btn">smdcn</a>
<a markdown="0" href="http://hmqk1995.github.io/" class="btn">hmqk1995</a><br />
<a markdown="0"><a href="jincan39.github.io" class="btn btn-info">Chan</a>


* Responsive templates. Looking good on mobile, tablet, and desktop.
* Gracefully degrading in older browsers. Compatible with Internet Explorer 8+ and all modern browsers.
* Minimal embellishments -- content first.
* Optional large feature images for posts and pages.
* Simple and clear permalink structure.
* [Custom 404 page](http://mmistakes.github.io/minimal-mistakes/404.html) to get you started.
* Support for Disqus Comments

{% highlight html %}
Comment below to exchange links
{% endhighlight %}

<!--<a markdown="0" href="{{ site.url }}/theme-setup" class="btn">Install Minimal Mistakes Theme</a>
-->

<!--## Buttons-->

<!--黑<div markdown="0"><a href="#" class="btn">Primary Button</a></div>-->
<!--绿<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>-->
<!--黄<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>-->
<!--红<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>-->
<!--蓝<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>-->

  {% if site.useDuoshuo %}
<!-- 多说评论框 start -->
    <div class="comment">
        <div class="ds-thread" data-thread-key="{{page.id}}" data-title="{{page.title}}" data-url="{{site.url}}/friends/"></div>
    </div>
    <!--<div class="ds-thread" data-thread-key="请将此处替换成文章在你的站点中的ID" data-title="请替换成文章的标题" data-url="请替换成文章的网址"></div>-->
<!-- 多说评论框 end -->

<!-- 多说公共JS代码 start (一个网页只需插入一次) -->
<script type="text/javascript">
var duoshuoQuery = {short_name:"jincan39"};
    (function() {
        var ds = document.createElement('script');
        ds.type = 'text/javascript';ds.async = true;
        ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';
        ds.charset = 'UTF-8';
        (document.getElementsByTagName('head')[0]
         || document.getElementsByTagName('body')[0]).appendChild(ds);
    })();
</script>
<!-- 多说公共JS代码 end -->
{% endif %}
