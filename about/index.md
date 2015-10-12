---
layout: page
title: About
description: "Chan's introduction."
tags: [about, Jekyll, theme, responsive]
modified: 2014-08-08T20:53:07.573882-04:00
comments: true
---

<div >


<!-- Chinese Version -->
<div class="zh">
    <blockquote>
        梦想很大，步伐要慢。<br />
    </blockquote>
</div>

</div>
<!--main div end-->

{% if site.useDuoshuo %}
<!-- 多说评论框 start -->
    <div class="comment">
        <div class="ds-thread" data-thread-key="{{page.id}}" data-title="{{page.title}}" data-url="{{site.url}}/friends/"></div>
    </div>
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
