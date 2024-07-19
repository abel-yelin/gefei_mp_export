![cover_image](https://mmbiz.qpic.cn/sz_mmbiz_jpg/LBrX00GQeicvUEwygQHLTODbRVsrgqoCj9SIykH1E8Ew2f2GIgQ5EeTe0MVYMJDxybRSh3XDo8mx4CMKcqzQwFA/0?wx_fmt=jpeg)

#  养网站防老第3步：根据搜索意图使用ChatGPT的GPT4生成网页

原创  我是哥飞  [ 哥飞 ](javascript:void\(0\);)

__ _ _ _ _

大家好，我是哥飞。  

网站养老系列哥飞已经更新了4篇了：  

[ 养网站防老：网站可以做成一生的事业
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080601&idx=1&sn=676b0fff888c93fd63b283e87a3c75d2&chksm=bf3f34628848bd74e4a6ebac72806e89be8bbc9440196edf14cf4f08837f3a81970070a21da2&scene=21#wechat_redirect)  

[ 养网站防老第1步，挖掘出第1个需求
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080669&idx=1&sn=baf814d85976df09a85c44d9a45a943b&chksm=bf3f34a68848bdb065889163a3b58f10566b937769d679fa50b25768351d55ea4ef24271cae4&scene=21#wechat_redirect)  

[ 养网站防老第2步：分析搜索意图
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080680&idx=1&sn=4ee04f6579aaa40acefb96318310cbcc&chksm=bf3f34938848bd850bcd811892f9b71c7a51512f9d010ab7aae46487eb045559ac55e9bd70ed&scene=21#wechat_redirect)  

[ 养网站防老第1.5步：用一个公式来判断关键词是否值得做，让你选择关键词不再犹豫
](http://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080690&idx=1&sn=b6b8b6fbcbc1a57e476d61e574f5c1a1&chksm=bf3f34898848bd9f107fff59df18264e792c3161734b71abc48713e49c9845ec02daa243f596&scene=21#wechat_redirect)  

本来昨天就要发第3步的，我们临时决定插入一篇文章，先教会大家怎么选择关键词。

基于昨天哥飞讲的公式，社群里@Kunsect 做了一个小工具，能够把大家从 Semrush
下载的关键词表格计算出“优化回报率”，并支持下载计算好的新表格。工具是在前端做的计算，所以大家不用担心自己正在调研的关键词被泄漏，同时工具还是开源的，大家可以自己部署使用。

工具网址：https://roi-calculator-flame.vercel.app/  

开源代码：https://github.com/Kunsect/roi-calculator

  

今天我们回到第3步，讲讲如何根据分析出来的搜索意图去让GPT帮我们制作网页。  

我们先在 Semrush 搜索“phone number generator”，得到所有相关关键词，点击导出按钮，得到关键词表格。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicticF1y80jsaJcuQxn7r61dLsoQ5IgHwsjjgrp65RR3Svwr0ELMO9gibHtL0ibNWNS7pNKeYiaNG3XKIw/640?wx_fmt=png)

之后上传到 @Kunsect 制作的小工具里，得到了最值得做的一些关键词。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicticF1y80jsaJcuQxn7r61dLOwOFgSasn3nNrVvDP8ksfhk8qfVMxDFwPw4IwIm9JkV17vCyerNnQQ/640?wx_fmt=png)

可以看到，最值得做的，还是主关键词“phone number generator”，我们昨天已经分析了这个关键词的搜索意图：  

> 用户可能寻求一个工具或服务，用于生成电话号码。这可以是出于各种目的，例如随机生成测试数据或隐私保护。
>
> 我是哥飞，公众号：哥飞 [ 养网站防老第2步：分析搜索意图
> ](https://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080680&idx=1&sn=4ee04f6579aaa40acefb96318310cbcc&chksm=bf3f34938848bd850bcd811892f9b71c7a51512f9d010ab7aae46487eb045559ac55e9bd70ed&token=243871311&lang=zh_CN#rd)

我们网站也的确是围绕着关键词  “  phone number generator
”来做优化的，但是因为全球每个国家的电话号码格式都不一样，所以我们的电话号码生成需要能够兼容各个国家。

最直接想到的办法是给出一个下拉框让用户选择需要生成哪个国家的，但是全球这么多国家，从下拉列表里查找很不方便。  

哥飞之前讲过，网页优化可以总结为六字真言“分门别类罗列”：

> 对此，哥飞总结了两点精髓：分门别类、罗列成语
>
> 我是哥飞，公众号：哥飞 [ 分享一个谷歌和百度都优化得不错的网站
> ](https://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650079796&idx=1&sn=235a92567234151a1a06f08ceb0e014a&chksm=bf3f330f8848ba19adae2069b35b6daaf4c3c34dd51db2cd73a27418ca282d88ad74b94fc7af&token=243871311&lang=zh_CN#rd)

>
> 哥飞之前讲过，一般权重关系是主域名>子域名>子目录>内页，所以我们如果要优化一个关键词的话，最好的办法就是用这个关键词注册一个域名，然后用上哥飞总结的六字真言“分门别类罗列”来做站内优化。
>
> 我是哥飞，公众号：哥飞 [ 保小图大：专门给给初学者的用小词图谋大词做站策略
> ](https://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080426&idx=1&sn=86da6a2e5286dbf1079364af9b02bbd4&chksm=bf3f35918848bc874fe572059c2386c7e17df09ae6118ea336e7b1d653f740e09c06497043e0&token=243871311&lang=zh_CN#rd)

所以对于  “  phone number generator  ”网站，我们的首页也可以用这个方法，分门别类罗列全球各个国家。  

我们打开ChatGPT，把需求描述给GPT4：  

  *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    你是一个SEO专家和前端开发专家，擅长使用html+css实现符合SEO要求的前端页面。我现在要建立一个关于“phone number generator”的网站，要求能够帮助全球各个国家的用户都生成电话号码，每个国家的电话号码格式都不一样，所以我会给每个国家制作一个页面，如“us phone number generator”、“china phone number generator”等，这就要求在首页把各个国家都列出来。我的想法是先在网站顶部用h1写出“phone number generator”，之后列出各个国家的名字，之后生成很多的 h2 ，每一个 h2 就是一个国家的名字+phone number generator，所以完整的 h2 举例是“us phone number generator”。每一个h2下方会有一小段描述文字，用p标签，描述文字下方是一个按钮，按钮文字为“us phone number generator”，不同的国家需要替换成不同的名字，点击按钮后打开新页面，不同的国家，新页面url不一样，如美国则页面url为“us-phone-number-generator”，现在，请帮我生成页面，要求符合SEO规范。对于我没有提要求的地方，你可以按照你的理解去做。

GPT4的回答如下：

  *   *   *   *   *   *   * 

    
    
    好的，根据您的需求，我为您提供了一个基本的前端HTML代码模板。我会确保其符合SEO基本规范：  
    使用语义化的HTML标签，如<header>, <nav>, <main>, <section>, <footer>等。使用<h1>到<h6>来组织页面内容的层级。为主要内容和按钮提供描述性的<alt>标签或<title>属性。为每个国家的链接使用了易于理解和搜索引擎友好的URL结构。这里仅列出了两个国家作为示例，您可以根据需要添加更多。

  *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    <!DOCTYPE html><html lang="en">  
    <head>    <meta charset="UTF-8">    <meta name="viewport" content="width=device-width, initial-scale=1.0">    <title>Phone Number Generator</title>    <meta name="description" content="Generate phone numbers for various countries around the world.">    <link rel="stylesheet" href="styles.css"> <!-- 这里连接到您的CSS样式表 --></head>  
    <body>    <header>        <h1>Phone Number Generator</h1>    </header>    <nav>        <!-- 如有需要, 可以在这里加入导航栏内容 -->    </nav>    <main>        <section>            <h2>US Phone Number Generator</h2>            <p>Generate valid US phone numbers with our tool. Suitable for various applications and tests.</p>            <a href="us-phone-number-generator" title="Generate US Phone Number">                <button>US Phone Number Generator</button>            </a>        </section>  
            <section>            <h2>China Phone Number Generator</h2>            <p>Generate valid China phone numbers with our tool. Perfect for various applications and tests.</p>            <a href="china-phone-number-generator" title="Generate China Phone Number">                <button>China Phone Number Generator</button>            </a>        </section>  
            <!-- ...您可以继续添加更多国家的sections... -->    </main>    <footer>        <!-- 如有需要, 可以在这里加入页脚内容，例如版权声明、联系方式等 -->    </footer></body>  
    </html>  
    

  *   *   *   *   *   *   * 

    
    
    一些建议和注意事项：  
    确保为每个页面提供了描述性和唯一的<title>标签和<meta name="description">内容，以增强搜索引擎的可发现性。考虑为每个国家的页面提供更多的描述性内容或与之相关的信息，以丰富页面内容并提高其对搜索引擎的吸引力。尝试使用schema.org的标记，这可以帮助搜索引擎更好地理解和展示您的网站内容。考虑为页面添加一个sitemap.xml，以帮助搜索引擎抓取和索引所有页面。希望这可以帮助您建立一个SEO友好的网站！

以上代码部分需要保存为文件 index.html。  

哥飞又让GPT4生成css样式：  

  * 

    
    
    请帮我生成styles.css，要求用简洁大气的配色

GPT4的回答：  

  *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    /* Reset some default browser styles for consistency */body, h1, h2, p, a, button {    margin: 0;    padding: 0;    font-family: 'Arial', sans-serif; /* 使用常见的无衬线字体 */    text-decoration: none;}  
    body {    background-color: #f4f4f8; /* 轻微的灰色背景 */    color: #333; /* 主要文字颜色 */    line-height: 1.5;    padding: 20px;}  
    header {    text-align: center;    margin-bottom: 50px;}  
    h1 {    font-size: 2em;    margin-bottom: 20px;}  
    main {    max-width: 800px;    margin: 0 auto; /* 居中主内容区域 */}  
    section {    background-color: #fff;    padding: 20px;    border-radius: 8px; /* 添加圆角 */    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* 轻微的阴影 */    margin-bottom: 30px;}  
    h2 {    font-size: 1.5em;    margin-bottom: 10px;}  
    p {    margin-bottom: 20px;}  
    button {    background-color: #2c89a0; /* 选中的宁静蓝色 */    color: #fff; /* 按钮上的文字颜色 */    border: none;    padding: 10px 20px;    border-radius: 5px;    cursor: pointer;    transition: background-color 0.3s;}  
    button:hover {    background-color: #247a8c; /* 按钮hover状态时的颜色 */}  
    footer {    margin-top: 50px;    text-align: center;}  
    

以上代码需要保存为文件 styles.css 。

基于以上GPT4生成的代码，哥飞创建了一个网站目录，把两个文件放进去：  

/index.html  

/styles.css

接着浏览器打开，看看效果，还是很不错的，第一次就达到了几乎可用的效果：  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicvUEwygQHLTODbRVsrgqoCjK4zBReDMXNwApb4ylmcsrac9uwNkYgaCdCRtEhtgqRQhiccIiaWOBVuA/640?wx_fmt=png)

不过也有点不足，缺少了哥飞提的需求，在h1下方列出所有国家名字，所以我们再次提需求：

  * 

    
    
    你漏掉了我的一个需求，在h1下方，需要设置一块区域，显示所有国家名字列表

GPT4的回答：

  *   *   * 

    
    
    对不起，我错过了这一点。以下是修改后的styles.css和index.html文件，添加了国家名单的部分。  
    styles.css（新加的部分在最下方）：

  *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    /* ...原先的CSS代码... */  
    /* Country list styles */.country-list {    display: flex;    flex-wrap: wrap;    gap: 10px;    margin: 20px 0;    justify-content: center; /* 让国家列表居中 */}  
    .country-list a {    background-color: #e0e0e0; /* 轻微的灰色背景 */    padding: 5px 15px;    border-radius: 5px; /* 圆角 */    color: #333;    transition: background-color 0.3s;}  
    .country-list a:hover {    background-color: #d0d0d0; /* 鼠标悬停时的背景色 */}

  * 

    
    
    index.html（在<header>下加入国家列表）：

  *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    <!-- ...之前的HTML代码... -->  
    <header>    <h1>Phone Number Generator</h1>    <div class="country-list">        <a href="us-phone-number-generator">US</a>        <a href="china-phone-number-generator">China</a>        <!-- ...更多国家的链接... -->    </div></header>  
    <!-- ...之后的HTML代码... -->  
    

我们把GPT4给的新代码，分别添加到 styles.css 和 index.html 中，保存后再次刷新浏览器，得到了新的效果。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicvUEwygQHLTODbRVsrgqoCjbzDtpjrg2EcFA8HCkIBaDBiaag1AbdSlMp6h5roy8YRBHQDs3KicyyBQ/640?wx_fmt=png)

大概效果没问题了，接着需要让GPT4列出更多国家，并且生成相关代码。  

我们继续提要求，限于篇幅原因，哥飞这里只让GPT4列出10个国家，实际使用时，你可以让AI列出100个国家。  

  * 

    
    
    目前你只列出来了2个国家，请按照互联网用户数量，列出10个国家，并生成相关代码

GPT4的回答：  

  *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    好的，按照互联网用户数量，以下是10个国家的列表（截止到我的最后的训练数据，2022年1月）：  
    中国 (China)印度 (India)美国 (United States/US)印度尼西亚 (Indonesia)巴西 (Brazil)巴基斯坦 (Pakistan)尼日利亚 (Nigeria)孟加拉国 (Bangladesh)俄罗斯 (Russia)日本 (Japan)以下是根据上述列表修改的index.html部分：

  *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    <!-- ...之前的HTML代码... -->  
    <header>    <h1>Phone Number Generator</h1>    <div class="country-list">        <a href="china-phone-number-generator">China</a>        <a href="india-phone-number-generator">India</a>        <a href="us-phone-number-generator">US</a>        <a href="indonesia-phone-number-generator">Indonesia</a>        <a href="brazil-phone-number-generator">Brazil</a>        <a href="pakistan-phone-number-generator">Pakistan</a>        <a href="nigeria-phone-number-generator">Nigeria</a>        <a href="bangladesh-phone-number-generator">Bangladesh</a>        <a href="russia-phone-number-generator">Russia</a>        <a href="japan-phone-number-generator">Japan</a>    </div></header>  
    <!-- ...之后的HTML代码... -->

  *   *   * 

    
    
    为了完整性，您可能还需要为每一个国家在<main>部分增加对应的<section>内容。此外，不要忘记在相应目录下为每个国家创建相应的页面，如china-phone-number-generator.html、india-phone-number-generator.html等。

哥飞继续提要求：  

  *   *   *   *   *   *   *   *   *   * 

    
    
    以下部分也请把全部10个国家列出来：```<section>            <h2>China Phone Number Generator</h2>            <p>Generate valid China phone numbers with our tool. Perfect for various applications and tests.</p>            <a href="china-phone-number-generator" title="Generate China Phone Number">                <button>China Phone Number Generator</button>            </a>        </section>```

GPT4的回答：  

  *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *   * 

    
    
    <section>    <h2>China Phone Number Generator</h2>    <p>Generate valid China phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="china-phone-number-generator" title="Generate China Phone Number">        <button>China Phone Number Generator</button>    </a></section>  
    <section>    <h2>India Phone Number Generator</h2>    <p>Generate valid India phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="india-phone-number-generator" title="Generate India Phone Number">        <button>India Phone Number Generator</button>    </a></section>  
    <section>    <h2>US Phone Number Generator</h2>    <p>Generate valid US phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="us-phone-number-generator" title="Generate US Phone Number">        <button>US Phone Number Generator</button>    </a></section>  
    <section>    <h2>Indonesia Phone Number Generator</h2>    <p>Generate valid Indonesia phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="indonesia-phone-number-generator" title="Generate Indonesia Phone Number">        <button>Indonesia Phone Number Generator</button>    </a></section>  
    <section>    <h2>Brazil Phone Number Generator</h2>    <p>Generate valid Brazil phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="brazil-phone-number-generator" title="Generate Brazil Phone Number">        <button>Brazil Phone Number Generator</button>    </a></section>  
    <section>    <h2>Pakistan Phone Number Generator</h2>    <p>Generate valid Pakistan phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="pakistan-phone-number-generator" title="Generate Pakistan Phone Number">        <button>Pakistan Phone Number Generator</button>    </a></section>  
    <section>    <h2>Nigeria Phone Number Generator</h2>    <p>Generate valid Nigeria phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="nigeria-phone-number-generator" title="Generate Nigeria Phone Number">        <button>Nigeria Phone Number Generator</button>    </a></section>  
    <section>    <h2>Bangladesh Phone Number Generator</h2>    <p>Generate valid Bangladesh phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="bangladesh-phone-number-generator" title="Generate Bangladesh Phone Number">        <button>Bangladesh Phone Number Generator</button>    </a></section>  
    <section>    <h2>Russia Phone Number Generator</h2>    <p>Generate valid Russia phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="russia-phone-number-generator" title="Generate Russia Phone Number">        <button>Russia Phone Number Generator</button>    </a></section>  
    <section>    <h2>Japan Phone Number Generator</h2>    <p>Generate valid Japan phone numbers with our tool. Perfect for various applications and tests.</p>    <a href="japan-phone-number-generator" title="Generate Japan Phone Number">        <button>Japan Phone Number Generator</button>    </a></section>

我们拿着新的这部分代码放到之前的代码文件里，之后刷新浏览器，就得到了我们想要的页面：  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicvUEwygQHLTODbRVsrgqoCj6Oh0ZGEbTj8Cgmic2u9gR7WWnka8S7hLJXKaXl9UY6NsZmAoolDYyWg/640?wx_fmt=png)

可以看到，整体效果还是不错的，目前GPT4在生成简单的前端页面时，已经可以做到不需要我们修改代码，只需要不断的提要求让GPT去完善页面就行。  

看完哥飞的完整演示，你学会了吗？有任何疑问都可以在评论区留言。

哥飞的社群现在已经有五百多人加入了，所以分为了一群和二群，目前一群453人，二群78人。也就是说说，一群还有47个位置，而二群目前价格500元，还剩28个位置，就要涨价到555元了。

你想要养网站防老吗？欢迎加入哥飞的社群，一起探索如何从种下第一棵树（网站）开始，建立起自己的果园，并且年年都能够收获果实。  

> 6、做网站就像是种树一样，先种下第一棵树，再种下第二棵树，慢慢你就有了一个小果园，收成会越来越好；
>
> 7、尽量多种几种不同品种的果树，既可以使得一年四季都有水果吃，又可以防止“病虫害”导致同种果树死亡；
>
> 8、网站可以做成一生的事业，只要碳基生命还存在，就还会有网站的需求，我们就还能靠网站来赚钱；
>
> 9、养儿防老不如养网站防老。
>
> 我是哥飞，公众号：哥飞 [ 养网站防老：网站可以做成一生的事业
> ](https://mp.weixin.qq.com/s?__biz=MjM5OTIzMzYyMA==&mid=2650080601&idx=1&sn=676b0fff888c93fd63b283e87a3c75d2&chksm=bf3f34628848bd74e4a6ebac72806e89be8bbc9440196edf14cf4f08837f3a81970070a21da2&token=243871311&lang=zh_CN#rd)

如果对社群感兴趣，请加哥飞微信 qiayue 咨询了解。  

![](https://mmbiz.qpic.cn/sz_mmbiz_png/LBrX00GQeicsG8Pro6O9Hu75bIIiafZVPs3qlYeaNNJ1BpqNplEGgibL5m1bcq8a1N1rzoI5lia8aJjtHfgiaAADJJQ/640?wx_fmt=png)

预览时标签不可点

微信扫一扫  
关注该公众号





****



****



  收藏

