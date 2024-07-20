![cover_image](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaShhzETVL4LDrQ8U6IAr7ibbUzDKaZ82dORM8fW2vM1x2v5lplnuJQWSA/0?wx_fmt=jpeg)

#  【哥飞评站】AI贴纸生成网站 StickerBaker 的SEO评测报告和改进建议（4000字）

原创  我是哥飞  [ 哥飞 ](javascript:void\(0\);)

__ _ _ _ _

大家好，我是哥飞。  

受社群里 @damo 老板的启发，哥飞决定从今天开始一个新栏目，不定期点评一些网站，说说他们有哪些做得好的地方，有哪些还值得改进的地方。

大家如果有需要点评的网站，也可以加哥飞微信 qiayue 提交，哥飞会挑选有特点的网站来点评，当然也支持付费点评你指定的网站。

今天是第一期，哥飞点评一下前两天在《  [ 【哥飞推荐】一个开源AI贴纸生成器，同时也是
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082220&idx=1&sn=c0f1a723fc79bc86979ac4f5fdbac74b&chksm=bf3f3a978848b381e2eed5d158bb775506395be25f221aaf03333e5aa4fe65f00f42f27e45fd&scene=21#wechat_redirect)
》介绍过的AI贴纸生成网站 StickerBaker.com 。

这个网站的代码是开源的，如果大家想要部署，可以看上面这篇文章。  

下面我们先看下网站首页，中规中矩，很典型的AI工具站的布局，从上到下依次是导航、Logo、工具表单、最新作品列表等。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicvShG7sltiaNTDTsicWsRKq4rQTH2hUL45PbdxDhVYxKDR7ARsfNwCWmQ0utX2deLiaNickFiaFwgVrfHw/640?wx_fmt=png&from=appmsg)

整个网站目录结构目前也比较简单，主要由以下几个页面构成：  
/  首页  
/  s  ticker/{id} 单个贴纸详情页  
/stickers 用户生成的贴纸列表  
/search 贴纸搜索入口  页  
/search?query={input  } 贴纸搜索结果页

上面这些页面里，首页是入口，所以需要把整个网站最核心的功能都展示出来，一是生成贴纸，二是浏览发现贴纸，三个功能导航如搜索入口、用户贴纸列表入口等。

虽然暂时不支持登录注册，但依然做了个人中心页面，可以列出当前浏览器用户生成的所有贴纸。  

贴纸  详情页和搜索结果页是亮点页面，这两个都可以动态生成海量页面，被搜索引擎收录之后，获取大量长尾关键词的流量。  

