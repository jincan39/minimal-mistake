---
layout: page
title: friends
description: "Hey, this is Channing."
tags: [about, Jekyll, theme, responsive]
modified: 2014-08-08T20:53:07.573882-04:00
comments: true
---

<!------->
<!--layout: page-->
<!--title: "About"-->
<!--description: "Hey, this is Hux."-->
<!--header-img: "img/about-bg.jpg"-->
<!------->

<!-- Language Selector -->
<select onchange= "onLanChange(this.options[this.options.selectedIndex].value)">
    <option value="0" selected> 中文 Chinese </option>
    <option value="1"> 英语 English </option>
</select>

<!-- Chinese Version -->
<div class="zh">
    <blockquote>
        朋友朋友朋友梦想造飞机，不想造轮子。<br />
        世界那么大，<br />
        多玩玩看看。
    </blockquote>

   
</div>







{% if site.useDuoshuo %}
<!-- 多说评论框 start -->
    <div class="comment">
        <div class="ds-thread" data-thread-key="{{page.id}}" data-title="{{page.title}}" data-url="{{site.url}}/about/"></div>
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
