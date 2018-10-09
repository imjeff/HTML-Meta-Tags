# HTML Meta Tags
HTML Meta 标签搜集，部分标签已加中文说明，欢迎补全。

## 基础 HTML Meta 标签

``` html
<!-- 声明文档使用的字符编码 -->
<meta charset="utf-8">
<!-- 页面描述 -->
<meta name="description" content="不超过150个字符">
<!-- 页面关键词 -->
<meta name="keywords" content="你的, 关键词">
<meta name="subject" content="your website's subject">
<meta name="copyright" content="company name">
<meta name="language" content="ES">
<!-- 搜索引擎抓取 -->
<meta name="robots" content="index,follow">
<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm">
<meta name="abstract" content="">
<meta name="topic" content="">
<meta name="summary" content="">
<meta name="Classification" content="Business">
<!-- 网页作者 -->
<meta name="author" content="name, email@gmail.com">
<!-- 网页设计师 -->
<meta name="designer" content="">
<!-- 网页制作软件 -->
<meta name="generator" content="VS Code">
<meta name="reply-to" content="email@gmail.com">
<meta name="owner" content="Jeff Design">
<meta name="url" content="http://www.jeffdesign.net">
<meta name="identifier-URL" content="http://www.websiteaddress.com">
<meta name="directory" content="submission">
<meta name="pagename" content="jQuery Tools, Tutorials and Resources - O'Reilly Media">
<meta name="category" content="">
<meta name="coverage" content="Worldwide">
<meta name="distribution" content="Global">
<meta name="rating" content="General">
<!-- 搜索引擎爬虫重访时间 -->
<meta name="revisit-after" content="7 days">
<meta name="subtitle" content="This is my subtitle">
<meta name="target" content="all">
<meta name="HandheldFriendly" content="True">
<meta name="MobileOptimized" content="320">
<meta name="date" content="Sep. 27, 2010">
<meta name="search_date" content="2010-09-27">
<meta name="DC.title" content="Unstoppable Robot Ninja">
<meta name="ResourceLoaderDynamicStyles" content="">
<meta name="medium" content="blog">
<meta name="syndication-source" content="https://www.example.com/2018/12/24/free-brand-monitoring-tools/">
<meta name="original-source" content="https://www.example.com/2018/12/24/free-brand-monitoring-tools/">
<meta name="verify-v1" content="dV1r/ZJJdDEI++fKJ6iDEl6o+TMNtSu0kv18ONeqM0I=">
<meta name="y_key" content="1e39c508e0d87750">
<meta name="pageKey" content="guest-home">
<meta itemprop="name" content="jQTouch">
<meta http-equiv="Expires" content="0">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Cache-Control" content="no-cache">
<meta http-equiv="imagetoolbar" content="no">
<meta http-equiv="x-dns-prefetch-control" content="off">
<!-- 为移动设备添加 viewport -->
<!-- 
width：控制 viewport 的大小，可以指定的一个值，如 600，或者特殊的值，如 device-width 为设备的宽度（单位为缩放为 100% 时的 CSS 的像素）。  
height：和 width 相对应，指定高度。  
initial-scale：初始缩放比例，也即是当页面第一次 load 的时候缩放比例。  
maximum-scale：允许用户缩放到的最大比例。  
minimum-scale：允许用户缩放到的最小比例。  
user-scalable：用户是否可以手动缩放。 
-->
<meta name="viewport" content="initial-scale=1, maximum-scale=3, minimum-scale=1, user-scalable=no">
```

## 公司/服务专用 Meta 标签

#### Apple Meta 标签

