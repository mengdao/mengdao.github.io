---
layout: page
title: "test jekyll"
category: team
date: 2015-03-13 14:32:24
---


## 目录

[我为什么爱你气质忧郁](#我为什么爱你气质忧郁)

## 我为什么爱你气质忧郁
没有人把忧郁挂在嘴边。我们并不到处八卦新来的IT主管多有忧郁气质，也不会列出让人触景伤情的风景清单（阴天早晨的布赖顿海滩；苏格兰的兰诺克沼泽；西西伯利亚平原）。

但我们还应该更加关注忧郁，甚至时不时地寻找它。

忧郁是悲伤的一种。生命本是苦难，痛苦和失望都是日常体验。明白了这个，忧郁就来了。忧郁不是情绪的失调，无需治疗。

现代社会强调活力和快乐，但不得不承认，现实中的大部分时间，我们是在处理悲伤和失去。理想的生活无法对悲伤免疫，但理想生活里的悲伤应帮助我们成长。

有时你莫名其妙地悲伤。困扰你的不是一件烦心事。整个生活都催人泪下。

忧郁很重要，很珍贵，因为它把痛苦与美和智慧联系在了一起。我们所受的苦不再是混乱的——失败的、错误的——它也跟我们喜爱的东西有了联系。悲伤常常有很大的意义。

想想这些事情吧，看看你是否会忧郁：

我们所爱如白驹过隙
昨日一去不返。每天向死亡靠近一步。小时候爱过我们的人，现在一天天变老。很快，我们也会随着他们的脚步，日渐衰亡。

人类境遇的尴尬和无奈
没人真的理解别人。孤独是如影随形的，孤独是网罗众生的。每个生命都饱尝耻辱忧伤。我们耗尽生命竭力争夺的事情，大部分落空——假使得到了，却又会失望。

他们会长大，他们会为钱苦恼，他们会尝到建功立业的艰难，上瘾，政治冲突，疾病，对感情的失望。

最终，我们所做的都不重要。我们的生命——我们的爱，我们的挂念，我们的悲痛，我们的胜利——全都被冲走。

祖母过世之前，我为什么没有跟她讲过这些。我们后知后觉。我们浪费年月。人人如此。除非关掉想象的闸门，谁也没法避免后悔。谁也不该想象另一个结局。

生命无法避免的矛盾
我们最想要的东西彼此矛盾：要安全感，还要自由；要钱，却不要变成工资的奴隶。要与他人有亲密的关系，却不想被他们的期望和要求窒息。要旅行，要探索世界，却还要深深扎根。要满足我们对食物、饮料、性爱、躺在沙发上的渴望——但是，还想要苗条、清醒、忠诚、健康。

（比起苦涩或愤怒），忧郁的智慧在于知道忧伤并不是一个人的事。你并不特殊，你的苦只是人类的一份。很多时候，我们的忧伤是自我中心的，似乎那是上天单独降下的灾祸。忧郁排斥这样的想法。它视野更广，更少把这当作私人的体验。我们生命中的大部分忧愁和痛苦可以追溯到生命本身：它短暂；我们无法抓住每个机会，欲望和自律永远对立。每个人都受其制约。忧郁是慷慨的。你也会为别人——为“我们”而忧郁。你同情整个人类的境遇。

而这样的同情让我们成为更好的人。它让我们对人的期望更符合实际。无论是谁，都一样承受种种苦难。他们会越轨，会疲惫，会时不时地说谎，会毫无理由地反悔（或毫无理由地固执己见）。我们意识到，生而为人，就早已与种种深重的问题绑在一起。这就是忧郁。心中常常不忘这一点，就是同情。

宗教都是忧郁的倡导者。《基督教祈祷录》中有这样一段话，常在葬礼上出现：

人从母体出生，经过短暂光阴，万般苦难。他长出，又被切下，就像花朵。在生活当中，我们都在死亡。

这一段话是为了引起人们共同的忧郁。在我们所爱之人的葬礼上，我们不仅是在见证一个生命的离去。我们受邀将彼此——以及我们自己——看作逐渐死亡的动物。这不应让我们绝望，而是让我们更加宽容，温和，更能专注于真正重要的东西，趁时间还来得及

## 解读微信公众平台图文消息的链接组成
微信公众帐号群发的图文消息一般情况下是在微信公众平台上编辑和产生的，个别帐号可以直接推送非微信公众平台的图文消息(现在也很少见了)，而新注册的微信个人帐号被直接绑定的腾讯新闻这种帐号并不是普通的公众帐号，而是微信的一个插件。

我们先从一篇普通的微信公众平台的图文消息看看一篇图文消息链接的组成元素:

昨天，「技术微谈」公众帐号推送了一篇图文消息「Linode Hardware Issue 对传送门造成的问题及解决」，如果你要看到这篇文章，需要访问链接:

http://mp.weixin.qq.com/s?__biz=MzA5Njg3MjAzOA==&mid=201304287&idx=1&sn=02cb223a0e2ef2c238664c3617f04ca8

上面链接中的参数有__biz，mid，idx和sn四个参数，而这四个参数现在能唯一确定一篇微信公众平台的图文消息。

这四个参数的含义是：
__biz可以认为是微信公众平台对外公布的公众帐号的唯一id
mid是图文消息id
idx是发布的第几条消息(1就代表是头条位置消息)
sn是一个随机加密串(对于一篇图文消息是唯一的，如果你想问这个sn的生成规则是什么或者怎么破解，你基本上只能从微信公众平台开发团队才能得到答案)

而这个__biz参数能用来生成公众帐号的二维码，比如「技术微谈」的__biz是MzA5Njg3MjAzOA，那么技术微谈的二维码可以用如下链接生成:

http://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MzA5Njg3MjAzOA==

即可得到「技术微谈」的129x129尺寸的二维码:


而你只需要对上面这个链接改一下size这个参数的值就能得到任意尺寸的二维码图片，比如把size改成500即可得到如下516x516尺寸的二维码:


另外，对于除了__biz之外的三个参数，mid/idx/sn 可以分别写成 appmsgid/itemidx/sign，比如还是之前的这篇文章「Linode Hardware Issue 对传送门造成的问题及解决」，用如下链接一样可以访问到:

http://mp.weixin.qq.com/s?__biz=MzA5Njg3MjAzOA==&appmsgid=201304287&itemidx=1&sign=02cb223a0e2ef2c238664c3617f04ca8

而在早期，大概在一年半以前，只需要__biz, mid 和 idx三个参数即可确定一篇微信公众平台的图文消息:

比如这篇 「小道消息 by Fenng」的文章「业绩考核」的链接是:

http://mp.weixin.qq.com/s?__biz=MjM5ODIyMTE0MA==&mid=10000382&idx=1

微信后来增加一个参数sn(sign)，这样做的原因是:

微信公众平台的图文消息首先在后台保存为了一篇素材才能发布，而这个素材也会生成一个链接，在早期这个素材的链接就是后来要发布的文章的链接，而从上面「业绩考核」这篇文章的链接你能猜出来，只需要改变mid(图文消息id)这个值，比如这篇文章的mid是10000382，对这个数字加上1或者2就极有可能是下一篇图文消息或者素材的链接，而实际上加2之后确实也是一篇文章:「说什么都不对」，链接是：

http://mp.weixin.qq.com/s?__biz=MjM5ODIyMTE0MA==&mid=10000384&idx=1

这样用户就有可能提前阅读到公众帐号已经写好并保存但还没群发的素材了。

今天就分享这些关于微信公众平台图文消息的基础信息，明天我会根据这些基础信息说说一些更有意思的事情，包括微信公众平台最近的一个变动和内在的思路以及将来可能会做的改变。


我的个人微信帐号是Zlexander.
这篇文章写了很久，如果你觉得对你有帮助，请分享到朋友圈或者把技术微谈推荐给朋友。
如需转载，请说明文章转载自技术微谈公众帐号，id是WeTalkTech.