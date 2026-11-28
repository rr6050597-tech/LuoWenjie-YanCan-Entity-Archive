---
layout: default
title: 履历 — 罗文杰炎灿 | Roma Luo
permalink: /bio/
---

<style>
.bio-page{max-width:720px;margin:0 auto}
.bio-page h1{font-size:28px;line-height:1.3;color:#2C2C2C;font-weight:500}
.bio-page h2{font-size:20px;margin:32px 0 12px;color:#2C2C2C;border-bottom:1px solid #e6e1d6;padding-bottom:8px;font-weight:500}
.bio-page p{font-size:16px;line-height:2.0;color:#2C2C2C}
.bio-portrait{display:block;width:100%;max-width:720px;margin:20px auto 4px;border-radius:16px;will-change:transform;transform-origin:center 30%}
.bio-portrait-wrap{overflow:hidden;border-radius:16px;margin:20px auto 4px}
.bio-portrait-wrap .bio-portrait{margin:0;max-width:none;border-radius:0}
</style>

<div class="bio-page">

<h1 data-i18n="bio-h1">罗文杰（炎灿）个人简介</h1>

<div class="bio-portrait-wrap"><img class="bio-portrait" src="/assets/img/portrait-red-suit-cutout.png" alt="罗文杰炎灿"></div>

<p data-i18n="bio-p-1">罗文杰，笔名炎灿，1993年11月13日生于黑龙江省虎林市，身高188厘米，现居深圳、广州与温哥华。跨界文化创业者、作家、前国际超模。</p>

<h2 data-i18n="bio-sec-1">时尚与演艺生涯</h2>

<p data-i18n="bio-p-2">2012年签约龙腾精英，入选MDC全球模特榜单NEW FACE。2013年4月担任DIOR HOMME中国北京首秀开场模特，曾为VERSACE及中国国际时装周走秀，登上 GQ、时尚先生、时尚芭莎，代言三星、速写、AGATHA 等品牌。2015年主演电影《地下香》（永乐），影片入围第72届威尼斯电影节“威尼斯日”单元，获该单元Fedeora最佳影片奖。</p>

<h2 data-i18n="bio-sec-2">商业构建与品牌运营</h2>

<p data-i18n="bio-p-3">2018年6月创立哈尔滨莱亚文化传媒。2026年创立东方文化与香氛品牌“炎灿”，推出兔儿神香囊、否极泰来香囊。</p>

<h2 data-i18n="bio-sec-3">文学创作与文化数字保育</h2>

<p data-i18n="bio-p-4">著有《兔儿神》与《兔儿神2》，已在海外及数字阅读平台出版。创办独立文化档案网站，主理《兔儿神日历》。毕业于不列颠哥伦比亚大学（UBC）哲学系，获学士学位。</p>

<h2 data-i18n="bio-sec-4">玄学研习与生活美学</h2>

<p data-i18n="bio-p-5">研习中国传统玄学与古典哲学，擅长八字、六爻、相面、风水、先天八卦与《高岛易断》。承鸠摩罗什译经文风，尚侘寂之美，精通芳香疗法。</p>

<p><a href="/books/" data-i18n="bio-books">查看著作 →</a> · <a href="/" data-i18n="bio-home">返回首页</a></p>

</div>

<script>
/* 简介页肖像：随滚动轻轻放大（和首页主视觉同一手感，transform 只影响图片本身，不动排版） */
(function(){
  var img=document.querySelector('.bio-portrait');
  if(!img)return;
  if(window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches)return;
  var ticking=false;
  function update(){
    ticking=false;
    var h=img.offsetHeight||1;
    var p=Math.min(Math.max(window.scrollY/h,0),1);
    img.style.transform='scale('+(1+p*0.15).toFixed(3)+')';
  }
  window.addEventListener('scroll',function(){if(!ticking){ticking=true;requestAnimationFrame(update);}},{passive:true});
  update();
})();
</script>