下面我们一个一个页面来看  一下，这里需要用到在《 [ 推荐一款好用且免费的SEO插件，哥飞天天都在用
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082258&idx=1&sn=e5d0a8e9a89c3793013d97ba53496c9c&chksm=bf3f3ae98848b3ff9bbdd5270be5b0a44ef41df81a89307190ff927c22f5bfde00f97ff76dd1&scene=21#wechat_redirect)
》介绍在  AITDK SEO Extension 这个浏览器插件。

** 一、首页  **

打开首页，点击  AITDK SEO Exte  nsion ，查看概览信息。
![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicvShG7sltiaNTDTsicWsRKq4rJZYDicuKUdIBUN5Sn8fnQu8vsiaEcGiac4iczXtjTT37obVvFgE5HZHeMQ/640?wx_fmt=png&from=appmsg)

** 1.1、Title  **

可以看到 Title 推荐长度是60个字符，但这个网站只用到了12个字符，这有点浪费，没有把需求关键词尽可能在 Title 中体现出来。

可以看这篇《 [ 【哥飞带你读】你需要了解的10个重要SEO元标签（上）
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082107&idx=1&sn=62f664473462228f5d03fb10d29ffa32&chksm=bf3f3a008848b3166bce42c86fdd070cead41af4df106fabd7f490ab6cbfcc38683f42183a05&scene=21#wechat_redirect)
》介绍的关于 Title 的最佳实践。  

** 1.2、Description  **

同样，Description 推荐长度是160个字符，这个网站只用到了21个字符，不过好在把核心关键词“Stickers AI”体现出来了。

** 1.3、Keywords  **

哥飞不推荐大家用 Keywords，所以这里不写是对的。

** 1.4、Canonical  **

Canonical 缺失，这个不应该。

可以在《 [ 【哥飞带你读】你需要了解的10个重要SEO元标签（下）
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082126&idx=1&sn=5a4d4b231eec5ac66ccb9ffa64382025&chksm=bf3f3a758848b363fc6a402e40840001f3bb8363c76be5658f3296d62fbb4d59dcd62d0ac063&scene=21#wechat_redirect)
》看到  Can  onical 的最佳实践，看完大家就知道，这个标签还是很建议写上的。

**1.5、Sitemap**

sitemap.xml 倒是不一定必须，尤其是对于页面数量有限的网站来说，谷歌自己就会把页面都爬了，不一定要用 sitemap.xml 。

不过  Can  onical 和  sitemap.xm  l 都是有比没有好，所以哥飞推荐大家都配置上。

** 1.6、Headings  **

再看 Headings ，会发现这个网站的 H 标签使用混乱，首页用到了两个 H1 ，而且都没有体现出网站的需求关键词。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSRTqWIjsZJoCUeXfEZQ4u17P8alKRMudTvtAsCwaNNHRjiaL9c0wpKXg/640?wx_fmt=png&from=appmsg)

哥飞建议一个页面只放一个H1，在H1里放你网站要做的核心关键词，如这个网站可以体现“Sticker Maker”这个关键词。

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSHltg7vJfMGz1jOlyXkNVAwcMwczopgwMp4PX5420fnhHVUuw9ZsSlg/640?wx_fmt=jpeg)

那么到底要怎么编写一个合理的H1呢，欢迎大家加入哥飞的付费社群学习。  

“Upload”这里是否可以用 H 标签呢？  

肯定是不能用H1，甚至H2都不能用，这里建议用H3，  结构就变成：  
H2:  C  onvert photo  to sticker  
H3  :  Upload photo

原因如下：
![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSiaJS7NqJ8l7ibCgKGQNznKVMGoSsJgEPur67GvJDsbEzcdWpAc1jcNWA/640?wx_fmt=png&from=appmsg)
![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSfdfyUiagOQedZ3DficqwZRdJ8QlBrnNWIx5NP9mHQ5FZSYmyN2xIdeoA/640?wx_fmt=png&from=appmsg)

当然他这里还有个核心需求是“Face to Sticker”，这个也需要体现出来，那么就可以改成这样：  
H2:  C  onvert face photo  to sticker  
H3: Upload face photo  

“Latest”也建议改为“Latest Generated Stickers”，并且用H2标签。  

** 1.7、图片  **

再说图片，这个网站的图片处理做得还是不错的，除了三个用到了网站ICON的地方没给图片加Alt，其它图片都加了合适的 Alt 。

不过哥飞建议生成的 Sticker 图片的 Alt 可以写长一点，体现 Sticker 关键词，如“Ayna”可以改为“Ayna Sticker”。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSGmaHctvdghoVSBY7GTicVZGicnDmicB9PbfYUnTBbohOD7U78K6zOmlDA/640?wx_fmt=png&from=appmsg)

**1.8、链接**  

可以看到这里有三个出站链接，都是Dofollow的，他这里都是自己可控的出站链接，所以用 Dofollow 也可以，不是一定出站链接就要Nofollow。  

关于链接如何设置请看《 [ 【哥飞带你读】你需要了解的10个重要SEO元标签（中）
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082113&idx=1&sn=bedf2b5a87ac6cc0d4aee2b60febc61f&chksm=bf3f3a7a8848b36c90819dc236a7ee36eae6b00d0a4fa04e551ac5c171f42631e06ef1bd85cf&scene=21#wechat_redirect)
》《 [ 再聊内链建设：内链重要性不亚于外链
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080958&idx=1&sn=2fbf04e3d60df159f04229a1ab3bcbae&chksm=bf3f37858848be93fc80626f87ab77271ae783fb689fe023a5d2ac110e14345fdf97482d2727&scene=21#wechat_redirect)
》。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSYsDpVSshbHibHzBmuaQpMicXR7gZicEQuVsO9etyrfM1x5YicWWtdp8HKQ/640?wx_fmt=png&from=appmsg)

**1.9、社媒**

这里不错，Open Graph 和 Twitter Card 都设置了。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaS2IZGnTb1myqicXN6mwGHXlVLJl9jJuqC1x6liacqDQxuJ8b8984mFqjA/640?wx_fmt=png&from=appmsg)

**1.10、** **Hreflangs 和 Structured**

这个网站暂时没有做多语言，所以  Hreflang  s 绑定没有设置。  

具体要怎么绑定，可以看 Hix.ai 的首页 HTML 代码学习一下。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSpEPA41Snr6VIhZR3aOVhdnP99sBCWSPAlrHDcPjfrOMYc6uhqLwprg/640?wx_fmt=png&from=appmsg)

