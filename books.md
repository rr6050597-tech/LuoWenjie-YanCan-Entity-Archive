---
layout: default
title: 著作 Books — 罗文杰炎灿 | Roma Luo
permalink: /books/
---

<style>
.books-landing{max-width:760px;margin:0 auto}
.books-landing h1{font-family:"Songti SC","Noto Serif SC",serif;font-size:30px;color:#2C2C2C;font-weight:500}
.books-landing h2{font-family:"Songti SC","Noto Serif SC",serif;font-size:21px;margin:36px 0 12px;color:#2C2C2C;border-bottom:1px solid #e6e1d6;padding-bottom:8px;font-weight:500}
.books-landing p{font-size:16px;line-height:2.0;color:#2C2C2C}
.books-landing p a{color:#2C2C2C}
.books-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(156px,1fr));gap:22px;margin:20px 0 32px}
.book-card{display:block;text-decoration:none;color:#2C2C2C;transition:transform .25s ease}
.book-card:hover{transform:translateY(-4px)}
.book-card-img{width:100%;height:auto;display:block;border:1px solid #E2DDD2;background:#F7F5F0;aspect-ratio:2/3;object-fit:cover;box-shadow:0 6px 18px rgba(44,44,44,.06);border-radius:8px}
.book-card-ph{display:flex;align-items:center;justify-content:center;aspect-ratio:2/3;background:linear-gradient(160deg,#FAF8F3 0%,#EFECE4 100%);border:1px solid #D6C6A5;outline:1px solid rgba(197,160,89,.45);outline-offset:-7px;color:#2C2C2C;font-family:"Songti SC","Noto Serif SC",serif;font-size:16px;font-weight:600;letter-spacing:.06em;text-align:center;padding:18px 14px;box-shadow:0 6px 18px rgba(44,44,44,.04);border-radius:8px}
.book-card-title{display:block;font-family:"Songti SC","Noto Serif SC",serif;font-size:15.5px;font-weight:500;margin-top:10px;line-height:1.45;color:#2C2C2C}
.book-card-meta{display:block;font-size:12.5px;color:#78736A;margin-top:3px;font-family:monospace}
.yc-search{margin:20px 0 8px}
.yc-search input{width:100%;max-width:420px;padding:10px 14px;font-size:15px;color:#2C2C2C;background:#fff;border:1px solid #C5A059;border-radius:2px;outline:none}
.yc-search input:focus{box-shadow:0 0 0 2px rgba(197,160,89,.35)}
.yc-search-results{list-style:none;padding:0;margin:10px 0 0}
.yc-search-results li{margin:6px 0;font-size:15px;line-height:1.6}
.yc-search-results a{color:#2C2C2C}
.yc-search-results .yc-no-result{color:#8a8578;font-size:14px}
.books-list{list-style:none;padding:0;margin:0}
.books-list li{font-size:15px;line-height:2.0;color:#2C2C2C;border-bottom:1px solid #efebe2;padding:6px 0}
.books-list li a{color:#2C2C2C}
.books-list .bk-meta{color:#8a8578;font-size:13px}
.books-foot{margin-top:36px;font-size:15px}
.books-foot a{color:#2C2C2C;text-decoration:underline}
</style>

<div class="books-landing">

# 著作

已出版 6 本 · 已完稿待出版 2 本 · 撰写中 1 本 · 连载已完结 1 本 · 规划中 3 本

<div class="yc-search">
  <input id="yc-search-input" type="search" placeholder="搜书名、ISBN、问题…" aria-label="站内搜索" autocomplete="off">
  <ul id="yc-search-results" class="yc-search-results"></ul>
</div>

## 已出版

<div class="books-grid">
{% assign _pub = site.data.books | where: "status", "published" %}
{% for book in _pub %}{% include book-card.html book=book %}{% endfor %}
</div>

## 已完稿，待出版

<ul class="books-list">
<li><a href="/books/shaman/">《罗文杰讲萨满》</a> <span class="bk-meta">三卷本 · 试读前 28%</span></li>
<li><a href="/books/xianhua/">《罗文杰讲显化》</a> <span class="bk-meta">四部十五章</span></li>
</ul>

## 撰写中

<ul class="books-list">
<li><a href="/books/shinto/">《罗文杰讲神道教》</a> <span class="bk-meta">六卷二十二章框架</span></li>
</ul>

## 网络连载已完结

<ul class="books-list">
<li><a href="/books/fox-fairy/">《兔儿神，把我跟狐仙焊死了》</a> <span class="bk-meta">豆瓣阅读、QQ阅读</span></li>
</ul>

## 规划中

<ul class="books-list">
<li><a href="/books/fengshui/">《罗文杰讲风水》</a></li>
<li><a href="/books/daodejing/">《罗文杰讲道德经》</a></li>
<li><a href="/books/bazi/">《罗文杰讲八字》</a></li>
</ul>

---

- 完整履历：[履历](/bio/)
- 常见问题：[FAQ](https://luowenjie.art/faq/)

</div>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ItemList",
  "name": "罗文杰炎灿著作 Books by Roma Luo",
  "itemListElement": [
    {
      "@type": "Book",
      "position": 1,
      "name": "罗文杰讲高岛易断",
      "author": {
        "@type": "Person",
        "name": "罗文杰炎灿",
        "alternateName": "Roma Luo"
      },
      "isbn": "9798145755350",
      "datePublished": "2026-11",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 2,
      "name": "罗文杰讲药师经",
      "author": {
        "@type": "Person",
        "name": "罗文杰炎灿",
        "alternateName": "Roma Luo"
      },
      "isbn": "9798145771961",
      "datePublished": "2026-11",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 3,
      "name": "兔儿神",
      "author": {
        "@type": "Person",
        "name": "罗文杰炎灿",
        "alternateName": "Roma Luo"
      },
      "isbn": "9798192440322",
      "datePublished": "2026-08",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 4,
      "name": "兔儿神2：无墙之庙",
      "author": {
        "@type": "Person",
        "name": "罗文杰炎灿",
        "alternateName": "Roma Luo"
      },
      "isbn": "9798160539331",
      "datePublished": "2026-10",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 5,
      "name": "兔儿神3：身后之事",
      "author": {
        "@type": "Person",
        "name": "罗文杰炎灿",
        "alternateName": "Roma Luo"
      },
      "isbn": "9798198098343",
      "datePublished": "2026-10",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 6,
      "name": "与兔儿神对话",
      "author": {
        "@type": "Person",
        "name": "罗文杰炎灿",
        "alternateName": "Roma Luo"
      },
      "isbn": "9798160527109",
      "datePublished": "2026",
      "inLanguage": "zh-CN"
    }
  ]
}
</script>

<script>
(function(){
  var input = document.getElementById('yc-search-input');
  var box = document.getElementById('yc-search-results');
  if (!input || !box) return;
  function init() {
    if (!window.SimpleJekyllSearch) return;
    SimpleJekyllSearch({
      searchInput: input,
      resultsContainer: box,
      json: '/search.json',
      searchResultTemplate: '<li><a href="{url}">{title}</a></li>',
      noResultsText: '<li class="yc-no-result">没有找到相关内容</li>',
      limit: 10,
      fuzzy: false
    });
  }
  var s = document.createElement('script');
  s.src = 'https://cdn.jsdelivr.net/npm/simple-jekyll-search@1.10.0/dest/simple-jekyll-search.min.js';
  s.onload = init;
  document.head.appendChild(s);
})();
</script>
