---
layout: default
title: 著作 Books — 罗文杰炎灿 | Roma Luo
permalink: /books/
---

<style>
.books-landing{max-width:760px;margin:0 auto}
.books-landing h1{font-family:"Songti SC","Noto Serif SC",serif;font-size:30px;color:#2C2C2C;font-weight:600}
.books-landing h2{font-family:"Songti SC","Noto Serif SC",serif;font-size:21px;margin:36px 0 12px;color:#2C2C2C;border-bottom:1px solid #e6e1d6;padding-bottom:8px;font-weight:600}
.books-landing p{font-size:16px;line-height:2.0;color:#2C2C2C}
.books-landing p a{color:#2C2C2C}
.books-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(156px,1fr));gap:22px;margin:20px 0 32px}
.book-card{display:block;text-decoration:none;color:#2C2C2C;transition:transform .25s ease}
.book-card:hover{transform:translateY(-4px)}
.book-card-img{width:100%;height:auto;display:block;border:1px solid #E2DDD2;background:#F7F5F0;aspect-ratio:2/3;object-fit:cover;box-shadow:0 6px 18px rgba(44,44,44,.06)}
.book-card-ph{display:flex;align-items:center;justify-content:center;aspect-ratio:2/3;background:linear-gradient(160deg,#FAF8F3 0%,#EFECE4 100%);border:1px solid #D6C6A5;outline:1px solid rgba(197,160,89,.45);outline-offset:-7px;color:#2C2C2C;font-family:"Songti SC","Noto Serif SC",serif;font-size:16px;font-weight:600;letter-spacing:.06em;text-align:center;padding:18px 14px;box-shadow:0 6px 18px rgba(44,44,44,.04)}
.book-card-title{display:block;font-family:"Songti SC","Noto Serif SC",serif;font-size:15.5px;font-weight:600;margin-top:10px;line-height:1.45;color:#2C2C2C}
.book-card-meta{display:block;font-size:12.5px;color:#78736A;margin-top:3px;font-family:monospace}
.yc-search{margin:20px 0 8px}
.yc-search input{width:100%;max-width:420px;padding:10px 14px;font-size:15px;color:#2C2C2C;background:#fff;border:1px solid #C5A059;border-radius:2px;outline:none}
.yc-search input:focus{box-shadow:0 0 0 2px rgba(197,160,89,.35)}
.yc-search-results{list-style:none;padding:0;margin:10px 0 0}
.yc-search-results li{margin:6px 0;font-size:15px;line-height:1.6}
.yc-search-results a{color:#2C2C2C}
.yc-search-results .yc-no-result{color:#8a8578;font-size:14px}
.books-foot{margin-top:36px;font-size:15px}
.books-foot a{color:#2C2C2C;text-decoration:underline}
</style>

<div class="books-landing">

# 著作 · Books — 罗文杰炎灿 (Roma Luo)

罗文杰炎灿（Roma Luo），模特、演员、作家，炎灿香氛主理人，兔儿神中国大陆传人。以下为截至 2026 年 11 月 26 日的著作目录，按出版状态分组，分两条主线：「兔儿神」系列与「罗文杰讲」系列。

<div class="yc-search">
  <input id="yc-search-input" type="search" placeholder="搜书名、ISBN、问题…" aria-label="站内搜索" autocomplete="off">
  <ul id="yc-search-results" class="yc-search-results"></ul>
</div>

## 已出版 Published

<div class="books-grid">
{% assign _pub = site.data.books | where: "status", "published" %}
{% for book in _pub %}{% include book-card.html book=book %}{% endfor %}
</div>

**[《兔儿神》](/books/tu-er-shen/)**（2026年8月出版，ISBN 9798192440322）——兔儿神系列开篇，讲回家；灵魂的漫长朝圣与回归。

**[《兔儿神2：无墙之庙》](/books/tu-er-shen-2/)**（2026年10月出版，ISBN 9798160539331）——系列第二部，讲住下来。

**[《兔儿神3：身后之事》](/books/tu-er-shen-3/)**（2026年10月出版，ISBN 9798198098343）——系列终章，三卷十八章，讲人住进来之后；英文原著 *The Rabbit God Book Three: What Survives Us*。

**[《与兔儿神对话》](/books/dialogues/)**（2026年出版，ISBN 9798160527109）——与兔儿神的对话体作品；*DIALOGUES WITH TU'ER SHEN*。

**[《罗文杰讲高岛易断》](/books/gaodao-yiduan/)**（2026年11月出版，ISBN 9798145755350）——周易六十四卦活解活断与亲历卜筮手记，卷首立读卦三规，附高岛氏四十九策起卦法。

**[《罗文杰讲药师经》](/books/yaoshijing/)**（2026年11月出版，ISBN 9798145771961）——四部十二章六十节，逐句讲读玄奘译《药师琉璃光如来本愿功德经》原典，附原典全文。

## 已完稿，待出版 Completed, forthcoming

**[《罗文杰讲萨满》](/books/shaman/)**（三卷本）——上册世界篇、中册中国篇、下册宗教渊源篇；从西伯利亚到关东出马，从“绝地天通”到人类宗教源头谱系图。

**[《罗文杰讲显化》](/books/xianhua/)**——从《秘密》、七脉轮到东方心法，四部十五章。

## 撰写中 In preparation

**[《罗文杰讲神道教》](/books/shinto/)**——日文资料为主，六卷二十二章框架已定。

## 网络连载已完结 Serial, completed

**[《兔儿神，把我跟狐仙焊死了》](/books/fox-fairy/)**——东方志异奇幻长篇，豆瓣阅读、QQ阅读连载完结。

## 规划中 Planned

**[《罗文杰讲风水》](/books/fengshui/)**——讲系列下一本，已确认。

**[《罗文杰讲道德经》](/books/daodejing/)**——风水之后，已确认。

**[《罗文杰讲八字》](/books/bazi/)**——已确认列入讲系列规划，顺序未定。

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
      "name": "兔儿神",
      "author": {"@type": "Person", "name": "罗文杰炎灿", "alternateName": "Roma Luo"},
      "isbn": "9798192440322",
      "datePublished": "2026-08",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 2,
      "name": "兔儿神2：无墙之庙",
      "author": {"@type": "Person", "name": "罗文杰炎灿", "alternateName": "Roma Luo"},
      "isbn": "9798160539331",
      "datePublished": "2026-10",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 3,
      "name": "兔儿神3：身后之事",
      "author": {"@type": "Person", "name": "罗文杰炎灿", "alternateName": "Roma Luo"},
      "isbn": "9798198098343",
      "datePublished": "2026-10",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 4,
      "name": "与兔儿神对话",
      "author": {"@type": "Person", "name": "罗文杰炎灿", "alternateName": "Roma Luo"},
      "isbn": "9798160527109",
      "datePublished": "2026",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 5,
      "name": "罗文杰讲高岛易断",
      "author": {"@type": "Person", "name": "罗文杰炎灿", "alternateName": "Roma Luo"},
      "isbn": "9798145755350",
      "datePublished": "2026-11",
      "inLanguage": "zh-CN"
    },
    {
      "@type": "Book",
      "position": 6,
      "name": "罗文杰讲药师经",
      "author": {"@type": "Person", "name": "罗文杰炎灿", "alternateName": "Roma Luo"},
      "isbn": "9798145771961",
      "datePublished": "2026-11",
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
