---
layout: page
title: サンプル
lang: ja
---


<!-- 技術書 -->
{% capture technical_description %}
特集ページも見てね

Vivliostyle Viewer: オンラインの Vivliostyle Viewer でページ表示、印刷用: トンボ付き Vivliostyle Viewer
HTML: 通常のHTML表示、ソース: GitHub上のソースファイル（HTMLやCSS）　　……みたいな説明
{% endcapture %}


<!-- 技術書 - vivliostyle_vol1 -->
{% capture vivliostyle_vol1_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

関連記事: [技術書典6に出展『Vivliostyle で本を作ろう Vol. 1』公開！]()
{% endcapture %}


<!-- 技術書 - vivliostyle_vol2 -->
{% capture vivliostyle_vol2_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

関連記事: [技術書典7に出展『Vivliostyle で本を作ろう Vol. 2』公開！]()
{% endcapture %}


<!-- 技術書 - vivliostyle_vol3 -->
{% capture vivliostyle_vol3_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

関連記事: [技術書典8に出展『Vivliostyle で本を作ろう Vol. 3』公開！]()
{% endcapture %}


{% include assign/sample.html
  data=site.data.sample.ja.technical.vivliostyle_vol1
  description=vivliostyle_vol1_description
%}{% assign sample1 = sample %}


{% include assign/sample.html
  data=site.data.sample.ja.technical.vivliostyle_vol2
  description=vivliostyle_vol2_description
%}{% assign sample2 = sample %}


{% include assign/sample.html
  data=site.data.sample.ja.technical.vivliostyle_vol3
  description=vivliostyle_vol3_description
%}{% assign sample3 = sample %}


{% include assign/array.html
  sample1=sample1
  sample2=sample2
  sample3=sample3
%}{% assign samples = array %}


{% include assign/hash.html
  title=site.data.sample.ja.technical.name
  description=technical_description
  samples=samples
%}{% assign category1 = hash %}


<!-- 小説 -->
{% capture novel_description %}
小説のさんぷるです

ここの文章はあってもなくてもいい
{% endcapture %}


<!-- 小説 - gutenberg -->
{% capture gutenberg_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

クレジットとか
{% endcapture %}


<!-- 小説 - gon -->
{% capture gon_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

固定ページ・可変ページとは？

クレジットとか
{% endcapture %}


{% include assign/sample.html
  data=site.data.sample.ja.novel.gutenberg
  description=gutenberg_description
%}{% assign sample1 = sample %}


{% include assign/sample.html
  data=site.data.sample.ja.novel.gon
  description=gon_description
%}{% assign sample2 = sample %}


{% include assign/array.html
  sample1=sample1
  sample2=sample2
%}{% assign samples = array %}


{% include assign/hash.html
  title=site.data.sample.ja.novel.name
  description=novel_description
  samples=samples
%}{% assign category2 = hash %}


<!-- 雑誌・新聞 -->
{% capture magazine_news_description %}
ここの文章はあってもなくてもいい
{% endcapture %}


<!-- 雑誌・新聞 - webmag -->
{% capture webmag_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

このサンプルでは、[JDIR JBpress Digital Innovation Review](http://jbpress.ismedia.jp/feature/jdir) の記事を、株式会社日本ビジネスプレスより承諾を得て利用させていただいております。
{% endcapture %}


<!-- 雑誌・新聞 - apollo8 -->
{% capture webmag_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

クレジットとか Peter Sorotokin’s [Adaptive Layout](https://sorotokin.com/adaptive-layout/)
{% endcapture %}


<!-- 雑誌・新聞 - shirouma -->
{% capture shirouma_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

クレジットとか
{% endcapture %}


<!-- 雑誌・新聞 - news -->
{% capture news_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

クレジットとか
{% endcapture %}


{% include assign/sample.html
  data=site.data.sample.ja.magazine_news.webmag
  description=webmag_description
%}{% assign sample1 = sample %}


{% include assign/sample.html
  data=site.data.sample.ja.magazine_news.apollo8
  description=apollo8_description
%}{% assign sample2 = sample %}


{% include assign/sample.html
  data=site.data.sample.ja.magazine_news.shirouma
  description=shirouma_description
%}{% assign sample2 = sample %}


{% include assign/sample.html
  data=site.data.sample.ja.magazine_news.news
  description=news_description
%}{% assign sample2 = sample %}


{% include assign/array.html
  sample1=sample1
  sample2=sample2
%}{% assign samples = array %}


{% include assign/hash.html
  title=site.data.sample.ja.magazine_news.name
  description=magazine_newspaper_description
  samples=samples
%}{% assign category3 = hash %}


<!-- 記事 -->
{% capture article_description %}
ここの文章はあってもなくてもいい
{% endcapture %}


<!-- 記事 - scholarly -->
{% capture scholarly_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

クレジット
{% endcapture %}


<!-- 記事 - malay -->
{% capture malay_description %}
なにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキストなにかしらの紹介テキスト

クレジット
{% endcapture %}


{% include assign/sample.html
  data=site.data.sample.ja.article.scholarly
  description=scholarly_description
%}{% assign sample2 = sample %}


{% include assign/sample.html
  data=site.data.sample.ja.article.malay
  description=malay_description
%}{% assign sample2 = sample %}


{% include assign/array.html
  sample1=sample1
  sample2=sample2
%}{% assign samples = array %}


{% include assign/hash.html
  title=site.data.sample.ja.article.name
  description=article_description
  samples=samples
%}{% assign category4 = hash %}


{% include assign/array.html
  category1=category1
  category2=category2
  category3=category3
  category4=category4
%}{% assign categories = array %}


{% include page/samples.html
  categories=categories

  viewer_buttontext="Vivliostyle Viewer で見る"
  print_buttontext="印刷用"
  html_buttontext="HTML"
  source_buttontext="ソース"
%}
