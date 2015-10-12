---
layout: page
title: About
description: "Chan's introduction."
tags: [about, Jekyll, theme, responsive]
modified: 2014-08-08T20:53:07.573882-04:00
comments: true
---

<div class="main">
 <!--Language Selector -->
<select onchange= "onLanChange(this.options[this.options.selectedIndex].value)">
    <option value="0" selected> 中文 Chinese </option>
    <option value="1"> 英语 English </option>
</select>

<!-- Chinese Version -->
<div class="zh">
    <blockquote>
        梦想很大，步伐要慢。<br />
        世界那么大，<br />
        多走走看看。
    </blockquote>

<p><b>金璨</b>，就读于上海应用技术大学软件工程 12 级，大四。</p>

<p>理想青年，<a href="https://jincan39.github.io/">文艺范geek</a>。曾在mbp（<a href="http://www.mbpsoft.com/" target="_blank">现代商友</a>）前端团队实习半年载，主攻 Java/JavaScript，也玩玩其他语言，希望成为一名<a href="http://www.zhihu.com/question/19677325">项目经理</a>.</p>
    
<p>软件工程师，Software Engineer。英文熟练CET6,曾有过Java Web项目(SSH框架)，hybrid app项目开发经验，熟悉Java,熟悉HTML5／CSS3/JS，SQL数据库.自学了<a href="https://github.com/jincan39/Mars">腾讯前端规范</a>和<a href="https://github.com/jincan39/Alice">支付宝CSS前端方案</a>. 熟悉前后端架构，亦使用ruby/python,了解Object C(Swift)/VB。</p>
<p>
在大学期间曾利用树莓派
<a href="https://www.raspberrypi.org">（Raspberry Pi）</a>实现过关于
<a href="http://www.cnblogs.com/xiaowuyi/p/4051238.html">网络云储存多媒体</a>
<a href="http://techcrunch.cn/2014/06/06/sherlybox-creates-a-network-storage-system-on-your-desk/">(私有云)</a>及<a href="http://www.verious.com/tutorial/bringing-star-trek-to-life-lcars-home-automation-with-arduino-and-raspberry-pi-piday-raspberrypi-raspberry-pi/">家庭智能系统</a>。
</p>

<p>设计师，UI/UX Designer，迷恋 OSX/iOS & Android & Windows/Linux，擅长 Layout/Typographic 与动效设计（Motion Graphic），会一些PS处理和Flash动画（ActionScript） </p><br />

<p>产品狗，热衷于 Web & Mobile 产品，<a href="http://www.zhihu.com/people/jincan39">知乎</a>用户。轻微<a href="/tags/#职业病">职业病</a>，没事想想用户痛点、行业趋势、商业模式，无论身处什么职位都很在乎产品本身</p><br />

<p><del>会计师</del>，自学并考过了会计上岗证，目前正在准备报考注册会计师CPA</p>
<p><del>健身教练</del>，热衷于健身，是个有八块腹肌的肌肉男😣</p>

    <hr>
    附上认真版的简历:
    <ul class="active-list">
        <li><a href="{{site.baseUrl}}/attach/121042Y126-金璨－2016届毕业生就业推荐表.doc"> Chan_DEV_cn 2016届毕业生就业推荐表</a></li>
    </ul>

    一些期待成为的角色:
    <ul>
    <li> "Full Stack" Engineer/Designer </li>
    <li> End to End Java(Object c/.NET)/JavaScript Engineer</li>
    <li> Project Mannager </li>
    <li> Creative Technologist </li>
    <li> Product Engineer </li>
    <li> UX Unicorn </li>
    </ul>
</div>
<!--zh div end-->

<!-- English Version -->
<div class="en">
    <blockquote>
        Designer or Engineer, things in between.
    </blockquote>

    <p>Student, major in New Media Art of <a href="https://en.wikipedia.org/wiki/Communication_University_of_China">Communication University of China</a>, which is a interdisciplinary subject of technology and art, and now Senior.</p>

    <p>Programmer, JavaScript Engineer Intern of <a href="http://m.wepiao.com/index.html">Wechat Movie</a>, previous worked in <a href="http://alitrip.com" target="_blank">Alibaba Trip</a> as Front End Engineer for one year, looking for opportunities abroad.</p>

    <p>Designer, offered as UI/UX Designer Intern by Alibaba Group, Microsoft Bing etc. Experienced in Motion Graphic Design, also familer with Layout and Typography.</p>

    <p>Product Design and Program Management is also attractive and comfortable to me.</p>

    <p>My Chinese name is <b>Huang Xuan</b>, you can call me English name <b>Hux</b> for short.</p>

    <hr>
    Interested in more details? Just checkout my resumes:
    <ul class="active-list">
        <li><a href="{{site.baseUrl}}/attach/2016_Hux_DEV_en.pdf"> 2016_Hux_DEV_en </a></li>
        <li><a href="{{site.baseUrl}}/attach/2016_Hux_PD_en.pdf"> 2016_Hux_PD_en </a></li>
        <li><a href="{{site.baseUrl}}/attach/2015_Hux_UX & PD_en.pdf"> 2015_Hux_UX & PD_en </a></li>
    </ul>

    My dream position include:
    <ul>
        <li> UX Unicorn </li>
        <li> Product Engineer </li>
        <li> Creative Technologist </li>
        <li> End to End JavaScript Engineer</li>
        <li> "Full Stack" Engineer/Designer </li>
    </ul>
</div>
<!--en div end-->


<!-- Handle Language Change -->
<script type="text/javascript">
    var $zh = document.querySelector(".zh");
    var $en = document.querySelector(".en");
    function onLanChange(index){
        if(index == 0){
            $zh.style.display = "block";
            $en.style.display = "none";
        }else{
            $en.style.display = "block";
            $zh.style.display = "none";
        }
    }
    onLanChange(0);
</script>

</div>
<!--main div end-->

{% if site.useDuoshuo %}
<!-- 多说评论框 start -->
    <div class="comment">
        <div class="ds-thread" data-thread-key="{{page.id}}" data-title="{{page.title}}" data-url="{{site.url}}/about/"></div>
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
