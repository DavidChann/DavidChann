# 山巅周刊第4期：西部大开发

这里定期分享科技、信息技术、商业、医学及人文资讯，每周日发布。欢迎投稿或推荐线索。

## 封面主题：西部大开发 ##

![20200517_15897440606517.png][1]

2000年开始实施西部大开发政策，四个主要项目西电东送、南水北调工程、西气东输、青藏铁路，除南水北调工程外，均在2010年基本完成。5月17日，中共中央、国务院再发《[关于新时代推进西部大开发形成新格局的指导意见][2]》，政策升级七大方面、三十六条意见。
<!--more-->

----------

## 活动：中国旅游日 ##

<center>![China_Tourism_Day_logo.jpg][3]</center>

中国旅游日于2011年由国务院正式确立，定于每年的5月19日，以纪念《徐霞客游记》开篇之日。今年“中国旅游日”的主题是“文明旅游，健康出行”。

[中国文化旅游网（cnctrip.com）][4]创立于2002年9月“世界旅游日(World Tourism Day)”前夕，当年的“世界旅游日”主题是“经济旅游：可持续发展的关键”。现在，网站转向私域小众话题——G318国道上的生态住家和有机食物。


----------

## 观点：致富与杠杆 ##

![20200519111847.png][5]

美国风险投资家 [Naval Ravikant][6] 在《如何致富，不靠运气》中谈了他的商业观，并详细解释这些观点。参看和菜头翻译的[中文版][7]。

他认为，致富其实只需要两步。

第一步：找到"个人-市场-产品"这三者交叉的那个定位。 你的竞争力在哪里？市场需要的哪一种产品，可以用到你的这种竞争力？这就是你的定位。

![0T6453403-0.png][8]

第二步：使用各种杠杆（leverage），使得你的产品可以服务尽可能大的市场。传统的杠杆是劳动力和资本，互联网时代出现了新的杠杆，就是软件和自媒体。

----------

## 人物：“打工皇帝”唐骏 ##

![8f89a89479be4df9b151600fdd8dde5e.png][9]

唐骏，美籍华人，先后进入微软、盛大、新华都等，并任微软中国总裁、盛大网络总裁、新华都总裁等，因其薪酬较高，曾被称为“打工皇帝”。唐骏自称获加州理工学院计算机科学博士学位（载入蓝狮子财经出版中心策划、中信出版社出版的唐骏自传《我的成功可以复制》，[阮一峰对此事有记述][10]）一事被方舟子挖坟，离开新华都。2016年实际控制港澳资讯，2019年推动创立于2015年的微创网络科创板IPO。

----------

## 技术：如何在网页上显示数学公式 ##

[MathJax][11]是一个跨浏览器的 JavaScript 库，它使用 MathML、TeX 和 ASCIImath 标记在 Web 浏览器中生成 HTML+CSS、SVG 或 MathML 显示数学符号，被认为是使用最广泛的“Beautiful math in all browsers”方案。

![20200515095332.png][12]

在HTML中添加以下代码以使用MathJax版本3

    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

并在HTML中输入MathML标记，并在`$...$`或`$$...$$`分隔符（或`\(...\)`和`\[...\]`）中包装TeX ，在`...`分隔符中包装AsciiMath 。

如[本站主页][13]内文中的公式\\(({16 \\over 9})^2\\)：

![20200514160831.png][14]

在`\(...\)`分隔符中包装TeX代码：

    \(({16 \over 9})^2\)

而在如本站使用的Typecho原生环境中，需要如下代码实现：

    \\(({16 \\over 9})^2\\)

本站显示著名二次方程\\(x = {-b \\pm \\sqrt{b^2-4ac} \\over 2a}\\)的代码：

    \\(x = {-b \\pm \\sqrt{b^2-4ac} \\over 2a}\\)

以及[第51个梅森素数][15]\\({2^{82,589,933}-1}\\)：

    \\({2^{82,589,933}-1}\\)

