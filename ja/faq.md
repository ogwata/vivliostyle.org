---
layout: page_with_toc
title: FAQ
lang: ja
---

{% assign contents = "" | split: "," %}


{% capture content %}
### Vivliostyle のオープンソース・ライセンスの種類は？

Vivliostyle はオープンソース・ライセンスとして AGPLv3 (GNU Affero General Public License, version 3) を採用しています。

AGPL は、GPL (GNU General Public License) と同様の互恵的なライセンス（派生物にも同じライセンスが適用される）であり、ソフトウェアの改変や商用利用が許可されています。GPL と異なる点は、ネットワーク経由の利用者にもソースコードにアクセスする権利が保証されることです。

参照:
- [GNU Affero General Public License (AGPLv3)](https://www.gnu.org/licenses/agpl-3.0.en.html)
  - [GNU Affero 一般公衆利用許諾書　日本語訳](http://gpl.mhatta.org/agpl.ja.html)
- [Frequently Asked Questions about the GNU Licenses](https://www.gnu.org/licenses/gpl-faq.en.html)
  - [GNUライセンスに関してよく聞かれる質問（GNUライセンスFAQ）日本語版](https://www.gnu.org/licenses/gpl-faq.ja.html)
{% endcapture %}
{% assign contents = contents | push: content %}


{% capture content %}
### Vivliostyle ソースコードのコピーライトの帰属先は？

Vivliostyle のソースコードには、次のようなコピーライト表記があります:
（[epub.ts](https://github.com/vivliostyle/vivliostyle/blob/master/packages/core/src/vivliostyle/epub.ts) の例）

> * Copyright 2013 Google, Inc.
> * Copyright 2015 Trim-marks Inc.
> * Copyright 2018 Vivliostyle Foundation

「Copyright 2013 Google, Inc.」とあるのは、Vivliostyle がもともと、Google に所属する Peter Sorotokin 氏によって開発された [EPUB Adaptive Layout JavaScript-based implementation ("Adapt")](https://github.com/sorotokin/adaptive-layout) をベースとして開発されたためです。この元プロジェクト由来のソースコードの権利は Google にあります。

Trim-marks 社（旧社名は Vivliostyle Inc.）は、2015年から2018年3月までのあいだ、Vivliostyle の開発の主体でした。この期間に書かれた Vivliostyle ソースコードの権利は Trim-marks 社にあります。また、Vivliostyle のライセンスは当初、元プロジェクトの "Adapt" を継承して Apache License 2.0 でしたが、2017年2月から AGPLv3 に変更されました。

Vivliostyle Foundation は、2018年3月に Trim-marks 社がオープンソース版の Vivliostyle の取り扱いをやめてから、そのオープンソース管理を引き継ぎました。それ以降に書かれた Vivliostyle のソースコードの権利は Vivliostyle Foundation にあります。
{% endcapture %}
{% assign contents = contents | push: content %}


{% capture content %}
### Vivliostyle を利用して作られた出版物にオープンソース・ライセンスによる制約はありますか？

いいえ。Vivliostyle のライセンスが AGPL であることは、Vivliostyle を利用して作られた出版物には影響しません。出版物のソースデータ（HTML や CSS）を公開する義務はとくにありません。
{% endcapture %}
{% assign contents = contents | push: content %}


{% capture content %}
### 会社内で Vivliostyle を制限なく利用できますか？

はい。Vivliostyle を会社・組織内でコピーして利用するのは自由であり、ソースコードを改変しても公開する義務はありません。

参照（GNUライセンスFAQ）:
- [GPLは、改変された版のソースコードを公に発表することを要求しますか?](https://www.gnu.org/licenses/gpl-faq.html#GPLRequireSourcePostedPublic)
- [一つの組織あるいは会社で複数のコピーを作成して使うことは「配布」となりますか?](https://www.gnu.org/licenses/gpl-faq.html#InternalDistribution)
{% endcapture %}
{% assign contents = contents | push: content %}


{% capture content %}
### Vivliostyle Viewer または Vivliostyle Print を商用の Web アプリケーションから呼び出して利用することはできますか？

はい。[Vivliostyle Viewer](https://github.com/vivliostyle/vivliostyle/tree/master/packages/viewer) および [Vivliostyle Print](https://github.com/vivliostyle/vivliostyle-print) は、クライアントサイドのブラウザ上で独立したプログラムとして動作するものなので、サーバーサイドのプログラムやクライアントサイドの別のプログラムがプロプライエタリであっても、それらと組み合わせて利用することが可能です。

Vivliostyle (Viewer/Print) を改変して利用することも、改変したソースコードを公開するならば可能です。ただし、AGPL である Vivliostyle のプログラムと、それを呼び出すプロプライエタリなプログラムとがそれぞれ独立を保った形でコミュニケートする必要があります。

参照（GNUライセンスFAQ）:
- [GPLの及ぶプラグインをロードするように設計された不自由なプログラムをリリースすることはできるでしょうか?](https://www.gnu.org/licenses/gpl-faq.html#NFUseGPLPlugins)
- [わたしのプロプライエタリ・システムに、GPLの及ぶソフトウェアを組み入れたいのです。わたしには、このソフトウェアを使う許可はGPLが与えてくれるもの以外にはなにもありません。わたしはできますか?](https://www.gnu.org/licenses/gpl-faq.html#GPLInProprietarySystem)
{% endcapture %}
{% assign contents = contents | push: content %}


{% capture content %}
### Vivliostyle CLI をサーバーサイドで利用することはできますか？

はい。[Vivliostyle CLI](https://github.com/vivliostyle/vivliostyle-cli) は、サーバーサイドの別のプログラムから呼び出されても、それぞれが独立したプログラムとして動作するかぎりは、呼び出す側のプログラムがプロプライエタリであっても問題ありません。
{% endcapture %}
{% assign contents = contents | push: content %}


{% capture content %}
### Vivliostyle を商用利用する上で気を付けるべき制限事項は？

Vivliostyle を AGPL ライセンスに従いながら商用利用する上で、以下のことに気を付ける必要があります:

- Vivliostyle を改変して配布する場合（注意：Webサイトでの利用も含まれます）、改変した Vivliostyle のソースコードを公開する必要があります。
- Vivliostyle を組み込んで単一の結合したプログラムとして動作するものを作成して配布する場合は、その全体のソースコードを AGPL ライセンスで公開する必要があります。
{% endcapture %}
{% assign contents = contents | push: content %}


{% include page/faq.html
  title="Vivliostyle のライセンスについての FAQ"
  contents=contents
%}
