---
layout: default
title: 图集 — 罗文杰炎灿 | Roma Luo
permalink: /gallery/
---

<style>
.gallery-page{max-width:760px;margin:0 auto}
.gallery-page h1{font-size:28px;color:#2C2C2C}
.gallery-page h2{font-size:20px;margin:32px 0 12px;color:#2C2C2C;border-bottom:1px solid #e6e1d6;padding-bottom:8px}
.gallery-page p{font-size:15px;line-height:1.9;color:#2C2C2C}
.gallery-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(160px,1fr));gap:16px}
.gallery-grid figure{margin:0}
.gallery-grid img{width:100%;height:auto;display:block;cursor:zoom-in;border:1px solid #e6e1d6;background:#F7F5F0}
.gallery-grid figcaption{font-size:13px;color:#8a8578;text-align:center;margin-top:6px}
.lightbox{position:fixed;inset:0;background:rgba(0,0,0,.88);z-index:999;display:flex;align-items:center;justify-content:center;flex-direction:column}
.lightbox[hidden]{display:none}
.lightbox img{max-width:94vw;max-height:86vh;width:auto;height:auto}
.lightbox button{margin-top:14px;background:none;border:1px solid #fff;color:#fff;padding:8px 20px;font-size:15px;cursor:pointer}
</style>

<div class="gallery-page">

# 图集

照片与封面，点开放大。更多照片陆续补充。

## 书封

<div class="gallery-grid">
  <figure><img src="/assets/covers/tu-er-shen-3-en.jpg" alt="《兔儿神3》英文版封面"><figcaption>《兔儿神3》英文版封面</figcaption></figure>
  <figure><img src="/assets/covers/tu-er-shen-3-zh.jpg" alt="《兔儿神3》中文版封面"><figcaption>《兔儿神3》中文版封面</figcaption></figure>
  <figure><img src="/assets/covers/gaodao-yiduan.jpg" alt="《罗文杰讲高岛易断》封面"><figcaption>《罗文杰讲高岛易断》封面</figcaption></figure>
  <figure><img src="/assets/covers/yaoshijing.jpg" alt="《罗文杰讲药师经》封面"><figcaption>《罗文杰讲药师经》封面</figcaption></figure>
</div>

## 威尼斯 · 2015

<div class="gallery-grid">
  <figure><img src="/visual_assets/venice-2015/luo-wenjie-venice-red-carpet-2015.jpg" alt="2015年威尼斯电影节红毯"><figcaption>2015年威尼斯电影节红毯</figcaption></figure>
  <figure><img src="/visual_assets/venice-2015/luo-wenjie-venice-2015-photocall.jpg" alt="2015年威尼斯电影节拍照环节"><figcaption>2015年威尼斯电影节拍照环节</figcaption></figure>
  <figure><img src="/visual_assets/venice-2015/luo-wenjie-underground-fragrance-film-still.jpg" alt="《地下香》剧照"><figcaption>《地下香》剧照</figcaption></figure>
</div>

## 肖像

<div class="gallery-grid">
  <figure><img src="/assets/img/profile.jpg" alt="罗文杰炎灿肖像"><figcaption>罗文杰炎灿</figcaption></figure>
</div>

<p><a href="/">返回首页</a></p>

</div>

<div class="lightbox" id="lightbox" hidden><img id="lightbox-img" alt=""><button id="lightbox-close" type="button">关闭</button></div>
<script>
(function(){
  var box=document.getElementById('lightbox');
  var img=document.getElementById('lightbox-img');
  var nodes=document.querySelectorAll('.gallery-grid img');
  for(var i=0;i<nodes.length;i++){
    nodes[i].addEventListener('click',function(){
      img.src=this.src;
      img.alt=this.alt||'';
      box.hidden=false;
    });
  }
  document.getElementById('lightbox-close').addEventListener('click',function(){box.hidden=true;});
  box.addEventListener('click',function(){box.hidden=true;});
})();
</script>
