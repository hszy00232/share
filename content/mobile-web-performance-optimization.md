<section data-state="bg-cover">
    <style>
        .bg-cover body {background-image: url(//farm4.staticflickr.com/3254/3120186015_b5e4feaa19_b.jpg)}
    </style>
    <h1 style="bottom:15%;top:auto;">移动Web性能优化</h1>
</section>

<style>
.reveal li {
    margin: 1em 0;
}
</style>

--------------------

# Web性能会影响哪些?

-------------------------

>2006年，Google实验性地把一个搜索页的结果调整为30个，导致多花费了半秒时间来加载页面，在这个实验里，流量和收益都减少了20个百分点。

&nbsp;

>2010年，Forrester研究所的Akamai的一项研究表明，网页响应时间一旦超过3秒，会有57%的用户放弃浏览页面。

&nbsp;

>由Tealeaf科技（现在已经并入IBM）委托的“Harris的互动2011移动 交互调查”显示，在前一年有过移动消费经历的成年人中，有85%希望移动设备上的体验能与手提电脑或者PC上的体验相当，甚至于更好。并且有63%的人表示，一旦他在移动设备上的交易遇到了一个问题，他们就不会再想通过其他渠道去购买这个公司的其他产品了。

&nbsp;

在2012年，由Strangeloop网络（现已并入 Redware）发起的一项针对200家领先的电子商务网站研究表明，3G网络环境下，平均加载时间为11.8秒（图1），而在LTE（4G）环境下，加 载时间只有轻微的改善，为8.5秒。


-------------------------

##影响性能的原因?

* 移动设备天生的限制：带宽低，内存小，处理器性能低
* 网页比以前更大
* 延迟相当巨大
* 下载速度相差巨大

-----------------------

##移动端性能优化？

* 减少依赖文件
* 降低每个请求加载的大小
* 减轻客户端负担

-----------------------

##Notes about rendering

* Browser [start rending](http://www.yahoo.com/) as soon as it receives HTML
* Browser downloads components(js/css/image) parallel in a queue
* Connections per host are [limited](http://www.stevesouders.com/blog/2008/03/20/roundup-on-parallel-connections/)

-------------------

## #0 减少依赖文件 

* 减少HTTP请求数
  * 整合资源
  * 使用浏览器缓存和本地缓存
  * 在HTML中嵌入资源
  * 消除重定向

------------------

## #1 降低每个请求加载的大小

* 压缩文本和图像
* 调整图片大小
* 使用HTML5和CSS 3.0来简化页面

------------------

## #2 减轻客户端负担

* 延迟渲染”BELOW-THE-FOLD”内容
* 延迟读取和执行的脚本
* 将CLICK事件替换成TOUCH事件

------------------

## Books

<a href="http://search.safaribooksonline.com/book/web-development/9780596529307"><img src="http://akamaicovers.oreilly.com/images/9780596529307/lrg.jpg" style="max-width: 40%;display:inline-block;" /></a> &nbsp; &nbsp;
<a href="http://search.safaribooksonline.com/book/web-design-and-development/9780596803773"><img src="http://akamaicovers.oreilly.com/images/9780596522315/lrg.jpg" style="max-width:40%; display:inline-block" /></a>


------------------

## Online Resources

* [Best Practices for Speeding Up Your Web Site](http://developer.yahoo.com/performance/rules.html) from Yahoo! 
* [Web Performance Best Practices](https://developers.google.com/speed/docs/best-practices/rules_intro) from Google
* [Steve Souders](http://www.stevesouders.com/blog/)'s Blog

------------------

# &nbsp;

#Q & A
