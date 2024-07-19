![cover_image](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicuR4pGHycZWB5cksAEll1LBO574g3Xv5yAv1pN9FscLZoVibiafDOaV0KRx8slRU03NJSs1Rc8Kezsg/0?wx_fmt=jpeg)

#  OpenAI DevDay 发布了好多好东西之开发者后台

原创  我是哥飞  [ 哥飞 ](javascript:void\(0\);)

__ _ _ _ _

大家好，我是哥飞。  

OpenAI 开发者春晚结束了，大家看完视频后，记得看开发者后台，更新了好多东西，甚至开发者后台界面改版了。  

** 1、布局导航改版  **

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LB4Pn5Ekm6xiaKmUpr4gAGaY7weqEpUq6ch5hUxb32uoYw7Mdp3FicLyTQ/640?wx_fmt=png)

更改了界面布局，尤其是导航，更方便地查找更多信息了。  

之前的开发者后台各种页面是陆陆续续完成的，散乱在各个地方，很割裂，今天发布的新版统一了导航，可以在一个界面内打开各个页面了。

** 2、一级导航  **  

开发者后台左侧导航属于一级导航，如下图所示，可以快速访问开发平台首页、Playground 测试场、Assistants 助手、Threads
会话、Fine-tuning 微调、API Keys 密钥、Files 文件、Usage 用量、Settings 账号设置等。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBhia8eHl9jM3IdRNiayIkvTcGIw89KXn6IQAMZQqJWnoXffglQCF7HibYA/640?wx_fmt=png)

** 3、开发平台首页  **

点击OpenAI的黑色  图标是开发平台首页，  在顶部导航  可以快速地  切换  文档  、API、  开发使用  示例、  开发者论坛和帮助。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBUJbrtg1ibPRTyGZCHXqSRLy1ebdqzCoa8tUia2Qiaib5zCqCENQDQtHK0g/640?wx_fmt=png)

作为开发者，我们最常用的就是文档和API了。  

** 4、Playground 测试场  **  

Pl  aygr  ound 没有通用的中文翻译，如果简单翻译为游乐场不好理解，所以哥飞更倾向于翻译为  测试场，一听就知道干嘛的。

Pl  aygr  ound 中  支持测试Assistant 助手、Chat 问答、Complete 续写、Edit 编辑。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LB8mQBaDYWsCXqH2BBPe0Ba8Iejics4eZDrQch8Rp3RpKnuRFLLFFAgNA/640?wx_fmt=png)

其中 Assistant 助手，哥飞给大家演示一下，可以告别 ChatPDF 了。

我创建了一个助手，并且上传了一个Markdown文档，是《 [ 科技爱好者周刊#276：内容行业的衰落
](http://mp.weixin.qq.com/s?__biz=MzI4NjAxNjY4Nw==&mid=2650235241&idx=1&sn=2683e5cf3d45b2517deabef7837ac686&chksm=f3e094a9c4971dbf9731ca79ce8b859527d635e9ac3c38b091c97c6692310c8f586298a840ac&scene=21#wechat_redirect)
》的Markdown格式，之后就可以基于文档进行问答对话了。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBvypt3ZWIFbaia3q8Zj9eAiaubQttYicTgsJ63yxdqcZ02XmIq0D0xyjsA/640?wx_fmt=png)

其它几个测试都很常规，哥飞就不给大家演示了。  

** 5、Assistants 助手管理  **

对于助手，哥飞想隆重向大家推荐。

这次 OpenAI DevDay 更新的这么多接口中，  对于开发者来说，最好用的是 assistant 助手 API。

简单来说，我们把最大512M的 pdf 、markdown 文件上传到 OpenAI 得到文件id，之后在问答接口中直接指定文件id，OpenAI
会自动从文件中查找所需的知识来回答问题。

也就是说，不需要开发者自己做向量化，也不需要开发者自己检索之后把内容片段放到问答接口中了，OpenAI 自动帮我们做好了。

所以 ChatPDF 类产品没有被杀死，反而更容易做了。

之前提前泄漏出来的消息说，调用成本会降低20倍，其实指的就是这个东西，我们不需要每次在问答中把文档内容片段反复提交，只需要先上传文件得到文件ID，之后就可以直接基于文件进行问答。  

在 A  ss  istants 助手管理中，可以查看我们创建过的所有助手，也可以创建新助手。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBmMWM3AYRFvbgCHTv4e9vUmjbk2Mm4GD0ENUyAbhqr94I28ibaPDWonA/640?wx_fmt=png)