``` html
<!-- 添加到主屏后的标题（iOS 6 新增） -->
<meta name="apple-mobile-web-app-title" content="My App">
<!-- 是否启用 WebApp 全屏模式，删除苹果默认的工具栏和菜单栏 -->
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-touch-fullscreen" content="yes">
<!-- 设置苹果工具栏颜色 -->
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="format-detection" content="telephone=no">
<meta name="viewport" content="width=device-width; width = 320; initial-scale=1.0; maximum-scale=1.0; user-scalable=yes; target-densitydpi=160dpi">
<!-- 添加智能 App 广告条 Smart App Banner（iOS 6+ Safari） -->
<meta name="apple-itunes-app" content="app-id=myAppStoreID, affiliate-data=myAffiliateData, app-argument=myURL">

<link href="/apple-touch-icon.png" rel="apple-touch-icon" type="image/png">
<link href="touch-icon-ipad.png" rel="apple-touch-icon" sizes="72x72">
<link href="touch-icon-iphone4.png" rel="apple-touch-icon" sizes="114x114">
<link href="/startup.png" rel="apple-touch-startup-image">

<!-- Safari 9 Pinned tabs in El Capitan -->
<link rel="mask-icon" href="website_icon.svg" color="red">

<!-- iPhone 和 iTouch，默认 57x57 像素，必须有 -->
<link rel="apple-touch-icon-precomposed" href="/apple-touch-icon-57x57-precomposed.png"/>
<!-- Retina iPhone 和 Retina iTouch，72x72 像素，可以没有，但推荐有 -->
<link rel="apple-touch-icon-precomposed" sizes="72x72" href="/apple-touch-icon-72x72-precomposed.png"/>
<!-- Retina iPad，144x144 像素，可以没有，但推荐有 -->
<link rel="apple-touch-icon-precomposed" sizes="144x144" href="/apple-touch-icon-144x144-precomposed.png"/>

<!-- iPad 竖屏 768 x 1004（标准分辨率） -->
<link rel="apple-touch-startup-image" sizes="768x1004" href="/splash-screen-768x1004.png"/>
<!-- iPad 竖屏 1536x2008（Retina） -->
<link rel="apple-touch-startup-image" sizes="1536x2008" href="/splash-screen-1536x2008.png"/>
<!-- iPad 横屏 1024x748（标准分辨率） -->
<link rel="apple-touch-startup-image" sizes="1024x748" href="/Default-Portrait-1024x748.png"/>
<!-- iPad 横屏 2048x1496（Retina） -->
<link rel="apple-touch-startup-image" sizes="2048x1496" href="/splash-screen-2048x1496.png"/>
<!-- iPhone/iPod Touch 竖屏 320x480 (标准分辨率) -->
<link rel="apple-touch-startup-image" href="/splash-screen-320x480.png"/>
<!-- iPhone/iPod Touch 竖屏 640x960 (Retina) -->
<link rel="apple-touch-startup-image" sizes="640x960" href="/splash-screen-640x960.png"/>
<!-- iPhone 5/iPod Touch 5 竖屏 640x1136 (Retina) -->
<link rel="apple-touch-startup-image" sizes="640x1136" href="/splash-screen-640x1136.png"/>
```


#### Internet Explorer Meta 标签

``` html
<meta http-equiv="Page-Enter" content="RevealTrans(Duration=2.0,Transition=2)">
<meta http-equiv="Page-Exit" content="RevealTrans(Duration=3.0,Transition=12)">
<meta name="mssmarttagspreventparsing" content="true">
<!-- 优先使用 IE 最新版本和 Chrome -->
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<meta name="msapplication-starturl" content="http://www.yourwebsite.com/">
<meta name="msapplication-window" content="width=800;height=600">
<meta name="msapplication-navbutton-color" content="red">
<meta name="application-name" content="Rey Bango Front-end Developer">
<meta name="msapplication-tooltip" content="Launch Rey Bango's Blog">
<meta name="msapplication-task" content="name=About;action-uri=/about/;icon-uri=/images/about.ico">
<meta name="msapplication-task" content="name=The Big List;action-uri=/the-big-list-of-javascript-css-and-html-development-tools-libraries-projects-and-books/;icon-uri=/images/list_links.ico">
<meta name="msapplication-task" content="name=jQuery Posts;action-uri=/category/jquery/;icon-uri=/images/jquery.ico">
<meta name="msapplication-task" content="name=Start Developing;action-uri=/category/javascript/;icon-uri=/images/script.ico">
<meta name="msvalidate.01" content="6E3AD52DC176461A3C81DD6E98003BC9">
<meta http-equiv="cleartype" content="on">
<!-- 忽略页面中的数字识别为电话，忽略email识别 -->
<meta name="format-detection" content="telphone=no, email=no"/>
<!-- 双核浏览器渲染方式 -->
<!-- 默认webkit内核 -->
<meta name="renderer" content="webkit">
<!-- 默认IE兼容模式 -->
<meta name="renderer" content="ie-comp">
<!-- 默认IE标准模式 -->
<meta name="renderer" content="ie-stand">
<!-- 避免IE使用兼容模式 -->
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<!-- 不让百度转码 -->
<meta http-equiv="Cache-Control" content="no-siteapp" />
<!-- 针对手持设备优化，主要是针对一些老的不识别viewport的浏览器，比如黑莓 -->
<meta name="HandheldFriendly" content="true">
<!-- 微软的老式浏览器 -->
<meta name="MobileOptimized" content="320">
<!-- uc强制竖屏 -->
<meta name="screen-orientation" content="portrait">
<!-- QQ强制竖屏 -->
<meta name="x5-orientation" content="portrait">
<!-- UC强制全屏 -->
<meta name="full-screen" content="yes">
<!-- QQ强制全屏 -->
<meta name="x5-fullscreen" content="true">
<!-- UC应用模式 -->
<meta name="browsermode" content="application">
<!-- QQ应用模式 -->
<meta name="x5-page-mode" content="app">
<!-- windows phone 点击无高光 -->
<meta name="msapplication-tap-highlight" content="no">
```

