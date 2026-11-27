---
layout: default
title: 罗文杰炎灿 | Roma Luo
permalink: /
---

<style>
.home{max-width:760px;margin:0 auto}
/* —— 第一屏：品牌视觉（黑白肖像全幅） —— */
.hero-full{position:relative;margin:0 -24px;padding:0;background:#F7F5F0;border:1px solid #e6e1d6;border-radius:28px;overflow:hidden;box-shadow:0 10px 32px rgba(44,44,44,.08)}
.hero-full .hero-img{display:block;width:100%;height:62vh;min-height:400px;object-fit:cover;object-position:center 18%;will-change:transform}
.hero-full .hero-veil{position:absolute;inset:0;background:linear-gradient(180deg,rgba(255,255,255,0) 0%,rgba(255,255,255,.06) 45%,rgba(255,255,255,.78) 100%)}
.hero-full .hero-copy{position:absolute;left:0;right:0;bottom:0;padding:0 24px 34px;color:#2C2C2C;text-align:center}
.hero-full .hero-copy .hero-en{font-size:15px;letter-spacing:.5em;text-transform:uppercase;color:#2C2C2C;margin:0 0 10px;text-indent:.5em}
.hero-full .hero-copy h1{font-family:"Songti SC","Noto Serif SC",serif;font-size:46px;line-height:1.15;letter-spacing:.16em;margin:0 0 10px;color:#2C2C2C;font-weight:500}
.hero-full .hero-copy .hero-roles{font-size:15px;letter-spacing:.18em;color:#55524a;margin:0 0 8px}
.hero-full .hero-copy .hero-tag{font-size:15px;letter-spacing:.32em;color:#C5A059;margin:0}
@media (max-width:560px){.hero-full .hero-copy h1{font-size:38px}}
/* —— 第二屏：宣言 —— */
.manifesto{text-align:center;padding:64px 24px 58px}
.manifesto p{font-family:"Songti SC","Noto Serif SC",serif;font-size:22px;line-height:2.1;color:#2C2C2C;margin:0}
.manifesto .m-rule{width:48px;height:2px;background:#C5A059;border:0;margin:28px auto 0}
/* —— 通用小节 —— */
.home-sec{font-family:"Songti SC","Noto Serif SC",serif;font-size:23px;margin:52px 0 6px;color:#2C2C2C;font-weight:500}
.home-sec-sub{font-size:14px;color:#8a8578;margin:0 0 18px}
.home-sec .no{color:#C5A059;font-size:14px;letter-spacing:.2em;margin-right:12px}
/* —— 四大体系 —— */
.sys-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media (max-width:560px){.sys-grid{grid-template-columns:1fr}}
.sys-card{display:block;text-decoration:none;color:#F7F5F0;border:1px solid rgba(255,255,255,.22);background:rgba(44,44,44,.78);backdrop-filter:blur(20px) saturate(1.3);-webkit-backdrop-filter:blur(20px) saturate(1.3);padding:22px 20px 18px;border-radius:16px;box-shadow:0 8px 24px rgba(44,44,44,.10),inset 0 1px 0 rgba(255,255,255,.18),inset 0 -1px 0 rgba(255,255,255,.06)}
.sys-card.sys-red{background:rgba(110,27,27,.72);border-color:rgba(255,255,255,.22)}
.sys-card.sys-gold{background:#F7F5F0;color:#2C2C2C;border-color:#e6e1d6}
.sys-card .sys-en{font-size:11px;letter-spacing:.32em;text-transform:uppercase;color:#C5A059;margin:0 0 8px}
.sys-card.sys-gold .sys-en{color:#C5A059}
.sys-card .sys-title{font-family:"Songti SC","Noto Serif SC",serif;font-size:21px;margin:0 0 8px;font-weight:500}
.sys-card .sys-desc{font-size:14px;line-height:2.0;color:#cfc9bd;margin:0}
.sys-card.sys-gold .sys-desc{color:#55524a}
.sys-card .sys-meta{font-size:13px;color:#a39d8f;margin:12px 0 0}
.sys-card.sys-gold .sys-meta{color:#8a8578}
.sys-card .sys-arrow{color:#C5A059}
/* —— 精选作品 —— */
.works-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(150px,1fr));gap:16px}
.work-card{display:block;text-decoration:none;color:#2C2C2C}
.work-card-img{width:100%;height:auto;display:block;border:1px solid #e6e1d6;background:#F7F5F0;aspect-ratio:2/3;object-fit:cover;border-radius:8px;box-shadow:0 2px 10px rgba(44,44,44,.08)}
.work-card-dark{position:relative;display:flex;flex-direction:column;justify-content:flex-end;aspect-ratio:2/3;overflow:hidden;background:#2C2C2C;color:#F7F5F0;border:1px solid #2C2C2C;border-radius:12px}
.work-card-dark>img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.work-card-dark .wk-text{position:relative;z-index:1;width:100%;padding:16px 14px;background:linear-gradient(to top,rgba(0,0,0,.62),rgba(0,0,0,0))}
.work-card-dark.work-red{background:#6E1B1B;border-color:#6E1B1B}
.work-card-dark .wk-en{font-size:10px;letter-spacing:.28em;text-transform:uppercase;color:#C5A059;margin:0 0 8px}
.work-card-dark .wk-title{font-family:"Songti SC","Noto Serif SC",serif;font-size:19px;line-height:1.4;margin:0 0 6px;font-weight:500}
.work-card-dark .wk-desc{font-size:13px;line-height:2.0;color:#cfc9bd;margin:0}
.work-card-title{display:block;font-size:15px;margin-top:8px;line-height:1.5}
.work-card-meta{display:block;font-size:13px;color:#8a8578;margin-top:2px}
/* —— 时间轴 —— */
.timeline{margin:8px 0 0;padding-left:18px;border-left:1px solid #e6e1d6}
.tl-item{position:relative;padding:0 0 22px 18px}
.tl-item::before{content:"";position:absolute;left:-23px;top:7px;width:9px;height:9px;border-radius:50%;background:#C5A059;border:2px solid #F7F5F0}
.tl-item .tl-year{font-family:"Songti SC","Noto Serif SC",serif;font-size:18px;color:#2C2C2C;margin:0 0 4px;font-weight:500}
.tl-item .tl-text{font-size:15px;line-height:2.0;color:#55524a;margin:0}
.tl-item .tl-text b{color:#2C2C2C}
/* —— 香氛 —— */
.home-products{font-size:15px;line-height:1.9;color:#2C2C2C}
.home-products .prod{border:1px solid #e6e1d6;padding:14px 16px;margin:10px 0;background:#F7F5F0;border-radius:16px}
.home-products .prod b{color:#2C2C2C}
.home-products .prod img{display:block;width:100%;max-width:420px;margin:0 auto 10px;border:1px solid #e6e1d6;background:#fff;border-radius:8px;box-shadow:0 2px 10px rgba(44,44,44,.08)}
/* —— 商务合作 —— */
.biz-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media (max-width:560px){.biz-grid{grid-template-columns:1fr}}
.biz-card{display:block;text-decoration:none;color:#2C2C2C;border:1px solid #e6e1d6;background:#F7F5F0;padding:20px 18px;border-radius:16px}
.biz-card:hover{border-color:#C5A059}
.biz-card .biz-en{font-size:11px;letter-spacing:.32em;text-transform:uppercase;color:#C5A059;margin:0 0 8px}
.biz-card .biz-title{font-family:"Songti SC","Noto Serif SC",serif;font-size:19px;margin:0 0 6px;font-weight:500}
.biz-card .biz-desc{font-size:14px;line-height:2.0;color:#55524a;margin:0}
/* —— 页脚：仅留“档案”小字入口 —— */
.home-foot{margin:56px 0 8px;text-align:center;font-size:13px;color:#a39d8f}
.home-foot a{color:#a39d8f;text-decoration:underline}
</style>

<div class="home">

<div class="hero-full">
  <img class="hero-img" src="/assets/img/portrait-white-cutout.png" alt="罗文杰炎灿">
  <div class="hero-veil"></div>
  <div class="hero-copy">
    <p class="hero-en">Roma Luo</p>
    <h1>罗文杰炎灿</h1>
  </div>
</div>

<div class="manifesto">
  <p data-i18n="home-manifesto"><span class="m-line">以文字记录思想，</span><span class="m-line">以影像记录时代，</span><br class="m-br"><span class="m-line">以文化探索生命，</span><span class="m-line">以气味连接记忆。</span></p>
  <hr class="m-rule">
</div>

<h2 class="home-sec" data-i18n="home-sec-systems">四大体系</h2>
<div class="sys-grid">
  <a class="sys-card" href="/works/film/">
    <p class="sys-en">01 · Fashion &amp; Performing Arts</p>
    <p class="sys-title" data-i18n="sys-1-title">ROMA LUO 时尚与演艺</p>
    <p class="sys-desc" data-i18n="sys-1-desc">DIOR HOMME 首秀开场、VERSACE、GQ、时装周，电影《地下香》。</p>
  </a>
  <a class="sys-card sys-red" href="/books/">
    <p class="sys-en">02 · Literature &amp; Publishing</p>
    <p class="sys-title" data-i18n="sys-2-title">ROMA LUO 文学与出版</p>
    <p class="sys-desc" data-i18n="sys-2-desc">《兔儿神》系列与《与兔儿神对话》。</p>
  </a>
  <a class="sys-card sys-gold" href="/books/">
    <p class="sys-en">03 · Roma Luo Lecture Series</p>
    <p class="sys-title" data-i18n="sys-3-title">罗文杰讲系列</p>
    <p class="sys-desc" data-i18n="sys-3-desc">已出版 · 《罗文杰讲高岛易断》《罗文杰讲药师经》<br>已完稿 · 《罗文杰讲萨满》（三卷）《罗文杰讲显化》<br>撰写中 · 《罗文杰讲神道教》</p>
  </a>
  <a class="sys-card" href="#fragrance">
    <p class="sys-en">04 · Yancan Fragrance</p>
    <p class="sys-title" data-i18n="sys-4-title">炎灿 YANCAN 东方香氛</p>
    <p class="sys-desc" data-i18n="sys-4-desc">兔儿神香囊、妲己香囊、米缸香囊。</p>
  </a>
</div>

<h2 class="home-sec" data-i18n="home-sec-works">精选作品</h2>
<div class="works-grid">
  <a class="work-card" href="/works/magazine/">
    <div class="work-card-dark">
      <img src="/visual_assets/fashion-flash/fashion-flash-05.jpg" alt="罗文杰炎灿时尚大片" loading="lazy" decoding="async">
      <div class="wk-text">
        <p class="wk-en">Fashion Editorial</p>
        <p class="wk-title" data-i18n="wk-fashion-title">个人时尚大片</p>
      </div>
    </div>
    <span class="work-card-title" data-i18n="wk-fashion-name">时尚大片</span>
  </a>
  <a class="work-card" href="/works/film/">
    <div class="work-card-dark work-red">
      <img src="/visual_assets/venice-2015/luo-wenjie-underground-fragrance-film-still.jpg" alt="电影《地下香》剧照" loading="lazy" decoding="async">
      <div class="wk-text">
        <p class="wk-en">Film</p>
        <p class="wk-title" data-i18n="wk-film-title">电影《地下香》</p>
      </div>
    </div>
    <span class="work-card-title">《地下香》</span>
  </a>
  {% assign _g1 = site.data.books | where: "id", "gaodao-yiduan" | first %}
  {% include book-card.html book=_g1 %}
  {% assign _y1 = site.data.books | where: "id", "yaoshijing" | first %}
  {% include book-card.html book=_y1 %}
  {% assign _t1 = site.data.books | where: "id", "tu-er-shen" | first %}
  {% include book-card.html book=_t1 %}
  <a class="work-card" href="#fragrance">
    <div class="work-card-dark">
      <img src="/assets/products/sachet-tuershen.jpg" alt="炎灿兔儿神香囊" loading="lazy" decoding="async">
      <div class="wk-text">
        <p class="wk-en">Yancan Fragrance</p>
        <p class="wk-title" data-i18n="wk-fragrance-title">炎灿香氛</p>
      </div>
    </div>
    <span class="work-card-title" data-i18n="wk-fragrance-name">炎灿香氛</span>
  </a>
</div>

<h2 class="home-sec" data-i18n="home-sec-bio">个人档案</h2>
<div class="timeline">
  <div class="tl-item">
    <p class="tl-year">2012</p>
    <p class="tl-text" data-i18n="tl-2012">签约龙腾精英，入选 MDC NEW FACE。</p>
  </div>
  <div class="tl-item">
    <p class="tl-year">2013</p>
    <p class="tl-text" data-i18n="tl-2013">DIOR HOMME 中国北京首秀开场模特。</p>
  </div>
  <div class="tl-item">
    <p class="tl-year">2015</p>
    <p class="tl-text" data-i18n="tl-2015">主演《地下香》，威尼斯日 Fedeora 最佳影片奖。</p>
  </div>
  <div class="tl-item">
    <p class="tl-year">2018</p>
    <p class="tl-text" data-i18n="tl-2018">创立哈尔滨莱亚文化传媒。</p>
  </div>
  <div class="tl-item">
    <p class="tl-year">2026</p>
    <p class="tl-text" data-i18n="tl-2026">六本书出版；创立炎灿东方香氛品牌。</p>
  </div>
</div>

<p class="home-sec-sub" style="margin-top:18px"><a href="/bio/" data-i18n="bio-link">完整履历 →</a></p>

<h2 class="home-sec" id="fragrance" data-i18n="home-sec-fragrance">炎灿香氛</h2>
<div class="home-products">
  <div class="prod">
    <a href="https://v.douyin.com/Cn5nHlyH8Ps/" target="_blank" rel="noopener"><img src="/assets/products/sachet-tuershen.jpg" alt="兔儿神香囊"></a>
    <b>兔儿神香囊</b> · ¥298 · <a href="https://v.douyin.com/Cn5nHlyH8Ps/" target="_blank" rel="noopener" data-i18n="fragrance-buy">抖音商城购买 →</a>
  </div>
  <div class="prod">
    <a href="https://v.douyin.com/Pbe2uTeAyTc/" target="_blank" rel="noopener"><img src="/assets/products/sachet-daji.jpg" alt="妲己香囊"></a>
    <b>妲己香囊</b> · ¥298 · <a href="https://v.douyin.com/Pbe2uTeAyTc/" target="_blank" rel="noopener" data-i18n="fragrance-buy">抖音商城购买 →</a>
  </div>
  <div class="prod">
    <a href="https://v.douyin.com/s9ryhyQnQ3Y/" target="_blank" rel="noopener"><img src="/assets/products/sachet-migang.jpg" alt="米缸香囊"></a>
    <b>米缸香囊</b> · ¥298 · <a href="https://v.douyin.com/s9ryhyQnQ3Y/" target="_blank" rel="noopener" data-i18n="fragrance-buy">抖音商城购买 →</a>
  </div>
</div>

<h2 class="home-sec" data-i18n="home-sec-biz">品牌与商业合作</h2>
<div class="biz-grid">
  <a class="biz-card" href="/books/">
    <p class="biz-en">Publishing</p>
    <p class="biz-title" data-i18n="biz-1-title">出版合作</p>
    <p class="biz-desc" data-i18n="biz-1-desc">已出版 6 本，另有待出版与撰写中作品。</p>
  </a>
  <a class="biz-card" href="/bio/">
    <p class="biz-en">Media &amp; Business</p>
    <p class="biz-title" data-i18n="biz-2-title">媒体与商务联系</p>
    <p class="biz-desc" data-i18n="biz-2-desc">请通过微信公众号“兔儿神胡天保”或 Instagram @luoyancan 联系。</p>
  </a>
</div>

<div class="home-auth">
  <h2 data-i18n="auth-title">权威链接</h2>
  <a href="https://www.imdb.com/name/nm7587912/" target="_blank" rel="noopener">IMDb</a>
  <a href="https://www.instagram.com/luoyancan/" target="_blank" rel="noopener">Instagram</a>
  <a href="https://www.facebook.com/profile.php?id=61596530016263" target="_blank" rel="noopener">Facebook</a>
  <a href="https://www.douyin.com/user/MS4wLjABAAAAHw1Jmov3dkm6ieqaQmTibsAKdiS8Ck0QLlcDSIj2zVVc78im497WKOnRPI-hWtD6" target="_blank" rel="noopener">炎灿抖音</a>
  <a href="https://weibo.com/u/2773030401" target="_blank" rel="noopener">释悟光-龙婆光</a>
  <button type="button" id="yc-wechat-btn">微信公众号</button>
  <a href="https://baike.baidu.com/item/%E7%BD%97%E6%96%87%E6%9D%B0/22678094" target="_blank" rel="noopener">百度百科</a>
  <a href="https://www.douban.com/personage/32568031/" target="_blank" rel="noopener">豆瓣影人</a>
</div>
<div class="yc-wechat-modal" id="yc-wechat-modal" hidden>
  <div class="yc-wechat-card">
    {% assign _qr = site.static_files | where: "path", "/assets/img/wechat-oa-qr.jpg" | first %}
    {% if _qr %}<img src="/assets/img/wechat-oa-qr.jpg" alt="微信公众号二维码">{% endif %}
    <p>微信公众号</p>
    <p><strong>兔儿神胡天保</strong></p>
    <p style="font-size:13px;color:var(--yc-glass-muted)">微信搜索“兔儿神胡天保”关注</p>
    <button type="button" id="yc-wechat-close">关闭</button>
  </div>
</div>

<p class="home-foot"><a href="/archive/" data-i18n="foot-archive">档案</a> · <a href="/books/" data-i18n="foot-books">全部著作</a></p>

</div>

<script>
/* 首页主视觉：随滚动轻轻缩放（克制优雅，transform 只影响图片本身，不动排版） */
(function(){
  var img=document.querySelector('.hero-full .hero-img');
  if(!img)return;
  if(window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches)return;
  var hero=img.closest('.hero-full');var ticking=false;
  function update(){
    ticking=false;
    var h=(hero&&hero.offsetHeight)||1;
    var p=Math.min(Math.max(window.scrollY/h,0),1);
    img.style.transform='scale('+(1+p*0.15).toFixed(3)+')';
  }
  window.addEventListener('scroll',function(){if(!ticking){ticking=true;requestAnimationFrame(update);}},{passive:true});
  update();
})();
/* 微信公众号二维码弹窗 */
(function(){
  var btn=document.getElementById('yc-wechat-btn');
  var modal=document.getElementById('yc-wechat-modal');
  var close=document.getElementById('yc-wechat-close');
  if(!btn||!modal)return;
  btn.addEventListener('click',function(){modal.hidden=false;});
  if(close)close.addEventListener('click',function(){modal.hidden=true;});
  modal.addEventListener('click',function(e){if(e.target===modal)modal.hidden=true;});
})();
</script>
