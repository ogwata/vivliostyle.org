---
layout: page
title: 使ってみる
lang: ja
---

{% capture pub_description %}
Vivliostyle Pub は、ブラウザ上で完結する〜〜

ブラウザ上ではなく、手元のPCで作りたい場合は [Vivliostyle CLI](#Vivliostyle CLI) をご利用ください。
{% endcapture %}


{% capture pub_frame1_description %}
HTMLとCSSを用意する→Vivliostyle Pub上でビルド→いい感じにPDFができる

Vivliostyle Pub上で動くサンプルを用意したので見てね
{% endcapture %}


{% capture cli_description %}
Vivliostyle Pub は、コマンド〜〜

コマンドラインではなく、ブラウザ上で作りたい場合は [Vivliostyle Pub](#Vivliostyle Pub) をご利用ください。
{% endcapture %}


{% capture cli_frame1_description %}
Vivliostyle CLI は、npm パッケージとして公開して〜〜

Node〜〜

```shell
$ npm install -g @vivliostyle/cli
```
{% endcapture %}


{% capture cli_frame2_description %}
〜〜

preview機能では〜〜

```shell
$ vivliostyle init --template thesis
$ vivliostyle preview
$ vivliostyle build
```
{% endcapture %}


{% capture viewer_description %}
Vivliostyle Viewer は、〜〜
{% endcapture %}


{% capture viewer_frame1_description %}
〜〜

Vivliostyle CLI の preview 機能との違いは、〜〜
{% endcapture %}


{% include page/getting_started.html
  pub_title="Vivliostyle Pub"
  pub_tip="v2.x.x"
  pub_description=pub_description
  pub_buttontext="Vivliostyle Pub を使う"
  pub_buttonlink=""
  pub_buttonlink_github=""
  pub_frame1_title="CSS組版で本を作りたい！"
  pub_frame1_description=pub_frame1_description
  pub_gallery=site.data.pub.gallery.ja

  cli_title="Vivliostyle CLI"
  cli_tip="v2.x.x"
  cli_description=cli_description
  cli_link_github=""
  cli_frame1_title="インストール方法"
  cli_frame1_description=cli_frame1_description
  cli_frame2_title="HTMLからPDFを作成する"
  cli_frame2_description=cli_frame2_description

  viewer_title="Vivliostyle Viewer"
  viewer_tip="v2.x.x"
  viewer_description=viewer_description
  viewer_buttontext="Vivliostyle Viewer を使う"
  viewer_buttonlink=""
  viewer_buttonlink_github=""
  viewer_frame1_title="Webページを好みのスタイルで見たい！"
  viewer_frame1_description=viewer_frame1_description
%}
