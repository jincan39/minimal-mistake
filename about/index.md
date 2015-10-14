
>梦想很大，步伐要慢。
>
>世界那么大，多走走看看。

#### 金璨
&nbsp;&ensp;&emsp;*就读于上海应用技术大学软件工程12级，大四。*

**理想青年**，
>&emsp;<a href="https://jincan39.github.io/">文艺范geek</a>。曾在mbp（<a href="http://www.mbpsoft.com/" target="_blank">现代商友</a>）前端团队实习半年载，主攻 Java/JavaScript，也玩玩其他语言，希望成为一名项目经理/技术达人.


**软件工程师**，
>&emsp;Software Engineer。英文熟练CET6,曾有过Java Web项目(SSH框架)，hybrid app项目开发经验，熟悉Java,熟悉HTML5／CSS3/JS，SQL数据库.自学了<a href="https://github.com/jincan39/Mars">腾讯前端规范</a>和<a href="https://github.com/jincan39/Alice">支付宝CSS前端方案</a>. 熟悉前后端架构，亦使用ruby/python,了解Object C(Swift)/VB。
在大学期间曾利用树莓派<a href="https://www.raspberrypi.org">（Raspberry Pi）</a>实现过关于<a href="http://www.cnblogs.com/xiaowuyi/p/4051238.html">网络云储存多媒体</a><a href="http://techcrunch.cn/2014/06/06/sherlybox-creates-a-network-storage-system-on-your-desk/">(私有云)</a>及<a href="http://www.verious.com/tutorial/bringing-star-trek-to-life-lcars-home-automation-with-arduino-and-raspberry-pi-piday-raspberrypi-raspberry-pi/">家庭智能系统</a>。

<del>设计师</del>，
>UI/UX Designer，迷恋 OSX/iOS & Android & Windows/Linux，擅长 Layout/Typographic 与动效设计（Motion Graphic），会一些PS处理和Flash动画（ActionScript）

**产品**，
>&emsp;热衷于 Web & Mobile 产品项目管理，行业趋势、商业模式，思维导图分析，团队沟通，无论身处什么职位都很在乎产品本身.

<del>会计师</del>，
>自学并考过了会计上岗证，目前正在准备报考注册会计师CPA

<del>健身教练</del>，
>热衷于健身，是个有八块腹肌的肌肉男😣

---
>*附上学校版的简历:*
&emsp;<a href="https://github.com/jincan39/jincan39.github.io/blob/master/attach//121042Y126-金璨－2016届毕业生就业推荐表.doc"> Chan_DEV_cn 2016届毕业生就业推荐表</a><br />
    
{% highlight html %}
<a href="https://github.com/jincan39/jincan39.github.io/attach/121042Y126-金璨－2016届毕业生就业推荐表.doc"> Chan_DEV_cn 2016届毕业生就业推荐表</a>
{% endhighlight %}
 


> **一些期待成为的角色:** 
> - **"Full Stack"** Engineer/Designer 
> - End to End Java(Object c/.NET)/JavaScript Engineer
> - Project **Mannager**
> - Creative Technologist 
> - Product Engineer
> - UX Unicorn

**欢迎同我联系!** Welcome/Feel FREE to contact me😊.
{: .notice}


$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$


```sequence
Title:15年11月开始求职
我->>企业: 求职请求（SYN=1,seq=client_isn） 
企业-->我: 建立联系（SYN=1,seq=client_isn）\n ack=client_isn+1
我-->>企业: 面试请求（SYN=1,seq=client_isn） 
企业-->我: 面试通过（SYN=1,seq=client_isn）\n ack=client_isn+1
我->>企业: 确认入职（SYN=0,seq=client_isn+1）\nack=server_isn+1
```
