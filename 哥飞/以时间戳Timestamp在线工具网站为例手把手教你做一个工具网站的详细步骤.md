![cover_image](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJuuAgkpkXAmDem5BQbcSUwmsISnFunHINqUapdKnAabDnyJfaABMSMg/0?wx_fmt=jpeg)

#  以时间戳Timestamp在线工具网站为例，手把手教你做一个工具网站的详细步骤

原创  我是哥飞  [ 哥飞 ](javascript:void\(0\);)

__ _ _ _ _

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJfhodK3sxWxMhn1n7qiaq1wMhHGu7zQFKNxVVQJl7tJjFBfzxy9ianhBQ/640?wx_fmt=png)

先放上面这张图镇楼，月访问量4880万，年收入200万到500万美元，这是工具站的顶级Top存在了。

大家小板凳坐好，我开始聊下，如果要做一个时间戳工具，会怎么做。因为我们是竞争者，所以用全力，所以每个语言单独做一个站。不太理解的可以先看下本公众号之前的文章。

这里以英文为例，其它语言以此类推，同理可得。

先从分析开始，谷歌搜索“  timestamp  ”，结果如下图：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJw62H9zTP9OQ6o9anDw5YuKIodRmYR6IFvsaM4bcEbLx21cvddcQszg/640?wx_fmt=png)

可以看到第一条就是工具，并且是顶级域名的首页，想超过他，有难度。但我们可以去学习一下，他为什么能够排第一。

第二是维基百科，这个高权重域名，我们一般也无法超过。但是既然第一个站可以排第一，把维基百科都比下去，说明第一个站还是有两把刷子的。

第三个，也是工具，也是直接首页，但是域名没有带关键字。就这种情况下，他能排第三，说明也是有点技术的。

第四名是内页，并且不是工具，是文章。那就说明，如果我们去做，做得好的话，有可能能够排到第四名，把这个给挤下去。

第五名，是protobuf.dev的一个文档页面，也算是文章类。

好，这么粗略分析下来，看起来竞争不大，我们的站如果优化得好，假以时日，是可以上首页，甚至上升第四名的。

接着，我们用关键字密度检测工具 https://tool.chinaz.com/tools/density.aspx ，查一下每个页面的 timestamp
这个关键字的密度。

第五名，密度 3.9%：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJRrFoibFicia6mwicqz5lAPQf81r916oFmpLFe9eR0tsIKOSXrKW4ltmJvg/640?wx_fmt=png)

第四名，密度4.1%：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJoR6dS5RSibuCwiaHbZGzT0kM5RVen2hlAdDoM56CA5UcTbWQqO4sNHrA/640?wx_fmt=png)

第三名，密度2.6%：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJBLfNuibL8HpGlvckYWtGjJJNbmECeFzPzsEFXVeEnR3qNPcEibdDcOfQ/640?wx_fmt=png)

第二名用国内工具查不了，所以直接在浏览器里  看  出现  次数  ，可以看到出现了  31次，很多了：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJgKPQv9JQQw6DWf8PSaq0GmutibZr8QiaEWYWQfJe9eGsXrZxMNpa8rdg/640?wx_fmt=png)

第1名，密度 1.4%：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJotYwxyBGTe5ibNXMP6fLDSpL9HmfgicTDE00thB82Zenia3D37gZTgia8w/640?wx_fmt=png)

第一名的关键字密度居然这么低，那么一定有什么其它地方做得好，让谷歌可以把他排到前面去，最有可能就是外链。

然后看下这几个域名的注册时间：

unixtimestamp.com 注册于 2003年10月09日

epochconverter.com 注册于 2007年05月08日

techtarget.com 注册于 1999年09月15日

protobuf.dev 注册于 2020年07月02日

可以看到我没有列出维基百科，因为这个站不能一般看待，后文我们直接略过这个站。

一般来说，我们可以假设，域名注册越久，运营越久，那么权重会越高，外链就会越多。

下面我们看下前两个站的反链数量，第一名  unixtimestamp.com  ，反向链接400万，引荐域名4900多个。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJbHs5VyUtWFKnZiaziaVuScr6FKQYiaibTN7zj7f8FXYMrI79ftF90UZj8A/640?wx_fmt=png)