#### Windows 8 Meta 标签

``` html
<meta name="application-name" content=" Contoso" />
<!-- Windows 8 磁贴颜色 -->
<meta name="msapplication-TileColor" content=" #009900" />
<!-- Windows 8 磁贴图标 -->
<meta name="msapplication-TileImage" content="icon.png"/>
<meta name="msapplication-square70x70logo" content="images/smalltile.png" />
<meta name="msapplication-square150x150logo" content="images/mediumtile.png" />
<meta name="msapplication-wide310x150logo" content="images/widetile.png" />
<meta name="msapplication-square310x310logo" content="images/largetile.png" />
<meta name="msapplication-notification" content="frequency=30; polling-uri=notifications/contoso1.xml;
polling-uri2=notifications/contoso2.xml; polling-uri3=notifications/contoso3.xml" />
```

#### TweetMeme Meta 标签

``` html
<meta name="tweetmeme-title" content="Retweet Button Explained">
```

#### Blog Catalog Meta 标签

``` html
<meta name="blogcatalog">
```

#### Rails Meta 标签

``` html
<meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="/bZVwvomkAnwAI1Qd37lFeewvpOIiackk9121fFwWwc=">
```

#### ClaimID Meta 标签

``` html
<meta name="microid" content="mailto+http:sha1:e6058ed7fca4a1921cq91d7f1f3b8736cd3cc1g7">
<meta name="readability-verification" content="E7aEHvVQpWc8VHDqKvaB2Z58hek2EAv2HuLuegv7">
<meta name="google-site-verification" content="4SMIedO1X4IkYrYuhEC2VuovdQM36Xxb0btUjElqQyg">
<meta name="ICBM" content="40.746990, -73.980537">
<meta name="generator" content="WordPress 3.3.1">
<meta name="norton-safeweb-site-verification" content="tz8iotmk-pkhui406y41y5bfmfxdwmaa4a-yc0hm6r0fga7s6j0j27qmgqkmc7oovihzghbzhbdjk-uiyrz438nxsjdbj3fggwgl8oq2nf4ko8gi7j4z7t78kegbidl4">
```

## HTML 链接类标签

