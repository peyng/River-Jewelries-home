# River-Jewelries-home
<!DOCTYPE html>
<!-- saved from url=(0054)https://naoyu.net/sample/scroll-background-fadein.html -->
<html lang="ja"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Scroll Background Fadein | naoyu.net</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-10603270-10">
</script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-10603270-10');
</script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js">
</script>
<style>
/* init */
.background {
    top: 0;
    left: 0;
    right: 0;
    height: 100%;
    position: fixed;
    background-position: center center;
    opacity: 0;
-webkit-background-size: cover;
        background-size: cover;
-webkit-transition: all 0.5s ease 0s;
   -moz-transition: all 0.5s ease 0s;
        transition: all 0.5s ease 0s;
}
.show .background { opacity: 1;}
.contents .wrap {
    padding: 40vh 0 60vh;
    position: relative;
    z-index: 2;
}
  p {
color: #fffafa;
font-size: 1.5em;
 }
<!--
 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}
 -->
/* design*/
#content01_bg {background-image: url(https://peyng.github.io/2022criterium/20221015criterium.png);}
#content02_bg {background-image: url(https://peyng.github.io/miya_jazz_inn_2021/20211030_005.jpg);}
#content03_bg {background-image: url(https://peyng.github.io/miya_street_gig_2021/20210522038.JPG);}
#content04_bg {background-image: url(https://peyng.github.io/miya_jazz_inn/back.JPG);
<!--
#content05_bg {background-image: url(https://torokoid.github.io/mahoroba/283.JPG);}
#content06_bg {background-image: url(https://torokoid.github.io/mahoroba/454.JPG);}   
#content07_bg {background-image: url(https://torokoid.github.io/mahoroba_2018/20180810_097.JPG);}
#content08_bg {background-image: url(https://torokoid.github.io/mahoroba_2019/20190809_068.JPG);}
-->

/*
#content01 .wrap { background-color: rgba(255,0,0,0.2);}
#content02 .wrap { background-color: rgba(0,255,0,0.2);}
#content03 .wrap { background-color: rgba(0,0,255,0.2);}
#content04 .wrap { background-color: rgba(255,0,0,0.2);}
#content05 .wrap { background-color: rgba(0,255,0,0.2);}
#content06 .wrap { background-color: rgba(0,0,255,0.2);}
#content07 .wrap { background-color: rgba(255,0,0,0.2);}
*/

#content01 .wrap { background-color: rgba(0,0,0,0);}
#content02 .wrap { background-color: rgba(0,0,0,0);}
#content03 .wrap { background-color: rgba(0,0,0,0);}
#content04 .wrap { background-color: rgba(0,0,0,0);}
#content05 .wrap { background-color: rgba(0,0,0,0);}
#content06 .wrap { background-color: rgba(0,0,0,0);}
#content07 .wrap { background-color: rgba(0,0,0,0);}
#content08 .wrap { background-color: rgba(0,0,0,0);}

