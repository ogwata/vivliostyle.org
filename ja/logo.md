---
layout: page
title: ロゴ
lang: ja
---

{% capture about_logo_description %}
2020年から新しくなりました

地球要素と本要素をいい感じに

青と赤と白がテーマカラーです
{% endcapture %}


{% capture use_logo_description %}
Vivliostyle を紹介したい際に使えるロゴデータがあるとうれしい
{% endcapture %}


{% include page/logo.html
  about_logo_title="ロゴについて"
  about_logo_description=about_logo_description

  use_logo_title="ロゴの使用について"
  use_logo_description=use_logo_description
%}