``` html
 <!-- 添加 RSS 订阅 -->
<link rel="alternate" type="application/rss+xml" title="RSS" href="https://example.com/feed.atom">
<link rel="alternate" type="application/atom+xml" title="Atom 0.3" href="https://example.com/feed.atom">
<!-- 添加 favicon icon -->
<link rel="shortcut icon" type="image/ico" href="/favicon.ico">
<link rel="fluid-icon" type="image/png" href="/fluid-icon.png">
<link rel="me" type="text/html" href="http://google.com/profiles/thenextweb">
<link rel="shortlink" href="http://www.example.com/?p=353">
<link rel="archives" title="May 2003" href="http://www.example.com/2003/05/">
<link rel="index" title="DeWitt Clinton" href="http://www.example.com/">
<link rel="start" title="Pattern Recognition 1" href="http://www.example.com/photos/pattern_recognition_1_about/">
<link rel="bookmark'title="Styleguide" href="http://www.example.com/about/styleguide/">
<link rel="search" href="/search.xml" type="application/opensearchdescription+xml" title="Viatropos">

<link rel="self" type="application/atom+xml" href="http://www.example.com/atomFeed.php?page=3">
<link rel="first" href="http://www.example.com/atomFeed.php">
<link rel="next" href="http://www.example.com/atomFeed.php?page=4">
<link rel="previous" href="http://www.example.com/atomFeed.php?page=2">
<link rel="last" href="http://www.example.com/atomFeed.php?page=147">

<link rel="canonical" href="http://www.example.com/2010/06/9-things-to-do-before-entering-social-media.html">
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="http://www.example.com/xmlrpc.php?rsd">
<link rel="pingback" href="http://www.example.com/xmlrpc.php">
<link rel="stylesheet" media="only screen and (max-device-width: 480px)" href="http://wordpress.org/style/iphone.css" type="text/css">
<link rel="wlwmanifest" href="http://www.example.com/wp-includes/wlwmanifest.xml" type="application/wlwmanifest+xml">

<link rel="help" title="FAQ" href="/faq">
<link rel="logo" type="image/svg" href="https://playfoursquare.s3.amazonaws.com/press/logo/foursquare-logo.svg">
<link rel="P3Pv1" href="/w3c/p3p.xml">
<link rel="publisher" href="https://plus.google.com/115081025762845243709/">
<link rel="image_src" href="http://du3itj18e4z0b.cloudfront.net/7b29fe/images/icon-facebook.gif" type="image/jpeg">

<link rel="author" href="humans.txt" type="text/plain">
<link href="http://thenextweb.com/2009/01/08/how-to-snap-up-that-twitter-username-youve-always-wanted/" rel="original-source">
<link rel="profile" title="Microformats" href="http://microformats.org/profile/specs/">
<link rel="profile" href="http://gmpg.org/xfn/11">
```

## OpenGraph Meta 标签

``` html
<!-- SNS 开放内容协议 (Open Graph Protocol) -->
<meta name="og:title" content="The Rock">
<meta name="og:type" content="movie">
<meta name="og:url" content="http://www.imdb.com/title/tt0117500/">
<meta name="og:image" content="http://ia.media-imdb.com/rock.jpg">
<meta name="og:site_name" content="IMDb">
<meta name="og:description" content="A group of U.S. Marines, under command of...">
<meta name="fb:page_id" content="43929265776">
<meta name="application-name" content="foursquare">
<meta name="og:email" content="me@example.com">
<meta name="og:phone_number" content="650-123-4567">
<meta name="og:fax_number" content="+1-415-123-4567">
<meta name="og:latitude" content="37.416343">
<meta name="og:longitude" content="-122.153013">
<meta name="og:street-address" content="1601 S California Ave">
<meta name="og:locality" content="Palo Alto">
<meta name="og:region" content="CA">
<meta name="og:postal-code" content="94304">
<meta name="og:country-name" content="USA">
<meta property="fb:admins" content="987654321">
<meta property="og:type" content="game.achievement">
<meta property="og:points" content="POINTS_FOR_ACHIEVEMENT">
<meta property="og:video" content="http://example.com/awesome.swf">
<meta property="og:video:height" content="640">
<meta property="og:video:width" content="385">
<meta property="og:video:type" content="application/x-shockwave-flash">
<meta property="og:video" content="http://example.com/html5.mp4">
<meta property="og:video:type" content="video/mp4">
<meta property="og:video" content="http://example.com/fallback.vid">
<meta property="og:video:type" content="text/html">
<meta property="og:audio" content="http://example.com/amazing.mp3">
<meta property="og:audio:title" content="Amazing Song">
<meta property="og:audio:artist" content="Amazing Band">
<meta property="og:audio:album" content="Amazing Album">
<meta property="og:audio:type" content="application/mp3">
```


## 参考资源

- [HTML5 Boilerplate explanations and suggestions of header tags](http://html5boilerplate.com/docs/head-Tips/)
- [Dublic Core Meta Tags](http://www.seoconsultants.com/meta-tags/dublin/)
- [Apple Meta Tags](http://developer.apple.com/safari/library/documentation/appleapplications/reference/safarihtmlref/articles/metatags.html)
- [Link Tag Meaning](http://intertwingly.net/wiki/pie/LinkTagMeaning)
- [Google Chrome HTML5 Tags](http://www.html5rocks.com/)
