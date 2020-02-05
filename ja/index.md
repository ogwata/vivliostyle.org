---
title: The Vivliostyle Project
lang: ja
jumbotron_image: true
excerpt: "open source, web browser based CSS typesetting engine project"
---

{% capture section1_description %}
Vivliostyle Pub <small>(β版6月予定)</small> を使えば、EPUBや印刷可能なPDFをブラウザ上で作成できます。

Vivliostyle CLI <small>(春頃公開)</small> でも、HTMLとCSSがあればEPUBやPDFを作成できます。
{% endcapture %}


{% capture section2_description %}
Vivliostyle Viewer を使えば、EPUBやWeb上の文書を〜〜
{% endcapture %}


{% capture section3_description %}
coreがあって役割ごとにn個の小プロジェクトがありますよみたいな説明
{% endcapture %}


{% capture section5_description %}
Vivliostyleプロジェクトでは、開発方針などをSlack上で話し合〜〜

開発ガイド、ドキュメントは [開発のてびき]() を〜〜
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

  posts=posts

  animation1_src="/assets/animation1.png"
  animation2_src="/assets/animation2.png"
  animation3_src="/assets/animation3.png"

  core_thumbnail="/assets/project-core.png"
  pub_thumbnail="/assets/project-pub.png"
  cli_thumbnail="/assets/project-cli.png"
  viewer_thumbnail="/assets/project-viewer.png"

  project1_src="/assets/project1.png"
  project2_src="/assets/project2.png"
  project3_src="/assets/project3.png"
  project4_src="/assets/project4.png"
  project_core_description="〜〜"
  project_pub_description="〜〜"
  project_cli_description="〜〜"
  project_viewer_description="〜〜"

  pub_buttontext="ブラウザで作る"
  pub_buttonsampletext="作成例を見る"
  cli_buttontext="コマンドで作る"
  viewer_buttontext="Vivliostyle Viewer で読む"
  or_text="または"

  core_link=""
  pub_samplelink=""
  pub_link=""
  cli_link=""
  viewer_link=""
%}
