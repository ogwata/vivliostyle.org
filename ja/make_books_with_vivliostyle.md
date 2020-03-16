---
layout: page
title: Vivliostyle で本を作ろう
lang: ja
---

{% capture description %}
「Vivliostyle で本を作ろう」はユーザ会編集による同人誌。Vivliostyleを使うノウハウや、開発に参加するための情報がギッシリ詰まってます。毎回の[技術書典](https://techbookfest.org/)にあわせて刊行していますが、ご存知の通り技術書典8 (2020年2月29日、3月1日) は[開催中止](https://techbookfest.org/event/tbf08)。そこで、ここで販売予定だった第3号の内容を公開することにしました。あわせてバックナンバーも公開。これを読んで、Vivliostyle で本を作ろう！

<i class="mdi mdi-alpha-a-circle toc__type"></i>……入門、
<i class="mdi mdi-alpha-b-circle toc__type"></i>……使用レポート、
<i class="mdi mdi-alpha-c-circle toc__type"></i>……活用事例、
<i class="mdi mdi-alpha-d-circle toc__type"></i>……開発について、
<i class="mdi mdi-alpha-e-circle toc__type"></i>……Vivliostyle とはなにか？
{% endcapture %}


{% capture vol3_description %}
「Vivliostyleの過去と未来」が分かる原稿が集まりました。また、村上ファウンダーの論考は、なぜ Vivliostyle が生まれたのかを考えるためにも必読！
{% endcapture %}


{% capture vol2_description %}
一歩踏み込んだ活用事例が集まりました。とくに「Vivliostyle で縦組シナリオを組版する」では今までなかった縦組組版についても説明しています。

関連記事：[技術書典7に出展『Vivliostyleで本を作ろう Vol.2』公開！](/ja/blog/2019/09/25/make-books-with-vivliostyle-vol2/)
{% endcapture %}


{% capture vol1_description %}
創刊号らしく体験記事がたくさん集まりました。とくに村上ファウンダーの「Vivliostyle Viewer でCSS組版ちょっと入門」は今のところ数少ない Vivliostyle の入門記事です。

関連記事：[技術書典6に出展『Vivliostyleで本を作ろう Vol.1』公開！](ja/blog/2019/05/06/make-books-with-vivliostyle-vol1/)
{% endcapture %}



{% include assign/hash.html
  title="Vivliostyle で本を作ろう Vol.3<small>（2020年3月7日）</small>"
  description=vol3_description
  thumbnail=site.data.book.vol3.img
  toc=site.data.book.vol3.toc
  web_buttonlink=site.data.book.vol3.url.web
  viewer_buttonlink=site.data.book.vol3.url.viewer
  print_buttonlink=site.data.book.vol3.url.print
  source_buttonlink=site.data.book.vol3.url.source
%}{% assign vol3 = hash %}


{% include assign/hash.html
  title="Vivliostyle で本を作ろう Vol.2<small>（2019年9月22日）</small>"
  description=vol2_description
  thumbnail=site.data.book.vol2.img
  toc=site.data.book.vol2.toc
  web_buttonlink=site.data.book.vol2.url.web
  viewer_buttonlink=site.data.book.vol2.url.viewer
  print_buttonlink=site.data.book.vol2.url.print
  source_buttonlink=site.data.book.vol2.url.source
%}{% assign vol2 = hash %}


{% include assign/hash.html
  title="Vivliostyle で本を作ろう Vol.1<small>（2019年4月14日）</small>"
  description=vol1_description
  thumbnail=site.data.book.vol1.img
  toc=site.data.book.vol1.toc
  web_buttonlink=site.data.book.vol1.url.web
  viewer_buttonlink=site.data.book.vol1.url.viewer
  print_buttonlink=site.data.book.vol1.url.print
  source_buttonlink=site.data.book.vol1.url.source
%}{% assign vol1 = hash %}


{% assign books = "" | split: "|" | push: vol3 | push: vol2 | push: vol1 %}


{% include page/make_books_with_vivliostyle.html
  title="特集企画：Vivliostyle で本を作ろう"
  description=description
  books=books

  web_buttontext="Webページで読む"
  viewer_buttontext="Vivliostyle Viewer で読む"
  print_buttontext="印刷用"
  source_buttontext="ソース"
%}
