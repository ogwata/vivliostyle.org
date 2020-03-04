---
title: Vivliostyle — 楽しく CSS 組版！
lang: ja
jumbotron_image: true
excerpt: "open source, web browser based CSS typesetting engine project"
---

{% capture section1_description %}
Vivliostyle Pub <small>(初期版を今年中に公開予定)</small> を使えば、EPUBや印刷可能なPDFをブラウザ上で作成できます。

Vivliostyle CLI でも、HTMLとCSSがあればPDFを作成できます。
{% endcapture %}


{% capture section2_description %}
Vivliostyle Viewer を使えば、EPUBやHTMLファイルを自分好みの組版で読むことができます。
{% endcapture %}


{% capture section3_description %}
Vivliostyle Core から、さまざまなプロジェクトが派生しています。
{% endcapture %}


{% capture section5_description %}
Vivliostyleプロジェクトでは、開発方針などをSlack上で話し合っています。ぜひ見てみてください。開発ガイド、ドキュメントは下記ボタンからご覧ください。
{% endcapture %}


{% assign posts = site.posts | where: "lang", page.lang | slice: 0, 3 %}


{% include page/index.html
  section1_title="CSS組版で本を作りたい！"
  section1_description=section1_description

  section2_title="EPUBやWeb上の文書を、好みのスタイルで読みたい！"
  section2_description=section2_description

  section3_title="Vivliostyle プロジェクトとは？"
  section3_description=section3_description

  section4_title="最近のブログ"
  section4_description=section4_description

  section5_title="一緒に開発しませんか"
  section5_description=section5_description

  slack_buttontext="Slackに参加"
  github_buttontext="開発に参加"
  document_buttontext="ドキュメントを見る"
  document_buttonlink="/ja/documents"

  posts=posts

  animation1_src="/assets/animation1.png"
  animation2_src="/assets/animation2.png"
  animation3_src="/assets/animation3.png"

  core_thumbnail=site.data.project.core.thumbnail
  pub_thumbnail=site.data.project.pub.thumbnail
  cli_thumbnail=site.data.project.cli.thumbnail
  viewer_thumbnail=site.data.project.viewer.thumbnail

  project1_src="/assets/project1.png"
  project2_src="/assets/project2.png"
  project3_src="/assets/project3.png"
  project4_src="/assets/project4.png"
  project_core_description="各種 CSS 組版仕様を実装した TypeScript ライブラリ"
  project_pub_description="マークダウンを入力すると組版結果をすぐ見られる。"
  project_cli_description="コマンドラインから組版して PDF を生成。"
  project_viewer_description="HTML を読み込んで組版結果をブラウザに表示。"

  pub_buttontext="ブラウザで作る"
  pub_buttonsampletext="作成例を見る"
  cli_buttontext="コマンドで作る"
  viewer_buttontext="Vivliostyle Viewer で読む"
  or_text="または"

  core_link=site.data.project.core.github
  pub_samplelink=site.data.project.pub.sample
  pub_link=site.data.project.pub.github
  cli_link=site.data.project.cli.github
  viewer_link=site.data.project.cli.sample
%}