另外，如 [mathpix.com][16] 一类的软件，可以将数学公式的截图 OCR 转为 LaTex 代码，从而实现印刷、手写类公式的快速数字化。

## 技术：如何使π的数字像这样螺旋状地旋转？ ##

![螺旋π][17]

最美的π螺旋接近阿基米德螺旋线。在[How to make the digits of π go around in a spiral like this?][18]中有讨论这种实现方式。

----------

## 资源：2019-nCoV笔记 ##

![3869033628.jpg][19]

[2019-nCoV笔记][20]是关于2019新型冠状病毒（2019-nCoV）和2019年冠状病毒病（COVID-19）的资料索引，全人肉整理。

----------

## 资讯：疫情下的创新 ##

![bg2020051710.jpg][21]
MineCraft 毕业典礼

5月16日，加州大学伯克利分校为学生在游戏 MineCraft 之中，举行了[虚拟的毕业典礼][22]。只要到时登录游戏，就可以参加典礼了。

游戏中的场景，完全是按照真实校园搭建的，从图书馆到钟楼都有。典礼过程中也会有校长和嘉宾讲话，大家在下面鼓掌，典礼之后是音乐会，整个过程在 Twitch 上直播。

![bg2020051827.jpg][23]
帐篷教室

一家英国设计工作室提出了"[帐篷教室][24]"的设计，帮助学校搭建室外的帐篷作为教室，一方面利用新鲜空气减少病毒传播，另一方面也可以增大空间保持社交距离。

英国学校每个班的人数较少，在帐篷里面，可以达到每个学生间隔2米。

![9604-isqivxf5769903.jpg][25]
Zoom远程会议

新冠病毒大流行让原本在企业世界偏安一隅的Zoom成为社交互动的新宠，为增加会议的有趣程度，在北卡罗来纳州[Peace N Peas农场][26]经营的网站设计工作室Peace N Peas Web Solutions，用户能以50美元10分钟的价格租赁一头明星驴子[Mambo][27]加入你的视频会议中，此外你还可以租用Eddie（白马）、鸭子和鸡等农场动物。

![20200522115551.png][28]
威尼斯直播

现在，意大利威尼斯的[Hotel American Dinesen][29]已经没有了生意，就在[Youtube][30]直播它的窗口望出去的景象，有好几个摄像头轮流切换，画面相当清晰。

直播中多个摄像头轮播一遍后会显示文字："等到疫情结束，请预订您的行程，帮帮这个城市"。

![bg2020042611.jpg][31]
千年磨坊恢复生产

英国由于疫情造成了供应链中断，面粉供应紧张。英格兰多塞特郡一家1000年历史的磨坊[Sturminster Newton Mill][32]，重新开始使用水力生产面粉，运行10天，磨了一吨小麦。

![5ec7e1f6aee6a8433f1667d5.jpg][33]
[社会距离之冠][34]

Burger King 汉堡王在德国推出了 Social Distancing 帽子，帮顾客保持 6 英尺距离。

![bg2020032702.jpg][35]
远程教育

3月5日，米兰一位大学教授对着空教室远程讲课。不过真不建议教育者们效仿出一屏笑话，浏览 [3Brown1Blue][36] 和 [Kurzgesagt][37] 的范例可以感受一下吸引人的网课是什么风格。

----------

## 事件：比特币区块奖励减半 ##

5月12日，比特币迎来四年一期的比特币区块奖励减半，在区块高度 631008 完成减半，矿工每创建一个区块的比特币挖矿奖励将从12.5枚降至6.25枚。比特币第一次减半是在2012年11月，当时挖矿的回报从50个比特币减至25个，第二次减半是在2016年7月，回报进一步减至12.5个比特币。

![bg2020051206.jpg][38]

俄罗斯西伯利亚布拉茨克水坝长1.43公里，高125米。1971年之前，它是世界最大的发电厂，装机容量达到4,500兆瓦。以前的一个旧厂房里面，现在运行着大约25000台矿机。