也没有设置结构化数据，具体有什么效果可以看《 [ 10种谷歌结构化搜索结果样式介绍及实现方法，最骚的是第9种
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650079358&idx=1&sn=8633a276dd94efc971cc2ca2239a34d6&chksm=bf3f31458848b853b74dfe41cebfc4da5c639a3519bf20bac7d3888bee99d27819c2cb95a999&scene=21#wechat_redirect)
》。  

**1.11、首页总结**  

看完上面这些基础SEO信息，可以发现大部分都做得还行，就是H标签需要改的比较多。

除了这些，  哥飞再跟大家说下这个网站首页有哪些做得好的地方：  

  1. 首页最核心区域直接放置工具的入口，让用户一打开网站就能够一眼看到满足他们核心需求的工具，然后就开始使用工具，这可以提高页面停留时间； 

  2. 首页增加了最近作品列表，每次刷新都会取出最新的，对于搜索引擎来说，这是一个频繁更新的页面，每次搜索引擎爬虫过来，都能够有新东西可以抓，于是这个网站被收录的页面就会越来越多； 

  3. 首页的最新作品列表还会在用户使用时不断冒出新的贴纸，给用户感觉这个网站很火，还有很多人在使用，我也要去试一试。 

  
当然也还  有些值得改进的，如目前首页的更多贴纸是通过上拉获取更多的，而搜索引擎爬虫无法做上拉操作，所以建议首页增加Discover链接，点击后进入
Discover 页面，能够分页展示所有贴纸，这样搜索引擎就能够爬取到所有贴纸。  

  

** 二、贴纸详情页  **

哥飞以 /sticker/29961 为例，点评一下贴纸详情页。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSsWYSYhRGDVIKmMaFEVdexu9lvXoqRu924XeOI41EBY2C0iaxV5rpKibw/640?wx_fmt=png&from=appmsg)

**2.1、URL**  

这个站URL直接用的数字ID，容易被从1开始遍历，扒站的爬虫会很喜欢这种路径，  建议改为  /sticker/29  961-fairy-unicorn
。

程序读取的时候有两种办法，一是拆分解析得到29961之后从数据库根据ID读取内容；二是数据库增加 url 字段，保存“  29  961-fairy-
unicorn  ”字符串，之后直接用路径从数据库读取。  

另外注意，如果用户输入的生成贴纸的提示词比较长的话，不建议直接拿来做URL，而是可以抽取主要关键词作为URL。

** 2.2、SEO基础信息  **

之后的内页哥飞就不一项一项说了，大家可以参考首页点评去对照。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSevF3IHIot57feZoeS938PdFs8oGgl0oDQFyv8n1NLb4lV6LsmiaPSIg/640?wx_fmt=png&from=appmsg)

这里说下贴纸详情页的Title，目前的写法估计是考虑到分享出去时显示的标题更好看，但是其实可以把“I made an”去掉，直接是“AI Sticker
of fairy unicorn”就很好了，核心关键词“  AI Sticker  ”和长尾关键词“  fairy unicorn  ”都照顾到了。

为了分享出去的标题好看，就可以去设置Open Graph和Twitter Card的标题为“I made an AI sticker of fairy
unicorn”。  

描述则可以更长一些，可以加上行动召唤，提升CTR，具体可以看这里《 [ 【哥飞带你读】你需要了解的10个重要SEO元标签（上）
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082107&idx=1&sn=62f664473462228f5d03fb10d29ffa32&chksm=bf3f3a008848b3166bce42c86fdd070cead41af4df106fabd7f490ab6cbfcc38683f42183a05&scene=21#wechat_redirect)
》。

** 2.3、Headings  **

H 标签依然还有同样的问题，层级错乱。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaS5J1ACHFnWrYBaWITZ8DFia3FRs8Ayn9T2uBFIdLzfbPzw2N85x0Df0w/640?wx_fmt=png&from=appmsg)

首先是 H1 必须体现核心关键词，可以是“fairy unicorn”，更好的是“AI Stickers of fairy unicorn”。  

“Similar-ish stickers” 则可以放在 H2。  

** 2.4、贴纸详情页总结  ** ** **  

这个页面其实已经做得挺不错的了，或者说，知道要做贴纸详情页这件事情，并且去做了，就是很不错的。  当然上面我们也看到了，会有一些细节需要去调整。

尤其是相似贴纸这个真是神来之笔，可以有效的提升长尾关键词“  fairy unicorn  ”的  关键词密度  。

