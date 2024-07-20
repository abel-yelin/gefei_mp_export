![cover_image](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJUgEsBEWenphElJ8PdbtyqI6TJ5SjjKE6UQ17CTMNHzPZN4iaTQxHZHA/0?wx_fmt=jpeg)

#  Semrush 和 Similarweb 是如何知道每个网站的流量数据的？

原创  我是哥飞  [ 哥飞 ](javascript:void\(0\);)

__ _ _ _ _

大家好，我是哥飞。  

经常有朋友问，Semrush 和 Similarweb 是如何知道每个网站的流量数据的？

今天哥飞就跟大家聊聊这个问题，说的都是哥飞个人的理解，不一定全对哈。

首先这两家肯定都会有海量的爬虫，去收集整个互联网上的每一个网站的信息。  

通过分析爬取到的 html 源码，就能够知道各个网站之间的链接关系。  

然后也会去爬各个搜索引擎如谷歌的各个关键词的搜索结果，知道每一个关键词的每一个搜索结果是哪些网站的哪些网页。  

再去跟一些网站或者数据方合作，得到一些真实的数据。  

最后把这些所有的数据整合起来，建立一个流量模型，就够知道每一个网站的流量了。  

原理是什么呢？

在已知每个关键词的搜索总量和每个搜索结果位置能够拿到的流量占比的情况下，就能知道这些网站从每一个关键词拿到的流量。

再把每个网站的所有关键词拿到的流量加起来，就知道了每个网站的能拿到的总搜索流量。

那么怎么知道每个关键词的搜索总量呢？  

可以有多种办法，假设知道了A关键词的排名第一的网站的从A关键词拿到的准确流量，是不是就可以反推A关键词的搜索总量。  

反过来，当已经知道B关键词的搜索总量情况下，也知道排名第一的网站从B关键词拿到的准确流量，是不是就可以算出排名第一能够拿到的流量占比。  

从各种途径去获取各种数据，最后建立一个模型，把已知的数据填进去，就能够推算未知的数据，而且已知的数据之间还可以互相印证，找出有问题的数据。  

不管是 Semrush 还是 Similarweb
，他们的方式都差不多，建立一个大模型，模拟每天各个网站之间的流量流动情况，再与真实数据印证，调整模型参数和各种因子，最终得到每个网站的流量数据。

我们拿个例子看看就知道了。  

最近 iPhone 15 上市了，我们就拿这个词来说。

我们先在谷歌上搜索“  iPhone 15  ”，可以看到结果如下，排第1的肯定得是苹果的官方网页。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJuNvaWbC8vAA5aBMicq0F0wZ721jB6gFfBNUWzibNSJJKlGMd6ERibV5fg/640?wx_fmt=png)

再在 Semrush 搜索一下，可以看到美国的搜索量是673K。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJNsPbsiccTcenicYca4icOjGv3zVUwpxicXjNxXR2AIribicicufkMcaLf10HQ/640?wx_fmt=png)

拉到下面的“SERP”模块，可以看到排名第一的也是苹果的这个官方页面。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJUy4KncAqnXfDCV0cMKC8r1G2cQ8NYhKkhfYdH5WyqdpGb9dlHBwTCQ/640?wx_fmt=png)

我们点击哥飞红色框出的位置，打开 Semrush 的新页面。  

可以看到，“iPhone 15”这个关键词，在第1位置，能够拿到的点击流量是80%。

记住这个数字，也就是说，一个词只要排到了第一名，  大多数情况  下  ，都是能够吃到搜索总量的80%的流量的。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJqE94eAwln8ibZFQzJCpP73tcibbOgDN0Xs0ms1ESQaolBsA4yyV7y43Q/640?wx_fmt=png)

为什么说是大多数情况下呢？

我们  拿  “  Ch  atGPT  ”  这个词来看看就知道了，谷歌搜索结果如下。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJVMsU3aWNwNupz1F8Rlax45V1tdGymAG00nYLT17TMUmHlkHUKnkmBw/640?wx_fmt=png)

再看 Semrush 的结果，前两个结果跟谷歌搜索结果是一样的。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJT7GGUia6XGWBsm7oAoRriboXdfBe8mTSlat0THyFw6T2Vd317wia9xnlw/640?wx_fmt=png)

分别点击两个红框，打开看数据，你看，排名第1的拿到了55%的点击，而排名第2的拿到了35.5%点击。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJ19RhiaKoia9niaLVibia7CE7I4GkSt4OcTR0uREgShgrfDn8FmheWa5qLhw/640?wx_fmt=png)

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuAVVlkmCeGjeOj4FWlhrBJ9CXyYiasRZjYsVxbrLgmCCfczCuHpASicZpOQ8ibZkbCicdaiac16cljStA/640?wx_fmt=png)

至于为什么排名到了第1，也只拿到55%的点击，哥飞也不知道真实原因，  今天这篇文章，我们暂不深究这个问题。

总结一下，Semrush 和 Similarweb 的流量数据都是用模型运算推测出来的。这个特别复杂的模型还结合了真实数据来校验修正算法。

大家都知道，哥飞运营了一个付费社群，名叫“哥飞的朋友们”，社群从7月2日开始运营，到现在已经有347位朋友加入社群了。  

为什么会有这么多朋友愿意加入这个价格为666元/365天的付费社群呢？

因为值得，给大家看张截图就知道哥飞所说不虚，  感谢这位老板邀请了公司里4位同事，总共5位朋友在哥飞的社群里  。哥飞继续努力输出，保证让所有朋友都有收获。

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeictib15GAhhBkjVhSVEiaXNVwg4nZGX2AGchQ2iaVaiaUmkeY0ibhibk9179aPd4lIwv3346zh9tLhFcjhFA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1)

想知道怎么值吗，欢迎加哥飞微信 qiayue ，入群你就知道了。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicsG8Pro6O9Hu75bIIiafZVPs3qlYeaNNJ1BpqNplEGgibL5m1bcq8a1N1rzoI5lia8aJjtHfgiaAADJJQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

预览时标签不可点

微信扫一扫  
关注该公众号





****



****



  收藏