对于每一个创建好的助手，还可以修改助手信息，或者克隆复制助手，还可以一键直达在测试场中使用这个助手。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LB1lBEwJRL0RAnbvibWzABHSJWhIuVjyoRD2Jo0NUMM5MAqHomWPYzHpw/640?wx_fmt=png)

** 6、Threads 会话管理  **  

对于我们程序员来说，thread 很多时候会翻译为线程，但是在OpenAI 的助手这个语境下，其实翻译为会话更合适，几乎  可以等同于
ChatGPT中的会话。

在 Threads 中可以管理会话，查看会话列表。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LB8LdibFCTx4T5HBksXYn2DtGdUETzyWJqWI0cxykQRRjgjnR14vwLWNw/640?wx_fmt=png)

点击每一个会话，还可以查看会话详情，会话中每一条发言都能够看到。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBIV3FLztzptYvkpytlXGklibXZI4aFsmZjR3fXABNQq1zup9XSjPu89A/640?wx_fmt=png)

** 7、Fine-tuning 微调管理  **  

在这里可以查看我们所有的微调，查看每一个微调的进度，还可以创建新的微调。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBrHo6XLkTsn4ibMYzrYcHU3ZOdsRX9Ef1DmTPHWfdnl4DqibEAQibSzICA/640?wx_fmt=png)

** 8、API Keys 密钥管理  **  

密钥管理页面不用过多介绍，还是之前的页面。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LB8pY0iculJsXhyjFZiaUboenORRB5CRSHfiav4oWVpzqtJ7l1jAJO1ibJibA/640?wx_fmt=png)

** 9、Files 文件管理  **

文件管理中列出来了我们上传的所有文件，支持按照上传日期和文件名排序，且都支持按照升序和降序两种方式排序。  还可以  上传新文件。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBgVQdU18lWIsREz3uQ2K0LcZugItdqibFjbbk2dwzoZWG0QlcjNZcfUA/640?wx_fmt=png)

点击文件名，可以进入文件详情页面，可以查看文件ID，这个文件ID可以在助手中使用。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBkofm0P963Islpopibwuib3xACMMmpNAxUcPP82OmzszVeDJibxPdFX6pw/640?wx_fmt=png)

** 10、Usage 用量管理  **

使用量管理页面也改版了，改成图表形式更直观地显示使用量，可以看到按月、按日、按模型的消耗汇总数据图表。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LB9DPGyzYQ6lJa8hx3Tk7kSEMSHt5ClUHkVQ0uK3hvsr4TicCh00R1Eqw/640?wx_fmt=png)

** 11、Settings 账号信息设置  **

这里可以查看组织ID，管理团队，查看接口调用限制，查看账单，设置个人信息等。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicuR4pGHycZWB5cksAEll1LBAV2AOAsC3hic5JsYWs41pykE6MwLDAnFibAufmt63UyGa9W5TiaBDLzpw/640?wx_fmt=png)

每一个都是之前已经有的页面，哥飞就不做过多介绍了。

接口能力方面，OpenAI
发布了一些新模型，增加了一些新能力，大家可以直接看开发文档，很多细节，本文只介绍开发者后台界面，接口方面暂时不做介绍，欢迎关注哥飞公众号，我们后面会介绍接口能力方面的各种细节和用途用法。  

哥飞运营的付费社群，已经有五百多人加入了，哥飞总结了一套快速从搜索引擎获取流量的方法，大家基于这个方法去开发网站，基本上线第一周就能够从谷歌获取流量，最快的甚至上线第二天就有流量。

如下图就是一个上线五天的网站，在第5天就达到了3000多UV，12000多PV的成绩，而且流量全部来自于谷歌。

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicuR4pGHycZWB5cksAEll1LBlHwUytqYtduMaQNtic1zWKbibicI0I5tr35LxibicNBuGpzyuODuuXeBzlw/640?wx_fmt=jpeg)

还有个网站上线几天，就被谷歌送了流量大礼包，短时间内来了大量流量，同时在线1005个访客。

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicuR4pGHycZWB5cksAEll1LBcqlQaSDuFia9Fy4Jsz06oZx5jlF4ZRZUCV9y94mcn2vtBmqZ2rmTJbw/640?wx_fmt=jpeg)

想知道哥飞总结的方法是什么吗？

欢迎加入哥飞的付费社群，哥飞为你详细讲解。

如果感兴趣，请加哥飞微信 qiayue 咨询了解。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicsG8Pro6O9Hu75bIIiafZVPs3qlYeaNNJ1BpqNplEGgibL5m1bcq8a1N1rzoI5lia8aJjtHfgiaAADJJQ/640?wx_fmt=png)

预览时标签不可点

微信扫一扫  
关注该公众号





****



****



  收藏