不过目前相似贴纸是前端获取数据并渲染的，哥飞建议要改成后端渲染，这样才能被搜索引擎抓取到，从而提升关键词密度，进而让这个页面能够拿到更靠前的排名。  

  

** 三、搜索首页  **

“Sticker Search”这个关键词是有一定的搜索量的，虽然不大。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaS6qLu4fVPQaURKysOwd0umqV4DwUURGRxddln3GiaeuVrFoshgRRo8Lg/640?wx_fmt=png&from=appmsg)

所以这个站专门做了一个搜索入口页面，主打“  Sticker Sear  ch  ”这个关键词，这个做法很正确。

不过也有还有些细节需要改进，下面我们一一来看下。  

** 3.1、SEO基础信息  **

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSBnoejkHEResUMiapyRw41SBUO1UbbJ81L9dqM02NzgrgoR5LK7FjNLQ/640?wx_fmt=png&from=appmsg)

标题用的是“  StickerSearch  ”而不是“  Sticker Search  ”  ，哥飞猜测站长是想把  贴纸搜索打造成一个品牌。

这个思路是对的，看下两个关键词的网页供应量就知道了，不带空格的作为品牌名称完全没问题的，因为网页供应量少，当用户习惯使用不带空格来搜索之后，这个站长的新站就更容易拿到更靠前的排名。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSud9zYPPU6LTpBbziadQFP99RqbgB36TZDrHqDxUTicbKPLPQBcclgs6A/640?wx_fmt=png&from=appmsg)  
---  
![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaScko2AicIxXdsfFIs59q7Etgg4HAUBQowwicdTwYJHiaWg0SDibt5YRBlpw/640?wx_fmt=png&from=appmsg)  
  
  
不过也有个小问题，因为目前用户更容易想到的还是带空格的写法，所以网页Title、Description、H1等地方就需要把有空格的也兼容到。

** 3.2、Headings  **

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSwbTp02eAhNhia8qAoqdKEVtnVjISWzb6HJZMZ5KJTAoWdJhJtV2rC1g/640?wx_fmt=png&from=appmsg)

这里只用了一个H5，也是极其不合理的，应该改成H1，并且多增加一些内容和标签。

** 3.3、搜索首页总结  **  

设置一个单独的搜索首页是很不错的做法，有可能能够获取到一些流量。不过依然还是有很多细节值得改进。  

  

** 四、搜索结果页  **

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaShCTaoQrGcPqZX5X0POttZFSPuzaIHoPLasxOwobW1DUvSu85ctDVgw/640?wx_fmt=png&from=appmsg)

增加搜索结果页的好处显而易见，可以获取大量用户真实需求关键词，生成大量长尾关键词页面，被搜索引擎抓取后，从搜索引擎获取海量搜索流量。  

不过，依然还是有一些细节值得修改。  

** 4.1、SEO基础信息  **  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSiaqV6IglMqBpJPKEtIt6iafLJHMRmVHksdVohYYWyHDR4qgBTKWJve1Q/640?wx_fmt=png&from=appmsg)

不管搜索什么关键词，Title和Description都固定文案了，没有根据搜索关键词去调整，这跟搜索结果页目前用的前端渲染方案有关。  

目前前端渲染，虽然会产生很多的搜索结果页面，但是在搜索引擎爬虫看来，这些网址不同的页面其实HTML内容都是重复的，这是SEO大忌。

建议作者修改为后端渲染，这样就可以有效的利用真实用户搜索生成大量的长尾关键词页面了。

**4.2、Headings**  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSHqdE5gwIicz40iadHx2XrQK6NQztquAUibWueXAXjFBp2oUsPQRM9Lqpw/640?wx_fmt=png&from=appmsg)

依然是因为前端渲染导致的问题，目前H标签的标题都写死了。  

不仅需要修改为后端渲染，还需要修改H标签的层级关系。  

以 /search?query=unicorn 为例，H1和Title都可以是“160 Best Unicorn
Stickers”，其中“160”是搜索结果数量。

** 4.3、搜索结果页总结  **

搜索结果页很有用，但是要用好不容易，特别需要注重细节，像这个网站目前就做得不够好，从上面可以看到许多需要改进的地方。  

如果后面都改好了，那么这些可以生成无限多的页面会释放出巨大的潜力，会是首页之外最大的流量补充来源。

  

** 五、建议增加的新页面  **  

说完了已经存在的页面，哥飞说下建议增加的页面有哪些。  

**5.1、建议增加发现页面**  

这个其实我们在说首页时就提到了，需要有一个发现页面来列出所有的贴纸给搜索引擎爬虫去爬。  