四川电力交易中心曾于4月21日公布[2020年第一批水电消纳示范企业名单][39]，共99家企业，包括小金县科迪大数据存储科技有限责任公司、黑水科迪大数据科技有限公司、马尔康科迪科技有限公司、康定智通互链科技有限公司、成都无极链科技有限公司康定分公司等多个矿场在列。

矿机厂商方面的消息是，最大的三家加密货币挖矿机制造商比特大陆陷入宫斗、嘉楠科技巨亏和亿邦国际拟赴美上市。

## 鸣谢

![中国汽车绞盘网][100]

山巅周刊得到[中国汽车绞盘网][101]的帮助，深表感谢。

中国汽车绞盘网业务始创于2001年，提供各型绞盘产品和技术支持。

  [1]: http://3.14159.icu/usr/uploads/2020/05/156595256.png
  [2]: http://www.gov.cn/zhengce/2020-05/17/content_5512456.htm
  [3]: http://3.14159.icu/usr/uploads/2020/05/3823713239.jpg
  [4]: http://www.cnctrip.com/
  [5]: http://3.14159.icu/usr/uploads/2020/05/2655760181.png
  [6]: https://nav.al/
  [7]: https://new.qq.com/omn/20200413/20200413A0U72C00.html
  [8]: http://3.14159.icu/usr/uploads/2020/05/655552105.png
  [9]: http://3.14159.icu/usr/uploads/2020/05/969511438.png
  [10]: http://www.ruanyifeng.com/blog/2010/07/what_the_blue_lion_publishing_house_is_like.html
  [11]: https://www.mathjax.org/
  [12]: http://3.14159.icu/usr/uploads/2020/05/2101064657.png
  [13]: http://3.14159.icu/
  [14]: http://3.14159.icu/usr/uploads/2020/05/3264491446.png
  [15]: http://3.14159.icu/Notes/983.html
  [16]: https://mathpix.com/
  [17]: http://3.14159.icu/usr/uploads/2020/05/4234727368.png
  [18]: https://mathematica.stackexchange.com/questions/109982/how-to-make-the-digits-of-%CF%80-go-around-in-a-spiral-like-this
  [19]: http://3.14159.icu/usr/uploads/2020/05/960648036.jpg
  [20]: http://thailycare.com/2019-nCoV/
  [21]: http://3.14159.icu/usr/uploads/2020/05/3195419709.jpg
  [22]: https://www.blockeley.com/
  [23]: http://3.14159.icu/usr/uploads/2020/05/2508116794.jpg
  [24]: https://www.dezeen.com/2020/05/13/curl-la-tourelle-head-tent-classrooms-social-distancing-school/
  [25]: http://3.14159.icu/usr/uploads/2020/05/2333135755.jpg
  [26]: https://peacenpeasfarm.com/
  [27]: https://dangrooster.com/
  [28]: http://3.14159.icu/usr/uploads/2020/05/2388889646.png
  [29]: https://www.hotelamerican.it/
  [30]: https://www.youtube.com/watch?v=ph1vpnYIxJk
  [31]: http://3.14159.icu/usr/uploads/2020/05/2876369445.jpg
  [32]: https://sturminsternewton-museum.co.uk/mill/
  [33]: http://3.14159.icu/usr/uploads/2020/05/2173174800.jpg
  [34]: https://www.businessinsider.com/burger-king-debuts-social-distancing-crowns-in-germany-2020-5
  [35]: http://3.14159.icu/usr/uploads/2020/05/3060716777.jpg
  [36]: https://www.youtube.com/c/3blue1brown/
  [37]: https://www.youtube.com/user/Kurzgesagt/
  [38]: http://3.14159.icu/usr/uploads/2020/05/1796104255.jpg
  [39]: http://shoudian.bjx.com.cn/html/20200422/1065587.shtml
  [100]: https://raw.githubusercontent.com/iwiran/Pi/main/weekly/images/mywinch.png
  [101]: http://www.mywinch.com/
