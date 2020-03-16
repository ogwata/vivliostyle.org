---
layout: page
title: サンプル
lang: ja
---


{% capture lead %}
Vivliostyleの機能をフルに使ったサンプルを公開します。各サンプルのボタンを押すと、Vivliostyle Viewer が起動し、ボタンの種別に応じた表示をします。楕円タグはサンプルごとに使われている機能を表します。
{% endcapture %}


{% include page/samples.html
  title="サンプルページ"
  lead=lead

  sample=site.data.sample.ja
  sample_other=site.data.sample_other.ja
%}