而且这个页面还需要分页展示，因为贴纸太多了，不可能一个页面全部展示完。

又因为贴纸实在太多了，所以分页的链接建议有快进机制，即不能一直一页一页向下翻，而是不仅要列出当前页面的前后10个页面，同时还要列出下一级。  

如当前是第35页，那么需要列出以下页面链接：  
a) 第1页和最后一页；  
b) 第31到39页；  
c) 第50页、第100页、第200页……  

当然也还有其它方式来尽量让爬虫能够更快更轻松爬到完全部页面，如学习 Toolify.ai 的首页底部做法。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuLOoHfl6v8SutWFibFBbxaSxib7TgONlGKfvy74fcPncvIZsVia3VnvgfadC3ua4cexXt9k1brVIWjg/640?wx_fmt=png&from=appmsg)

**5.2、建议增加专题页面**

这个页面也是用来获取某些关键词的流量的，一个专题下面可以有多种不同的贴纸，但是  所  有  这些组合起来，就是一个完整的专题。

这个可以人工去选择，也可以用向量搜索来解决。  

**5.3、建议增加搜索结果列表页面**

上面也说过，  能  够通过
用户搜索获取大量真实需求关键词，那么这些关键词对应的搜索结果页面也是能够从搜索引擎获取流量的，所以我们需要有一个页面能够展示所有的搜索关键词，让爬虫有入口去爬去所有的搜索结果页面。

当然搜索关键词肯定会有很多，所以也是需要分页展示。  

为了好看，还可以给每一个搜索词匹配一个最佳结果贴纸作为配图。

好了，以上就是哥飞给AI贴纸生成网站StickerBaker的简略SEO评测报告和改进建议。  

因为是免费版，所以就没有写太详细，如果是付费点评，那么会更详细一些的。

大家对于自己的网站，也可以按照上面的方法去分析，自查，然后改进。  

很多时候，SEO拼的就是细节，谁愿意花更多时间去死磕细节，谁就有可能拿到更高的排名，获取更多的流量。

想要跟着一起做网站赚美元吗？  想要跟着哥飞学SEO  搞流量吗  ？

欢迎加入哥飞的付费社群“哥飞的朋友们”。  

  

社群目前暂时是微信群形态，有一个配套的网站，已上线第一版，社群内朋友可见。

  

社群主要面向技术开发者、产品经理、设计师等人群，大家一起讨论独立开发、出海产品、流量获取、流量变现等话题。

  

社群讨论的话题主要是围绕着网站来的，用网站来承接流量，然后变现。

  

那么就要考虑做什么网站，所以需要去挖掘需求。

  

然后去搞流量，可以是SEO，也可以是发帖宣传推广，还可以是付费软文。

  

有了流量之后就得考虑如何变现，可以是广告变现，也可以是联盟导购，更可以直接向用户收费。

  

社群目前超过1000人，新的一期开始了，这期哥飞将带着大家实战，每个月都会安排任务，推着大家前进，让大家能够赚钱。

  

目前社群价格999元一年。

  

社群按照365天计时，也就是你今天加入后，明年今日到期。

  

前两期讨论很活跃，行动很迅速，大家已经做了上百个产品了。

  

有的几人小团队已经用几个月时间从零开始做到了月收入4万美元以上，还有的单人实现了月收入几千美元。

  

这个社群7月2号开始运营的，到今天8个多月时间里，主要讨论了以下话题：

1、建站基础，如何快速做一个网站；

2、SEO基础，如何优化网站；

3、推广基础，如何宣传推广网站；

4、运营基础，如何运营好一个网站；

5、Adsense基础，如何靠谷歌Adsense赚广告费；

6、一些工具使用经验分享，如Semrush分析别的网站流量和出入站链接，Similarweb如何看流量；

7、基于Semrush、Similarweb等工具，如何去发掘新需求，发现新网站；

8、实战经验，如何去抓住新词热词做网站，从搜索引擎获取流量。

  

以上所有讨论都沉淀到了社群配套网站 web.cafe 上，所以第三期大家一进群就可以看到前两期的精华内容，以及其他更多相关话题。

  

欢迎加哥飞微信 qiayue 加入社群大家一起出海赚美元。

  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicv24nb20ZrM7niaIBxv5QynWqOtclGh4ApYjVM5exp1niaK9pOLIOswYu2jU0zczI2Hx2bdfAo1Fwow/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

预览时标签不可点

微信扫一扫  
关注该公众号





****



****



  收藏

