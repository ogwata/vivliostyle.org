---
layout: page
title: 使ってみる
lang: ja
---

{% capture pub_description %}
左ペインでテキスト / Markdown / HTML を入力・編集すると、右ペインで組版結果がプレビューできます。
{% endcapture %}


{% capture cli_description %}
コマンドラインで CSS 組版して、印刷入稿可能なPDF/X-1a で保存します。
{% endcapture %}


{% capture cli_frame1_description %}
Vivliostyle CLI は、npm パッケージとして公開する予定です。また、Node.js のインストールが前提になります。

```shell
$ npm install -g @vivliostyle/cli
```
{% endcapture %}


{% capture cli_frame2_description %}
ターミナルのコマンドラインから、HTML ファイルを指定して実行すると、CSS 組版したPDFファイルを出力します。preview オプションも用意されています。

```shell
$ vivliostyle preview
$ vivliostyle build
```
{% endcapture %}


{% capture viewer_description %}
ブラウザで動作する組版エンジン。HTML を読み込んで組版結果をブラウザに表示します。
{% endcapture %}


{% capture viewer_frame1_description %}
HTML と CSS を用意して Vivliostyle Viewer で組版結果を確認できます。これを PDF として出力できます。サンプルを用意したのでご覧ください。
{% endcapture %}


{% include page/getting_started.html
  pub_title="Vivliostyle Pub <small>(初期版を今年中に公開予定)</small>"
  pub_tip=site.data.project.pub.version
  pub_description=pub_description
  pub_buttontext="Vivliostyle Pub を使う"
  pub_buttonlink=site.data.project.pub.url
  pub_buttonlink_github=site.data.project.pub.github

  cli_title="Vivliostyle CLI <small>(2月中公開予定)</small>"
  cli_tip=site.data.project.cli.version
  cli_description=cli_description
  cli_buttonlink_github=site.data.project.cli.github
  cli_frame1_title="インストール方法"
  cli_frame1_description=cli_frame1_description
  cli_frame2_title="HTMLからPDFを作成する"
  cli_frame2_description=cli_frame2_description

  viewer_title="Vivliostyle Viewer"
  viewer_tip=site.data.project.viewer.version
  viewer_description=viewer_description
  viewer_buttontext="Vivliostyle Viewer を使う"
  viewer_buttonlink=site.data.project.viewer.sample
  viewer_buttonlink_github=site.data.project.viewer.github
  viewer_frame1_title="CSS組版で本を作りたい！"
  viewer_frame1_description=viewer_frame1_description
  viewer_gallery=site.data.pub.gallery.ja
%}