.text-box {
    padding: 50px 25px;
    max-width: 640px;
    background-color: rgba(0,0,0,0.5);
    color: #fff;
}
#content02 .text-box {
    margin-left: auto;
}
#content04 .text-box {
    margin-left: auto;
}
#content06 .text-box {
    margin-left: auto;
}
#content08 .text-box {
    margin-left: auto;
}
.text-box .catch {
    margin: 0 0 10px;
    font-size: 40px;
}
.text-box .copy {
    margin: 0;
    line-height: 2;
}
a{color: #fff;}
    
</style>
<link rel="preload" href="f.txt" as="script">
    <script type="text/javascript" src="f.txt"></script>
    <link rel="preload" href="f.txt" as="script">
    <script type="text/javascript" src="f.txt"></script>
    <link rel="preload" href="https://pagead2.googlesyndication.com/pagead/js/r20190424/r20190131/show_ads_impl.js" as="script">
    </head>
<body>
<section id="contents">
    <div id="content01" class="contents show">
        <div id="content01_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">わくわくコンサート2022<!--&ensp;&ensp;&ensp;&ensp;<img src="https://torokoid.github.io/fts/QR_mahoroba_home.png" alt="アクセス用QRコード" width="80">--></p>
                <a href="https://peyng.github.io/2022criterium/">わくわくコンサート 2022リンク</a>
            </div>
        </div>
    </div><!-- content01 -->

<section id="contents">
    <div id="content02" class="contents show">
        <div id="content02_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">Miya jazz inn 2021<!--&ensp;&ensp;&ensp;&ensp;<img src="https://torokoid.github.io/fts/QR_mahoroba_home.png" alt="アクセス用QRコード" width="80">--></p>
                <a href="https://peyng.github.io/miya_jazz_inn_2021/">Miya jaza inn 2021リンク</a>
            </div>
        </div>
    </div><!-- content02 -->
    <div id="content03" class="contents">
        <div id="content03_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">Miya street gig 2021<!--&ensp;&ensp;&ensp;&ensp;<img src="https://torokoid.github.io/fts/QR_mahoroba_home.png" alt="アクセス用QRコード" width="80">--></p>
                <a href="https://peyng.github.io/miya_street_gig_2021/">Miya street gig 2021リンク</a>
            </div>
        </div>
    </div><!-- content03 -->
  
    <div id="content04" class="contents">
        <div id="content04_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">Miya jazz inn 2020</p>
                <a href="https://peyng.github.io/miya_jazz_inn/">Miya jazz inn 2020リンク</a>
             </div>
        </div>
    </div><!-- content04 -->
<!--
<div id="content04" class="contents">
        <div id="content04_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">2015年まほろば</p>
                <a href="https://torokoid.github.io/mahoroba_2015/">2015年まほろばHPリンク</a>
             </div>
        </div>
    </div><!-- content04 -->
<!--
<div id="content05" class="contents">
        <div id="content05_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">2016年まほろば</p>
                <a href="https://torokoid.github.io/mahoroba_2016/">2016年まほろばHPリンク</a>
            </div>
        </div> 
    </div><!-- content05 -->
<!--
<div id="content06" class="contents">
        <div id="content06_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">2017年まほろば</p>
                <a href="https://torokoid.github.io/mahoroba_2017/">2017年まほろばHPリンク</a>
            </div>
        </div> 
    </div><!-- content06 -->
<!--
<div id="content07" class="contents">
        <div id="content07_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">2018年まほろば</p>
                <a href="https://torokoid.github.io/mahoroba_2018/">2018年まほろばHPリンク</a>
            </div>
        </div> 
    </div><!-- content07 -->
<!--
<div id="content08" class="contents">
        <div id="content08_bg" class="background"></div>
        <div class="wrap">
            <div class="text-box">
                <p class="catch">2019年まほろば</p>
                <a href="https://torokoid.github.io/mahoroba_2019/">2019年まほろばHPリンク</a>
            </div>
        </div> 
    </div><!-- content08 -->

<!--
                <div class="ad" style="text-align: center;">
                <script async="" src="./Scroll_files/f.txt"></script>
                -->
                <!-- naoyunet sampleページ -->
                <!--
                <ins class="adsbygoogle" style="display: block; height: 59px; width: 640px;" data-ad-client="ca-pub-7408088410773034" data-ad-slot="5732846980" data-ad-format="auto" data-full-width-responsive="true" data-adsbygoogle-status="done"><ins id="aswift_1_expand" style="display: inline-table; border: none; height: 59px; margin: 0px; padding: 0px; position: relative; visibility: visible; width: 640px; background-color: transparent;"><ins id="aswift_1_anchor" style="display: block; border: none; height: 59px; margin: 0px; padding: 0px; position: relative; visibility: visible; width: 640px; background-color: transparent; overflow: hidden;"><iframe width="640" height="59" frameborder="0" marginwidth="0" marginheight="0" vspace="0" hspace="0" allowtransparency="true" scrolling="no" allowfullscreen="true" onload="var i=this.id,s=window.google_iframe_oncopy,H=s&amp;&amp;s.handlers,h=H&amp;&amp;H[i],w=this.contentWindow,d;try{d=w.document}catch(e){}if(h&amp;&amp;d&amp;&amp;(!d.body||!d.body.firstChild)){if(h.call){setTimeout(h,0)}else if(h.match){try{h=s.upd(h,i)}catch(e){}w.location.replace(h)}}" id="aswift_1" name="aswift_1" style="left: 0px; position: absolute; top: 0px; border: 0px; width: 640px; height: 59px;" src="./Scroll_files/saved_resource.html"></iframe></ins></ins></ins>
                -->
                <script>
                (adsbygoogle = window.adsbygoogle || []).push({});
                </script>
                </div>
<!-- フッタ -->
 <footer>
 <span class="white">Copyright 2019/07/07 Torokoid</span>
 </footer>
            </div>
        </div>
    </div>
</section>

<script>
$(function(){
    $('.contents').each(function(i, elem){
        var contentsPOS = $(elem).offset().top;
        $(window).on('load scroll resize', function(){
            var winHeight = $(window).height();
            var scrollTop = $(window).scrollTop();
            var showClass = 'show';
            var timing = 100;
            if (scrollTop >= contentsPOS - winHeight + timing){
              $(elem).addClass(showClass);
            } else {
              $(elem).removeClass(showClass);
            }
        });
    });
});
</script>


<ins class="adsbygoogle adsbygoogle-noablate" data-adsbygoogle-status="done" style="display: none !important;"><ins id="aswift_0_expand" style="display:inline-table;border:none;height:0px;margin:0;padding:0;position:relative;visibility:visible;width:0px;background-color:transparent;"><ins id="aswift_0_anchor" style="display:block;border:none;height:0px;margin:0;padding:0;position:relative;visibility:visible;width:0px;background-color:transparent;"><iframe frameborder="0" marginwidth="0" marginheight="0" vspace="0" hspace="0" allowtransparency="true" scrolling="no" allowfullscreen="true" onload="var i=this.id,s=window.google_iframe_oncopy,H=s&amp;&amp;s.handlers,h=H&amp;&amp;H[i],w=this.contentWindow,d;try{d=w.document}catch(e){}if(h&amp;&amp;d&amp;&amp;(!d.body||!d.body.firstChild)){if(h.call){setTimeout(h,0)}else if(h.match){try{h=s.upd(h,i)}catch(e){}w.location.replace(h)}}" id="aswift_0" name="aswift_0" style="left:0;position:absolute;top:0;border:0px;width:0px;height:0px;" src="./Scroll_files/saved_resource(1).html"></iframe></ins></ins></ins><iframe id="google_osd_static_frame_1872476073822" name="google_osd_static_frame" style="display: none; width: 0px; height: 0px;" src="./Scroll_files/saved_resource(2).html"></iframe></body><iframe id="google_shimpl" style="display: none;" src="./Scroll_files/saved_resource(3).html"></iframe><iframe id="google_esf" name="google_esf" src="./Scroll_files/zrt_lookup.html" data-ad-client="ca-pub-7408088410773034" style="display: none;"></iframe>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script> 
