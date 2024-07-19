![cover_image](https://mmbiz.qpic.cn/mmbiz_jpg/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzyYFZHW85OUp3IEajibaDSz6Dh2yiayPd6K1c3W9WvnxXuDMPgSMgHrOTA/0?wx_fmt=jpeg)

#  我解锁了 ChatGPT 的一项隐藏能力，既能一键复制对话，又能提取指定内容结构化输出

原创  我是哥飞  [ 哥飞 ](javascript:void\(0\);)

__ _ _ _ _

这几天，哥飞对 ChatGPT 真是上瘾了，有空就玩两把，昨晚，哥飞解锁了 ChatGPT 的一项隐藏能力。

在电脑上，我们可以用 ShareGPT 来保存与 ChatGPT 的对话并分享链接出去，但是在手机里好像就只能截图了。  

昨晚，哥飞突发奇想，是否可以让 ChatGPT 自己把对话输出到代码框里，这样就可以用代码框右上角的一键复制按钮把对话复制出来了。

一试，还真可以，而且远比我们想象到的更强大，不仅能够输出对话原文，还可以从对话里提取指定内容，结构化输出。  

我们先输入一个 markdown 格式表格，让 ChatGPT 在网页里用表格显示数据。  

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzyX8H5Rs1rne9DmGvtgufHm6hxA6PaIQ2eibwTYWbbf5WPC0NGMKA76aQ/640?wx_fmt=png)

接着，我们要求 ChatGPT 按照 json 格式输出。

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzyTRQZEkQoMSxm0Z6YZmpzVIlEcREEFJFbFRYWgSXaCar00whnjvYurQ/640?wx_fmt=png)

接着，我要求 ChatGPT 把上面的对话用 json 格式输出，并且指定了 json 的格式。

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzyZ5LjKo7bIrYzxkqJtot7csJEMGemont9icypUhdlwoRGJTGYibeZyTBA/640?wx_fmt=png)

请记住魔法语句：

  * 

    
    
    请把以上对话用json格式输出，我问的用q，你回答的用a，每一组对话放在一个对象里，不同的对象放在数组里

用上这个魔法语句，你就可以点击代码显示框的右上角“Copy code”一键把对话复制，并且是 json 格式化后的对话，方便你在别处还原对话。

接下来，我们提一点更高难度的要求，让 ChatGPT 从对话里提取我们指定的内容，并且按照指定的格式输出 json 格式数据。

我们先喂一点数据进去。  

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzydPiau7n7vZRKDXm61m7tedibGwicPGdAIyKribOZK0Clyaz1HWFTmnLPzA/640?wx_fmt=png)

接着，说出魔法语句：

  * 

    
    
    请把以上对话中出现过的单词中英文输出为 json 格式，要求：每一个单词一个对象，多个对象放在一个数组里，英文放在 english 里，中文放在 chinese 里，类型如动物、植物、水果等放在 type 里

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzy9Sn5EM4GF5LpA1cl4DOTDsEL1fE0WICzgiae30v1C3NqHDUgrGzkNCg/640?wx_fmt=png)

可以看到，这次 ChatGPT 输出的并不是对话全文，而是从对话里提取的信息，并还根据我的要求，把 type 也放进去了。  

尤其我第三次对话，问的是中文的英文，而不是像第一次对话，问的是英文的中文，ChatGPT 都能够合理总结并输出。  

还有更多魔法语句：

  * 

    
    
    请用表格显示这组数据

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzyz9VX9qNfEeUepQYbpUrq9lGnuZicsVlY2KA8n70eoyicHAftjAQK4eyA/640?wx_fmt=png)

  * 

    
    
    请输出 markdown 格式代码

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzy866qb9T3k4YJfKVDa9Mm9exJwqre1EhP8PmIW1dzIMJ8ia0GQY2Ntmw/640?wx_fmt=png)

  * 

    
    
    请输出 html table 格式代码

![](https://mmbiz.qpic.cn/mmbiz_png/LBrX00GQeicuVeE40tQKgP6wCFBMoqXzy68yWLqHkNVe1HE7FrRGw4XbRslIQqXPcl9qzSBLtDQ73xlX4UoSZfg/640?wx_fmt=png)

你还有更多魔法语句吗，请在评论区说明。  

预览时标签不可点

微信扫一扫  
关注该公众号





****



****



  收藏