第三名  epochconverter.com ，反向链接 13.8 万个，引荐域名 6900 多个。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJyj1j1ZicicMc5FXZ8ZlBFziaW0UtO8berLExpzfic9ibFzmEwhozbdm6hCA/640?wx_fmt=png)

讲到这里，我去查了一下，第三名，其实带了关键字，只是这个用法不常见。在计算机科学中，"epoch"通常指的是一个特定的起始时间点。例如，在Unix和Linux系统中，"epoch
time"指的是从1970年1月1日开始的秒数。

第四、五名是内页，而且是文章，我们也不去看反链了。

那现在就剩下第一名 unixtimestamp.com 和第三名 epochconverter.com 我们去看下搜索流量来源关键字。

拿第一名来说，可以看到全球各个国家都有搜索流量过来，因为他做了多语言。看了下，用的子目录形式，如中文地址是
https://www.unixtimestamp.com/zh/ 。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJYuBibM3yLpWglGL0HrEKRlQEednGWgNpibsPn082hskDZtOMXgOmeajw/640?wx_fmt=png)

这里我们选择流量最高的美国来查看，都有哪些关键字。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJvu1H1mAEecyC4wdX4VGPr3MiasTjlpY4KiaECsSgOkHjpKnLGCz2yblA/640?wx_fmt=png)

可以看到有些关键字虽然搜索量比较大，但是这个网站并没有排到第一。

拿“  utc time  ”这个词为例，第一名是 https://www.timeanddate.com/ 的内页，也就是我们文章开头的镇楼图对应的网站。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJTZdMCwm5upQNNPEKJXPZfVaWTqWuyAz8VIAozfqgYDc0hqcqia5LtXQ/640?wx_fmt=png)

我们先不管他，我们聚焦到 timestamp 这个词，找长尾词。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJRDPIgnUfCEDJZcEwvS5rX1ibNhaaOPxIq203KT7OQqicMibTg3O6XzPVQ/640?wx_fmt=png)

这些长尾词，就是我们需要抓住的，做到我们的网站里的。

同样的方法，我们找出第三名的长尾词，可以看到，第三名的 timestamp 相关长尾词，基本也是这些。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJ07v6fCMpvZwVd1tErkOl78I1eLadVy6MzQUtSGXgXJ6HhJTbiau3AJw/640?wx_fmt=png)

我们还可以去谷歌下拉找搜索需求词：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJibAuuZsEUV6UsWriag1fXZJTCSbZc1uvGuEzeI7IXqrHOrWUls2oibPQA/640?wx_fmt=png)

去谷歌相关搜索找：  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJzDar3h8837Wbia5pMALgficqtrqdeZzJCl7gMaMicmbkR5NfSMd6abd2A/640?wx_fmt=png)

把以上这些地方找到的长尾词都收集起来，按照出现次数排序，去重，我们就得到了我们网站能用的关键词列表。

然后我们去挑一个合适的域名，最好是com的，没有的话，其它后缀也行。或者加长，如 timestamptool.net 。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJLibRls0iaibZOJHzwYBYKYuVW9JL2P8saIDyE6oibMoeKYkX0GBicGgOibMg/640?wx_fmt=png)

找到合适的域名之后，就要规划全站路径了。我们是后来者，是竞争者，最好的办法是每个语言用一个域名做一个站，那么多语言切换时，直接换不同的域名就行。所以就不需要考虑子域名形式或者子目录形式做多语言。

那么要做的就是

/ 首页，根目录，做工具

h1 是 timestamp把所有长尾词都变成 h2有层级关系的就变成h2下的h3

/{h2关键字}/ 内页，h2层级目录

/{h2关键字}/{h3关键字}/ 内页，h2下的h3层级目录

这样把所有url结构规划好之后，就可以开始做页面了。

以首页举例：

要有时间戳多种转换形式：

1、从数字时间戳转化为年月日时分秒形式；

2、从年月日时分秒形式转化为时间戳；

3、每分每秒显示当前时间戳。

