![cover_image](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicvvynJa2lDsT2DtwHs2lzCVJBUm2EsIBBqnyhbzq0atufcMUL6fOEMxKgquyXPGMvSB4Ygicic8QTsA/0?wx_fmt=jpeg)

#  哥飞：SEO友好的AI原生CMS思考和实践 Part 2

原创  我是哥飞  [ 哥飞 ](javascript:void\(0\);)

__ _ _ _ _

大家好，我是哥飞。

关于哥飞介绍可以看这里：  [ 哥飞是谁，哥飞在做什么事情，在哥飞公众号大家可以看到什么内容
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082843&idx=1&sn=50add036fed1ac78f2c71887bbedb990&chksm=bf3f3f208848b63647147b8c3328bfe12497d281c9c4257d548e83b095b6db33d29e2f6d03e6&scene=21#wechat_redirect)  
关于哥飞社群可以看这里：  [ 是时候给大家好好介绍一下哥飞的社群了，毕竟刚被二十年站长大佬夸过
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082450&idx=1&sn=b33f52d905edd76782d85eb06163f312&chksm=bf3f3da98848b4bf8214219c775293b397bdda48f14975f88e55a5bbe7efa75e4b11d93010a5&scene=21#wechat_redirect)

上周三，哥飞做了一场150分钟的直播，从这里可以打开《 [ 一不小心，哥飞花了70天做了一个DR62的新网站
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650083208&idx=1&sn=c39751fb08d928dcbcb9a41c2538f32b&chksm=bf3f3eb38848b7a5b241fefd72e564ec8fb8ba46befd14379b6f5e95e764f3a6ab038a7364e4&scene=21#wechat_redirect)
》。

有位朋友用他做的视频笔记工具“ReadLecture”把直播回放视频转录成了图文并茂的文章。  

哥飞申请复制过来在哥飞公众号备份一份，由于内容太多，这是第二部分。

##  大纲

  * **AI工具来源与收集**

    * 来源平台：Product Hunt，Hacker News，其他AI导航站点 
    * 收集方法：开发爬虫进行工具抓取和去重处理 
    * 技术栈：Next.js后端，Vercel部署，自建数据库 
  * **页面内容管理**

    * 自动化发现待收录页面 
    * 页面信息：Page Name，Page Description，外部链接，当前状态 
    * 技术选择：PGP，MySQL，PostgreSQL，Supabase，Cloudflare 
  * **AI原生特性**

    * 数据来源自动化 
    * 自动化分类处理 
    * 初期使用免费资源，后期考虑高级解决方案 
  * **参考资料表**

    * 存储内容：配对的具体参考资料 
    * 语言处理：多语言混合存储 
    * 作用：增加权威性，防止AI产生幻觉 
  * **AI产品收录与展示**

    * 收录新AI产品 
    * 参考资料来源：产品官网，科技媒体，官方博客等 
    * 自动化处理：爬虫获取信息，GPT格式化处理 
  * **工作流程**

    * 从手工到半自动再到全自动 
    * 上线简单版本，逐步完善功能 
  * **标签系统**

    * 标签生成：基于搜索量的关键词 
    * 标签用途：提升搜索引擎排名 
    * 多语言支持：不同语言的提示词生成内容 
  * **变现逻辑**

    * 广告收入 
    * PR发布 
    * 广告位租赁 
  * **技术细节**

    * 静态页面生成 
    * 缓存策略 
    * 数据库压力减轻 
  * **竞争与优化**

    * 站内SEO 
    * 网站权重提升 
    * 多页面协同优化关键词 
  * **结束语**

    * 服务端渲染 
    * 关注公众号和视频号 

##  内容总结

###  一句话总结

文章详细介绍了如何通过自动化工具和策略收集、管理AI工具信息，并通过优化内容和标签系统提升网站的搜索引擎排名和变现能力。

###  观点与结论

  * 使用爬虫自动化收集和去重AI工具信息，提高效率。 
  * 通过精心设计的提示词和多角度的内容介绍，有效提升AI产品的展示效果和搜索引擎排名。 
  * 利用多语言提示词生成不同语言的内容，提升多语言支持能力。 
  * 通过广告和PR发布等方式实现网站变现。 
  * 采用静态页面生成和缓存策略优化网站性能。 

###  自问自答

  1. **问：文章中提到的AI工具主要从哪些平台收集？**

     * 答：主要从Product Hunt、Hacker News和其他AI导航站点收集。 
  2. **问：文章中提到的数据库是如何处理的？**

     * 答：数据库是自建的，因为直接使用Vercel或Supabase的数据库成本太高。 
  3. **问：文章中提到的参考资料表有什么作用？**

     * 答：参考资料表用于存储配对的具体参考资料，增加权威性，防止AI产生幻觉。 
  4. **问：文章中提到的标签系统是如何生成的？**

     * 答：标签系统基于搜索量的关键词生成，用于提升搜索引擎排名。 
  5. **问：文章中提到的变现逻辑有哪些？**

     * 答：变现逻辑包括广告收入、PR发布和广告位租赁。 
  6. **问：文章中提到的静态页面生成是如何实现的？**

     * 答：静态页面生成是通过实时生成的静态页面技术实现的，并非预先生成HTML文件。 
  7. **问：文章中提到的竞争与优化策略有哪些？**

     * 答：竞争与优化策略包括站内SEO、网站权重提升和多页面协同优化关键词。 

###  关键词标签

  * AI工具 
  * 爬虫 
  * 数据库 
  * 参考资料 
  * 标签系统 
  * 变现逻辑 
  * 静态页面 
  * SEO优化 

###  适合阅读人群

  * AI工具开发者 
  * 网站运营者 
  * SEO优化专家 
  * 数据分析师 

###  术语解释

  * **Product Hunt** : 一个发现和分享新产品的社区平台。 
  * **Hacker News** : 一个关于计算机黑客和创业的新闻网站。 
  * **Next.js** : 一个用于构建服务器渲染的React应用程序的框架。 
  * **Vercel** : 一个用于部署和托管前端应用的平台。 
  * **PostgreSQL** : 一个强大的开源关系型数据库系统。 
  * **Supabase** : 一个开源的Firebase替代品，提供数据库和身份验证等服务。 
  * **Cloudflare** : 一个提供CDN、DNS、DDoS保护和安全服务的公司。 
  * **GPT** : 一种基于Transformer架构的预训练语言模型。 
  * **SEO** : 搜索引擎优化，通过优化网站内容和结构提升在搜索引擎中的排名。 
  * **CDN** : 内容分发网络，通过将内容分发到全球多个服务器来提高访问速度和可靠性。 

##  联系讲者

  
** 原直播视频见视频号  ** ：  **哥飞出海**

##  讲座回顾

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadjIg5E1oaH83AHDyWDOM0xNcuwDp7BHdxGhfDc8edwU9nhJgZQkvtRA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **AI工具来源** ：主要关注Product Hunt和Hacker News等平台，以及AI导航站点。 
  * **技术实现** ：使用爬虫抓取AI工具，进行去重处理。 
  * **技术栈** ：后端使用Next.js，部署在Vercel上，数据库自建以降低成本。 
  * **自动化处理** ：通过爬虫自动化发现待收录页面，进行分类处理。 
  * **成本考虑** ：初期使用免费资源，流量增加后再考虑高级解决方案。 

> 我之前提到过，大家经常问我内容是从哪里来的。目前，我主要关注的是AI工具。我们思考过，哪里可以找到这些AI工具？例如，Product
> Hunt每天都会推出许多新的AI工具，Hacker
> News也是如此。此外，其他AI导航站点每天也会发布许多新的AI工具。为此，我们开发了一个爬虫来抓取这些工具，并进行了一些去重处理。
>
> 举例来说，这个截图显示来源是Product
> Hunt。我的后端使用Next.js，部署在Vercel上。目前，整个服务都部署在Vercel上，不需要使用自己的服务器。不过，我的数据库是自建的，因为直接使用Vercel或Supabase的数据库成本太高。我的数据库目前是自建的。如果你直接使用Vercel，可以享受到免费的服务器服务。使用Next.js可以同时处理前后端。
>
> 回到我们的页面，所有待收录的PH页面都是通过爬虫自动化发现的。我可能会从多个来源发现这些页面，并列出它们的Page Name、Page
> Description、对应的外部链接以及当前状态。选择你目前熟悉的技术，没有必要一定要学习新知识。选择你最熟悉的技术可以快速上线网站，选择成本较低的方案也是可以的。
>
>
> 例如，如果你想使用Vercel，数据库可以选择MySQL、PostgreSQL等。我目前使用的是PostgreSQL。如果你选择其他服务，如Supabase或Cloudflare，它们也提供数据库服务，选择很多。
>
>
> 这就是我所说的AI原生体现在哪里，体现在我的数据来源是自动化的，并且进行了一些自动化的分类处理。一开始，你可以使用免费的资源，不必考虑太多。等到流量增加后再考虑更高级的解决方案。一开始不需要考虑大流量的问题，先确保能够处理100%的流量。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadQh3u5BCgpEpePrIazoG0v8AhYt7ElPNg1moyibyASG20vKIKMseibW7A/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

关于流量的问题，其次，我们刚才讨论过的内容中，我提到了一个参考资料，这一点之前已经提及过。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3Xiadadnxnzrj6yOqRNJkDTYMFicqtCvSmFicKXT3CO2x5OuUHppicu25NIibdw/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **表的名称与功能** ：存在一张名为“reference content”的数据库表，用于存储特定配对的具体参考资料。 
  * **资料存储形式** ：这些参考资料以文本形式存储，支持多语言混合。 
  * **GPT的能力** ：GPT能够处理和存储包括英文、中文在内的多种语言的参考资料。 
  * **表的必要性** ：提供参考资料以增加权威性，防止AI产生幻觉或生成不准确的内容。 
  * **新AI产品的处理** ：对于GPT训练数据库中不存在的新AI产品，确保参考资料的真实性，避免AI生成内容。 

> 我先回到刚才提到的数据库表。我有一张名为“reference
> content”的表。这张表存储的内容是某个配对的具体参考资料。目前，这些参考资料以文本形式存储，并且不区分语言，即使是多语言混合也没有问题。得益于GPT的强大能力，我可以存储英文、中文甚至其他语言的参考资料。这就是“reference
> content”表的作用，它存储的是参考资料。
>
>
> 为什么需要这张参考资料表呢？大家可以思考一下，为什么需要？有没有人能在评论区回答一下？增加权威性是正确的，相当于提供参考资料，防止AI产生幻觉也是正确的。因为我们知道，如果让GPT凭空生成内容，很可能会产生幻觉或胡说八道。因此，为了解决这个问题，我们需要提供参考资料，严格让GPT基于这些资料生成内容，确保AI不会乱说话。
>
>
> 还有一个要点是，我们每天收录的是新的AI产品，这些产品根本不在GPT的训练数据库中，它根本不知道这些产品是什么。你问了一个很好的问题，参考资料是怎么来的？为了确保资料的真实性，而不是AI生成的，我在这里做了一些处理。现在，让我们回到刚才的那个页面。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadgcHicPKrUCMVhnibU5dFDref5CMuWMQb3e1D641mV8NXnZMeY4t8icAMw/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **信息来源** ：产品官网、海外科技媒体、官方博客、About页面等。 
  * **信息获取方式** ：通过爬虫技术获取，由GPT进行格式化处理。 
  * **工作流程** ：从手工整理逐步过渡到半自动和全自动。 
  * **当前状态** ：后台尚未完全自动化，仍需手工调试和完善代码。 
  * **内容用途** ：参考资料不公开，仅用于GPT的内部参考。 
  * **AI依赖程度** ：爬虫操作基于人工编写的规则，AI尚未完全独立执行。 

>
> 对，你说的很对，我的内容是通过爬虫获取的。这里给了一个示例，我截图展示了Hedra这个产品，参考资料大致展示了其官网的内容。格式并不重要，我直接将产品名称、官网网址、Title等按照特定风格排列，并换行插入其介绍和从网页上抓取的社交媒体链接等。这就是参考资料，只要是与产品相关的信息都可以纳入。
>
> 获取这些信息的渠道包括产品官网、海外科技媒体如Tiger
> Client，以及官方博客、About页面、团队介绍页面、公司介绍页面、产品介绍页面、Features页面、How It
> Works页面和FAQ页面等。所有这些信息都可以通过爬虫获取，并由GPT进行简单的格式化处理，作为参考资料。
>
>
> 最初，我是手工整理这些资料的，因为尚未确定合适的参考资料格式。当我手工整理到一定程度，明确了所需的参考资料格式后，我编写代码让GPT进行格式化处理。注意，这是格式化处理，而非生成，是基于爬取的数据进行的。
>
>
> 我的整个工作流程是从纯手工逐步过渡到半自动再到全自动的过程。目前后台尚未完全实现全自动，仍有许多手工参与的环节，因为我还需要进一步调试和完善代码。这也是我上线网站的风格，我先上线一个简单可用的版本，逐步完善功能。
>
>
> 关于后续迭代是否会导致谷歌认为结构变化而降低流量，答案是不会的。因为我的参考资料本身不会公开，这部分内容仅用于GPT的参考。爬虫并非完全由AI自动执行，而是基于我编写的规则。目前，AI尚未强大到可以完全依赖，仍需人工介入。
>
> 为每个Page都制作了参考资料后，

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadqFbgw6HJDibNDDyrpJrk1wziaVsQLNKJv4vkmry9ichicqdTUXAtXRrxkw/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **提示词的作用** ：确保AI产品介绍的准确性和相关性，指导自动化减少重复劳动。 
  * **提示词的调整** ：持续进行，不同语言需要分别编写提示词。 
  * **内容生成策略** ：结合参考资料和产品名称，针对不同部分（如简介、常见问题、使用教程）使用专门的提示词。 
  * **内容丰富性** ：关注文本内容的同时，考虑图文并茂和增量信息，如使用截图和GPT-4的图片识别能力生成详细教程。 
  * **效果提升** ：通过精心设计的提示词和多角度内容介绍，提升AI产品的展示效果和搜索引擎排名。 

>
> 在介绍AI产品时，每个部分都配备了特定的提示词，以确保内容的准确性和相关性。这些提示词不仅帮助生成产品介绍，还用于指导如何通过自动化减少重复性劳动。例如，使用GPT模型逐步替代人工操作，探索更多自动化可能性。
>
>
> 提示词的调整是一个持续的过程，不同语言的提示词需要分别编写，以确保生成内容的准确性。例如，使用中文编写的提示词可能不适用于生成英文内容，因此需要为每种语言定制提示词。
>
>
> 此外，每个部分都有专门的提示词，这些提示词结合参考资料和产品名称生成内容。例如，为了提升单页面的搜索引擎排名，需要从不同角度介绍产品，如简介、常见问题、使用教程等，每个部分都有针对性的提示词。
>
>
> 在生成内容时，不仅要关注文本内容，还要考虑图文并茂和增量信息。例如，通过实际使用产品并截取使用截图，利用GPT-4的图片识别能力生成详细的使用教程，这些都是增加页面信息量的方法。
>
> 总之，通过精心设计的提示词和多角度的内容介绍，可以有效提升AI产品的展示效果和搜索引擎排名。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadKH9Q0fCSFBRGIkhmM1pVYxYDrQhJSdRpHlRmyk5C2CQLqlWzicg0MIQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **多语言内容生成** ：每个内容支持多语言特性，通过不同语言的提示词基于相同参考资料生成不同语言的内容。 
  * **生成过程** ：不是先生成一个语言的内容再翻译，而是直接使用不同语言的提示词进行多次生成。 
  * **成本与收益** ：虽然生成多语言内容的成本较高，但每个页面能带来大量点击，最终转化为收益，成本相对较低。 
  * **Tag管理** ：Tag是动态可维护的，有单独的表格管理。 
  * **具体案例** ：以PNG Maker产品为例，用英文、德语和荷兰语生成了特定的标题和配置。 

>
> 我们继续讨论下一个话题，即每个内容天然支持多语言的特性。这意味着什么呢？刚才我们提到，为每个页面抓取参考资料后，例如，我现在需要生成introduction部分，我可能会先以英文生成，然后再生成中文，以此类推。因为我对introduction部分有十种不同语言的提示词，我会让这十个不同的提示词基于相同的参考资料生成十个不同的内容。这里需要注意的是，我并不是先生成一个内容，然后让GPT进行翻译，而是直接使用不同语言的提示词，基于相同的参考资料生成不同语言的介绍。我进行了十次生成，而不是简单的翻译，这样的效果更佳。虽然费用不低，但相对于你能节省的费用，这是值得的，而且每个页面都能带来数百甚至数千的点击，这些点击最终能转化为收益，因此成本并不高。Tag是动态可维护的，有单独的表格，稍后我会详细介绍。例如，PNG
> Maker这个产品，我用英文生成了特定的标题和配置，同样也用德语和荷兰语进行了生成。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadaicczWvGFfEvqGb7TyokVXCd5mNo5Dicaqa0nkkMiamOTibwo19gXYbicRQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **标签生成原则** ：标签应基于有搜索量的关键词，旨在吸引搜索引擎流量。 
  * **标签生成过程** ：目前依赖手工操作，未来目标是自动化或半自动化。 
  * **关键词搜索量验证** ：通过查看高流量页面或使用谷歌趋势验证。 
  * **标签表构建** ：包括多语言标签，需找到每个标签在不同语言中的正确表达。 
  * **标签应用** ：通过GPT从标签列表中选择最合适的标签，确保标签的搜索量。 
  * **技术细节** ：数据缓存处理减轻数据库压力，网站打开速度优化通过静态化处理实现。 

>
> 在本次讲座中，我们将探讨如何自动提取有搜索量的关键词并将其作为标签。目前，这一步骤尚未完全自动化。有人可能会问，这些标签是如何生成的。需要注意的是，我们不能直接让GPT自动生成标签。我们的原则是，内容应旨在从搜索引擎获取流量。因此，我们必须寻找那些具有搜索量的关键词来作为标签。例如，我们之前提到的标签分类，如text
> to speech、speech to text、image to
> video等，这些标签目前仅要求有搜索量，而不追求其价值。我们将所有与AI产品相关的特性词抓取并清洗，然后存入数据库，形成一个多语言的标签表。这个标签表不仅包括简单的翻译，还需要找到每个标签在不同语言中的正确表达。
>
>
> 如何找到有搜索量的关键词？这需要我们回顾之前的挖掘需求方法，比如查看其他网站的高流量页面或高流量关键词。关于Claud3.5是否比GPT-4o效果更好，我没有进行过测试，因为我一直使用的是GPT-4o。此外，数据缓存处理是必要的，以减轻数据库压力，这需要多级缓存策略。
>
>
> 关于广告内容是否会与标签冲突，答案是不会。对于难以理解的语言标签，我们可以使用GPT或谷歌翻译进行初步处理，然后通过谷歌趋势验证其搜索量。缓存策略将在下次课程中详细讲解。目前，关键词标签的提取主要依赖手工操作，我希望未来能实现自动化或半自动化。这一过程的初始手工操作有助于形成标准操作流程（SOP），后续可以逐步实现自动化。
>
>
> 第六点涉及自动为页面打上合适的标签。虽然目前这一步骤是手动进行的，但我之前在测试GPT的插件商店时，已经验证了自动打标签的可行性。具体操作是，将所有标签和产品介绍传入GPT，让其从标签列表中选择最合适的标签，而不是自动生成标签。这一步骤非常关键，因为它确保了标签的搜索量。此外，网站的打开速度优化是通过静态化处理实现的。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadcSn498TeTqKkIHzQLBjcRO4cYmp5KfnMAwCWp88rvUibjDNXdqg7rtw/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

接下来，我们将进入重点部分。之前虽然讨论了许多内容，但尚未详细说明标签的具体用途。现在，我们将探讨如何利用标签生成多种不同的页面。在此，我暂时不展示具体内容，而是转向其他方面。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadGGrMEc3iaIExgpQ9DD82TqaBJVspDUJcUicuRuC9WKDqTibic0ud1w8o7A/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

直接看首页。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3Xiad1T2fv0YhT3vBjibnEGQGVddZaTmKZ0tZX2gIIhl5nzZ7Ba2VxaibolEg/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

例如，Awesome AI是一个AI工具，我们为其添加了“AI Tools
Directory”标签，表明这是一个AI导航站点。该导航站点收录了众多标签，提供了丰富的选项。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadzFlaYZXpv0a8GnTibNrX2GwypScTicVRoEwYek48WcibdruAP45jpaibJA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * 创建了一个以“t”开头的页面，用于展示特定标签的网站产品。 
  * 每个“t”页面有独特的URL、内容、标题和描述。 
  * 遵循“一个关键词一个页面”的原则，认为该标签关键词有搜索量。 
  * 页面目前仅罗列产品，未进行分类，未来可能增加细分分类和更多信息。 

>
> 那么多的产品，我这里专门会有一个页面，以“t”开头的页面。注意，刚才给大家演示的都是以“p”开头的页面，现在终于到了一个新的页面，以“t”开头的页面。这个“t”开头的页面是用来做什么的呢？我会给每一个“t”页面分配一个独特的“t”页面URL，例如这里的“AI
> Tools
> Directory”，它有自己的“t”页面内容、“t”页面标题和“t”页面描述等。也就是说，最终会生成一个“t”页面，在这个“t”页面下列出所有打了这个“t”标签的网站产品。这是为了遵循我们之前提到的“一个关键词一个页面”的原则，因为我认为这个标签对应的关键词有搜索量，所以我就制作了这样一个页面。
>
> 制作这个页面的另一个原则是分门别类地罗列。目前，这个页面暂时只做到了罗列，还没有做到分门别类。也就是说，它暂时只罗列出了“AI Tools
> Directory”下的所有AI产品，但没有进行分类。未来可能可以进行更细分的分类，例如，对于AI行业来说，大家更关心的是产品是否免费、付费，以及网站的流量等级等信息。更多的其他增量信息也可以加入进去。我换一个可能更合适的例子来说明。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiaduaQLSicfIyMlCKttn9t2D1AHJh0v6Ylq6mudek42gCvwQWvmQwq2q1g/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **文字生成图片功能** ：涛涛开发，页面加载快，收录多种产品但未分类，计划未来细分。 
  * **标签系统** ：基于SD模式，支持子标签如text to logo等，页面非最终版本。 
  * **变现逻辑** ：不依赖外链收费，通过广告位、内容发布等方式实现。 
  * **全自动镜像站群** ：AI生成内容难以带来流量，依赖GPT匹配标签。 
  * **Tag页面** ：静态化，未做分类，使用标签系统替代分类。 

> 比如说这个text to
> image，即文字生成图片，大家看到这个页面打开还是挺快的。这个是涛涛做的一个处理。在文字生成图片这个标签下，我收录了一些产品，但这些产品暂时没有分门别类。后面我们可能会做一些分门别类的处理。它是基于SD模式开源的模式，还是基于其他的一些更细分的产品功能，比如生成logo。这里举了一个很好的例子，因为AI生成logo也是text
> to image，所以同一个产品可以打上不同的标签，也就是有子标签。在text to image下，可能会有更细分的标签，如text to
> logo、text to headshot（头像）、text to sticker（贴纸）、text to png
> image等，这些不同的分类最终都会在这个页面体现出来。也就是说，目前的标签页面还不是最终页面，只是先放出来了一个页面。
>
>
> 关于变现逻辑，并不是通过外链收费。变现逻辑是当你的产品流量有了之后，你可以做很多事情。举例来说，别人有一个AI公司，他新拿到了投资，要做PR，可以在我们这里打广告，收取一些费用。还有，他想写一篇软文，也可以在我们这里发布。此外，我们网站上开辟一些广告位，如果你想在你的网站在我们的广告位里显示一周或一个月，我们会收取相应的费用。这些都是变现方式。
>
>
> 关于全自动镜像站群利用AI伪原创能带来流量的问题，这里还是不太可能能够带来流量的。因为AI生成内容，尤其是伪原创之类的，意味着没有独特的信息。将哪部分内容让GPT匹配标签呢？把你的生成的介绍部分，还有它的一些key
> features（核心功能点），把这几个扔进去，给GPT匹配标签。因为我们的标签本身就是基于功能去打的标签，所以你把产品介绍和key
> features传进去之后，就能够打到很不错的关联上的标签。Tag页面也静态化了。Tag和分类的关系，这里我的确要介绍一下。你会发现我整个网站我没有做分类，只做了Tag。为什么呢？如果你去看别的AI导航，他可能会做分类。因为在我理解为的是，分类是一个产品你只能分在一个内幕下面，而标签是你一个产品可以打多个标签的。这会有个什么样的问题呢？就是说，其实简单的对你这个产品经营一个分类没有多大意义，而且我用标签系统是可以做到分类效果的。举例来说，我们的标签目前有两个大类，一大类叫做产品形态，一大类叫做功能点。那我可以再增加一个叫做分类。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadYOLDk6OKLofohjy7cH432FsXjJcYKWEP2mGW8uPrqybkZA6xiabNgoA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

我们打开Toolify来说。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadCplEBnYtpMfr3zOLiaEePFibviak4rKy3Sjy9mUJjZDNPr6PwpT9diadsA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

好，Category，在这儿。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadsgOxdOWo2AKtmVORPt3fDJvFMOHk2EbEuOEuIkX9Vu5V7Cp9jDbA5w/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * Toolify产品通过标签进行详细分类，未采用传统分类方式。 
  * 页面数据从数据库提取一次后存储在缓存中，使用CDN服务加速静态页面获取。 
  * 标签支持层级关系，如Tags to Image下有Tags to Logo等子标签。 
  * 静态页面在首次访问时生成并存储在缓存中，后续访问直接从缓存获取。 

> 你会发现，Toolify将产品进行了详细的分类，每个分类下包含如AI Blog
> Rewriter、Handwriting等标签。在我看来，这些标签本身已经足够，无需再进行额外的分类。因此，我的设计中只采用了标签，而未设置分类。在访问过程中，我们不是预先加载所有链接，而是在访问前提前做好准备。具体来说，页面只需从数据库中提取一次数据，提取后生成页面并存储在缓存中。此外，我们还使用了cloudflare的CDN服务，以便就近获取静态页面。关于分类的问题，通常我们认为一个产品只能属于一个分类，但如果一个产品需要属于多个分类，使用标签则更为合适。因此，我只采用了标签，未设置分类。标签本身也可以有层级关系，例如，Tags
> to Image是一个大分类，其下可以有Tags to
> Logo等小分类。目前，我的标签设计中未包含分类，因为我认为初始阶段应保持简单。我预留了标签的层级关系功能，以便未来扩展。至于静态页面的生成频率，当有人访问时，系统会检查静态页面是否存在，如果不存在则从数据库中提取数据并生成页面。生成的页面会被存储在缓存中，下次访问时可直接从缓存中快速获取。具体的实现原理，建议在群内询问涛涛，他是负责这部分的，我对此不太清楚。我们这里就不展开讨论了。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadIKUPficicf2JA9dGOCsUsfJE60p7lsM4ShnPt5GqoU3e4jx8teM2SREg/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * 通过关键词获取流量，每个关键词对应一个标签。 
  * 每个标签下收录多个产品。 
  * 存在一个尚未被提及的强大功能。 

>
> 在下一步，刚才的介绍中提到，我通过分类来获取流量，每个具有流量的关键词对应一个功能，我都将其设置为一个标签。刚才口误了，是标签而不是分类。然后，每个标签下我会收录众多产品。此外，这里还有一个更为强大的功能，可能是你们目前尚未想到的，是什么呢？

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadunTiajuytRiaR6n0djhIkbReH50nf2ib1x1ibx8KJeF3Tl5I3NE6ibBzNgQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

我在这里举个例子，选择一个具有多个标签的产品，这样更容易解释。好的。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3Xiad2mEKtZ8mNMbicA0EsllLo4FbU1MmgzJj26w4oX26xRtDIqmOicqkw7CQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

您会注意到，该产品被标记了两个标签，分别是“AI Q&A Platform”和“Chatbot”。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadHlnw8m5I5Vkx2l4RRSnEUrWtaNtKeUT3k7hXjaB3iaNeQSbZcicLnybA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

好 重头戏在这里呢

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadquZbbgM6gksNf9V5uJ2QicJra9Ulj4ASYJ0keNNSHxMIgxvuKibMLpFQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * 展示的产品模块中，点击“View More”进入新页面。 
  * 新页面之前介绍过P页面和T页面。 
  * 新页面由涛涛同志负责，使用全称作为名称和目录。 
  * 涛涛同志选择使用全称，未采用A开头的单词或字母。 
  * 该名称是产品名称，后续提及产品的替代品。 

> 在这个模块下，我们展示了一些产品。关键在于，点击View
> More后，会进入一个新的页面。这个新页面之前已经介绍了P页面和T页面。现在，这个页面是由涛涛同志负责的，他直接使用了全称作为名称和目录。虽然如果保持风格一致，使用A开头的单词或字母也是可以的，但他已经采用了全称，所以就继续使用这个名称。这是一个产品名称，接下来是这个产品的替代品。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadPzeEdAgCuDfRmZq1rgBccoeQ7Vjib1ODShovqONlc86OWJEPvCmsTvw/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

关于替代产品，请看下方列表，我将为您介绍在AI
Q&A分类下有哪些可替代的产品。目前，该页面尚未完成。我已经完成了任务，明天我会与同事讨论，指出还需要改进的几个方面。举例来说，在这里边标题上，可能加上这个会更好。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadDoJrSG2Ok5AQfjR6PiaTtaywIzFVOHiaMABRdicShQymLkFTAjGUD0y8w/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

因此，您会发现，如果我为该产品添加了多个不同的功能标签，我会向用户说明，在第一个产品功能下，有哪些可替代的产品可供选择。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadEBaaCYMN3TpftDictmOve53kQn4N2cllcl7dW6f1X2XSVoJCNMiaRydw/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

在第二个产品功能下，你有哪些可替代产品？这个是失误，明天我会改掉的。因为website是产品形态，产品形态不需要放在这里边，没必要展示出来。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadRjN7SancW0BHBxGFicuuNTTAkTXq5cNiasduczp5O62ztHrFW7sicPBjg/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

好，然后我点进去chatbot呢。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadIlHiaCErJ1CicXwwLtv4NCwByxvavf3P3rhsaKQvwvj8fqTydUxlZVBQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这就是那个对应的那个标签，是吧?

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadFOGLXEyUavmKp2RTUpVn2Xn4SWakooNXoLXuKAxIapph1nwzVfVtJA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

我这里还有一个页面，目前尚未发布。我们来看一下当前页面的主打关键词是什么？当前页面的主打关键词是关于该产品在2024年的替代品有哪些。其实，用户可能会搜索某个产品的某个功能有哪些替代品。你问了一个好问题，关于这里的替代品是如何的？

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3Xiadg9iaTmrDm1tWeYHg9WGT9SibYMzibKkhUWX1aEe93xnRPGvTKNIaG0kwA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

很简单，因为我给这些产品都打了相同的features标签，即AI Q&A
platform标签，所以我将它们都归类到这个标签下。这个标签的产品只需列出即可，您可以看到，这正是我的Fetures标签系统的强大之处，相同的标签能够实现高效管理。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadRYhZaKkKTahkNWvlV90YvDcxiccUu3KANV5tiacibsbV31Aca9GfaB1IQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **标签与产品管理** ：讨论了当标签对应的产品数量众多时，如何通过显示最新或最热门产品、使用二级标签等方式优化展示。 
  * **页面生成技术** ：采用实时生成的静态页面技术，非预先生成HTML文件，技术细节参考Vercel文档。 
  * **竞争策略** ：强调站内SEO和网站权重的重要性，通过谷歌搜索结果评估竞争难度。 
  * **品牌词与域名** ：提到谷歌认证的域名和品牌词优化，最终目标是创建AI百科问答网站。 

>
> 由于当前页面尚未完成最终设计，因此目前不便详细讲解。待页面完成后，我们将在群内进行详细介绍。今天我们讨论的是，当一个标签对应的产品数量众多时，是否会有大量的替代品出现。确实，当产品数量庞大时，替代品自然会增多。对此，我们有多种解决方案。例如，可以仅显示最新的10个或20个产品，或者只展示最热门的产品。此外，我们还可以在AI
> Q&A
> Platform上，探索哪些产品是热门或最新的替代品。同时，我们也可以通过更细分的二级标签来进一步优化展示。目前，标签功能已经可以实现，但未来将由AI系统来完成。
>
>
> 关于页面生成，我们采用的是实时生成的静态页面技术，并非预先生成HTML文件。这是一种虚拟文件，具体技术细节可以参考Vercel的文档，他们提供了缓存页面功能。此外，关于购买AI域名的问题，实际上有很多途径可以购买，且AI域名价格普遍较高。
>
>
> 在竞争方面，即使有人采用相同的思路创建同类网站，由于每次生成内容的不同以及参考资料的差异，最终产品也不会完全相同。竞争的关键在于如何做好站内SEO和提升网站权重。要评估是否能超越竞争对手，可以在谷歌搜索中查看前十名的结果，如果大部分是其他网站的首页且外部链接众多，那么超越难度较大；如果是内页，则有机会通过全站优化来超越。
>
>
> 关于品牌词和谷歌认证的域名，如果该词已经被谷歌关联到特定网站，那么就没有必要再进行优化。此外，我们的最终目标并非创建导航站，而是一个AI百科问答网站。通过举全站之力，即从多个角度和维度介绍关键词，可以更有效地优化网站内容。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3Xiad5MQiasu9jmlngP3KjR4hYumcZmMJznIJrgBib8fJK2OxsjAibhZkqNEfg/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

刚才给大家介绍说我收录了某一个产品，那我这个产品下面呢，我会有不同的section页面。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadS8dTra7wVaRG3VWGSiacuzVFc5Qr9osnqsc8AD2BuKE10GUrNLTXmDQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * 采用多页面结构，每个页面设有返回上一页的链接，形成紧密的内链关联。 
  * 通过多个页面共同优化关键词，不依赖单一页面。 
  * 关键词优化策略涉及多个页面的协同工作。 
  * 对于流量不足的情况，首先考虑提升流量。 
  * 针对特定产品关键词，创建多个不同页面进行优化。 

>
> 我之所以设计多页面结构，是因为每个页面都设有返回上一页的链接，这种合理的内链设计使得页面之间形成了紧密的关联。通过这种方式，我向谷歌展示了我不仅仅依赖单一页面来优化关键词，而是通过多个页面共同作用来实现这一目标。此外，我围绕关键词的策略也涉及多个页面的协同工作。对于流量不大的情况，是否存在合适的变现方式？如果流量不足，首先应考虑如何提升流量。在进行整体规划时，我始终全力以赴。例如，当我针对某个产品关键词进行优化时，我会为其创建多个不同的页面。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadmuUVvO6ib9E4KR3tCoHDYKue2T9rLjcAwKHVaz2NKC2QzkicRaoSB3Aw/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * **页面结构优化** ：建议每个二级关键词生成独立页面，避免集中在一个主页下，以防止被搜索引擎视为重复内容。 
  * **内容分布策略** ：主页应包含各部分的总结性内容，详细内容通过点击查看，以优化用户体验和搜索引擎优化（SEO）。 
  * **技术实现** ：页面内容存储在数据库中，使用服务端渲染确保搜索引擎爬虫能抓取到完整内容，无论内容如何生成。 
  * **长期SEO策略** ：即使面对行业大站，通过持续优化和提升网站权重，长期内仍有可能超越这些大站获得更好的搜索排名。 

>
> 从不同角度审视不同的二级关键词，并生成相应的页面来处理这些关键词，避免仅依赖单一页面。有人提问，当前的做法是将所有内容集中在一个Page页面，同时将单独的内容放置在不同的Section页面，这样做是否存在问题？确实存在问题，可能会被谷歌视为重复页面。更好的做法是，每个Section生成不同的内容。例如，我的网站架构显示，一个Section下可以包含多条内容，第一条内容可以是总结性的，后续内容则详细介绍。最终的Page页面只需包含各个Section的总结性内容，详细内容需点击查看，这样就不会有问题。
>
>
> 你提到的关于Page和Section分别生成内容的做法是可行的。这些页面并非静态页面，我生成的内容全部存储在数据库中，为文本数据。如果这些页面都是静态的HTML，与后台存储的SEO权重是否不同？这里并无不同。谷歌的爬虫不关注最终构造HTML的方式，只关注爬虫抓取到的内容是否存在于HTML代码中。如果使用前端渲染，抓取到的HTML代码可能只包含框架代码，这是不可行的。只要返回的HTML中包含内容，无论使用何种程序或方式生成，都无关紧要。
>
>
> 时间已过去两个半小时，今晚的讨论就到此为止。需要进行服务端渲染，最后再回答一两个问题。请点赞并关注“哥飞出海”公众号和视频号，视频号关联的公众号也值得关注。公众号内有300多篇关于如何做网站、出海、流量运营的文章。
>
>
> 如果搜索结果前排都是业内大站，这种词能否做？可以做，虽然短期内可能无法获得排名，但长期来看，谷歌一定会将一个有足够权重和权威性的优质网站排到这些大站前面。再看看表结构吧。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadWK09pL4ETIl6KPIkWZryqn6CJ5qlRh49ibmLkd0gkQdCBYZnEc53ib0g/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)
![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadlBc1T0nwQLs5J3qAaItpRZ18Nb6sV4OQlhJf4mSOmvdhuUO85yYKVg/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)
![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadcHrfYpqSk8eZHbklWBQcgfO91ic2dNS4JTkdQib5N3ossr1Czw2ldiauA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

每个页面停留两秒钟，配置表。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3Xiad3MwWfq8tGw8Fvfyx3pahDhR3j3KHzjdQrQAOGAk8huu19XZKJNGQNA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

配置参考资料表、section表、content的资料表。

![](https://mmbiz.qpic.cn/mmbiz_jpg/g7rR9mua00KIvqUvLbdDBVgfQhMu3XiadBIxtwxmNqibmboiavSMIKFqSjiaibghZHKdfBMKLIjRldGEa7FAeSVbmGQ/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  * AI技术有助于新词在搜索引擎中被收录。 
  * 优化传统行业旧词的方法是通过分析谷歌排名靠前的页面。 
  * 需要理解这些页面排名靠前的原因，并在自己的页面上进行改进。 
  * 讨论时间有限，实际已花费两个半小时深入探讨。 
  * 邀请听众加微信和关注公众号。 

>
> 最后这个页面，AI站全是新词容易被收录，如何利用我的模式去优化传统行业的旧词呢？实际上，这可以通过分析每个词在谷歌排名靠前的页面来实现。你需要了解它们为何能排名靠前，并尝试在你的页面上做得更好。是的，15分钟的时间显然不足以详细讨论这个问题，实际上我们已经花了两个半小时来深入探讨。请加我微信，关注我的公众号，谢谢大家，再见。

好了，到此为止，总共两万五千字图文就全部发完了。  

关于哥飞介绍可以看这里：  [ 哥飞是谁，哥飞在做什么事情，在哥飞公众号大家可以看到什么内容
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082843&idx=1&sn=50add036fed1ac78f2c71887bbedb990&chksm=bf3f3f208848b63647147b8c3328bfe12497d281c9c4257d548e83b095b6db33d29e2f6d03e6&scene=21#wechat_redirect)  
关于哥飞社群可以看这里：  [ 是时候给大家好好介绍一下哥飞的社群了，毕竟刚被二十年站长大佬夸过
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082450&idx=1&sn=b33f52d905edd76782d85eb06163f312&chksm=bf3f3da98848b4bf8214219c775293b397bdda48f14975f88e55a5bbe7efa75e4b11d93010a5&scene=21#wechat_redirect)

下面给大家介绍一下哥飞的这个付费社群。

如果你是程序员，那么这绝对是你不能错过的一个社群。  

2024年，哥飞想达到这个目标：  
帮助20000+程序员了解出海；  
帮助2000+程序员参与出海；  
帮助600+程序员能够月入1000+美金；  
帮助100+程序员能够不再上班养活自己；  
帮助10+程序员建立自己的AI工厂。

其实目前哥飞已经有好几个朋友建立自己的AI工厂了，如Gary、AUDI、Alaadin、二两等。也有好多个朋友可以不上班就养活自己了，如Banbri、BingNi等。  

现在，哥飞一边开着自己的AI工厂，一边  带着大家一起出海赚美元，《 [ 【养网站防老】每个人都要有自己的小果园，今天请为你的果园种下第一棵小树苗吧
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650082415&idx=1&sn=8b725d7238143cdf7b0992b6f7835b57&chksm=bf3f3d548848b442dafc0a5fa379cf90be1749a82d62c2371d2140fed2cc5bbc86e3430e2d6f&scene=21#wechat_redirect)
》。

哥飞会用自己实践总结出来的最新的经验来教给大家，如何挖掘需求，如何实现需求，如何做好SEO，如何运营推广，如何变现赚美元。  

给  大家看看已经在社群里的其他朋友怎么评价的吧。

  

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeictfJNjePhchkZYLuBwKPcJl2yZPhaRV7VWHg1Fe9tIs05v9QTFBq1oCZjVn9qB08LszWxrFibHHeMQ/640?wx_fmt=other&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicsc3DNibdfcSLWyEGZBZSXSUbPuaibAobt9LPMO3wygibBF21OuH0mCYZU6Hn3qgz5Zvxml98F9dKnrQ/640?wx_fmt=other&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

  

![](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicu0ohJ2AspibworASbayGLjNicts7f15fE789SLz4EI2yZgzHicU6KCsqDNVgkpOwdulS8sGWaSXSRVg/640?wx_fmt=other&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

  
那么这到底是一个什么样的社群呢？  

  

一句话介绍，这是一个教你  出海做网站赚美元  的社群。  

  

哥飞知道，肯定会有人说，教人赚钱最赚钱。  

  

但是，哥飞这个社群，你学了，是真的能够赚美元的。

  

因为哥飞不是教你做一个类似的社群去赚别人的钱。  

  

哥飞教你怎么挖掘需求，怎么搞SEO，怎么搞流量，怎么把流量变现。

  

或者说，哥飞其实是在给大家做微培训。

  

如果想更多了解社群，或者想加入社群，请加哥飞的微信 GeFei55 。  

  

当然，即使你现在不加社群，也可以先关注哥飞的公众号，多看几篇文章，你会有收获的。  

  

  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicvZa9oicq3B1RX3fQHZibhLpskbS7RgnDRLTwyaibuWKUxk5jVsTIIA4BySYdCHACblrrCSqcsyOmRHg/640?wx_fmt=other&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

预览时标签不可点

微信扫一扫  
关注该公众号





****



****



  收藏