把以上时间戳转化做成模块，在多个页面都可以使用。

  
接着首页还需要把所有的h2、h3列出来。

每一个h2、h3都需要用一两段文字解释一下。

什么叫都解释一下呢，拿“timestamp sql”为例，我们就需要去告诉用户，在sql中如何获取时间戳，如何转化时间戳，如何使用时间戳。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJnLJJsk09q3qiaAnIibH2F5RBjZp4ibhgu6JI0yibPLp0ejVibT82Kz3u7mg/640?wx_fmt=png)

然后我们刚才说了，每个h2都需要做内页，还是以“timestamp sql”为例，在这个页面里，你就需要围绕“timestamp
sql”去做更详细的解释。基于这个关键字，会有更多的长尾关键字，都要解释到位。

如果内页页面里需要用到时间戳转换工具，那就引用一下刚才在首页已经做好的模块。

首页需要有列出所有的内页链接，至少需要h2和h3的链接。

所有的内页也需要到上一层级，直到首页的链接。

如h3页面，需要有h2和首页的链接。

注意制作页面时，注意保持关键字密度，你需要让每个页面的关键字的密度在5%左右，也就是超过之前最大密度4.1%。

以“timestamp sql”页面为例，这个页面会有很多文字，但  “timestamp sql”需要占所有字符的5%左右。

这里怎么计算呢？“times  tamp s  ql”总共13个字符，5%就是乘以20，也就是你的网页内容至少需要260个字符才行。如果你的网页需要
“times  tamp s  ql”出现3次，那么网页总字符需要780个。注意，空格和换行也算字符。

基于以上方法，把所有页面都做好。然后做好sitemap，就可以提交到搜索引擎了。

但是，你会发现，以上页面都是静态页面，只要做好了，就几乎不会增加新页面，如果我想让搜索引擎爬虫经常来怎么办？

可以学下面这两个网站，做动态页面，每一些时间戳都收录进去。时间戳页面url举例 /timestamp/1672502400 。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJicg8KznLtnoKZeicBdTScnZ3WPHZHRuVbmicLoibwurRQYKHEn0LDdVOrw/640?wx_fmt=png)

可以做一些层级，按年，按月按日分组，每天挑选整点时刻生成页面，将来时刻的页面也可以先生成。

分组后，可以是这样 /timestamp/2023/01/01/{秒时间戳} 。

做好之后，就是和时间交朋友了。

不过，因为我们是挑战者，最好能够做得更漂亮，更好用，让用户能够自发传播。

另外，站长之家的这个时间戳工具页面 https://tool.chinaz.com/Tools/unixtime.aspx ，值得学习。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJ0VHbcvhLGnLdrWcW7Z5Od4DMO8lxX7OjnvAxA43hOW3iaBMSnticmicSA/640?wx_fmt=png)

好了本次分享结束，以上就是昨天哥飞在 [ 人人都能学会的发掘 web 产品需求方法入门
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650079475&idx=1&sn=6d37631726b73f988d5c98b5d0ed3f87&chksm=bf3f31c88848b8de0ad5ab17faab210bccab8b0eaa3ae782d8e67fff4099e1480d2560b419a3&scene=21#wechat_redirect)
提到，会在哥飞的付费群里分享的操作技巧。  

今天哥飞把这个技巧分享出来，给关注哥飞公众号的所有朋友看。

最后再次推荐哥飞  运营的  “哥飞的朋友们  ”  付费社群，社群好不好，看看群友们怎么说，都是7月26日新鲜出炉的发言：

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeictj4gR85ZdHWopfVibqxkbtJEaywHT2dMINPB8hY4ZXt0cV1oSJJeedjQAJPsLyHjXz2FBBG6KsoQw/640?wx_fmt=jpeg)

对付费社群感兴趣的，请加哥飞微信 qiayue 交流。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeictmH6ZbzrmhFdgH55yNiarBAXwFK5njpE3j8ehd8M5CNnh5mX01ibDAls4gZvob7nUmwXnscEXNDm3g/640?wx_fmt=png)

预览时标签不可点

微信扫一扫  
关注该公众号





****



****



  收藏

