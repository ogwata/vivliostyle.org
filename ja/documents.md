---
layout: page
title: ドキュメント
lang: ja
---


{% capture guide_description %}
[docs.vivliostyle.org](docs.vivliostyle.org)

〜〜
{% endcapture %}


{% capture reference_description %}
[docs.vivliostyle.org](docs.vivliostyle.org)

〜〜
{% endcapture %}


{% capture plan_description %}
あなたもコントリビュートしてみませんか？〜〜
{% endcapture %}


{% capture plan_core_description %}
- 2020年のリリース計画を策定中。バージョン表記がvX.X.X形式になります
{% endcapture %}


{% capture plan_pub_description %}
- [〜〜機能の追加]()
{% endcapture %}


{% capture plan_cli_description %}
- [PDF/X-1a に適合したPDFファイルの出力]()
- --size オプションの〜〜
{% endcapture %}


{% capture plan_viewer_description %}
- [UIテストの更新]()
- 多言語化
{% endcapture %}


{% capture plan_others_description %}
- Chrome拡張の作成
{% endcapture %}


{% capture license_description %}
AGPL〜〜
{% endcapture %}


{% capture community_description %}
Vivliostyle プロジェクトでは、開発方針などをSlack上で話し合〜〜
{% endcapture %}

{% include page/documents.html
  guide_title="ガイド"
  guide_description=guide_description

  reference_title="リファレンス"
  reference_description=reference_description

  plan_title="今後の開発予定"
  plan_description=plan_description
  plans=plans

  plan_core_title="Vivliostyle Core"
  plan_core_url=""
  plan_core_description=plan_core_description
  plan_core_thumbnail="/assets/project-core.png"

  plan_pub_title="Vivliostyle Pub"
  plan_pub_url=""
  plan_pub_description=plan_pub_description
  plan_pub_thumbnail="/assets/project-pub.png"

  plan_cli_title="Vivliostyle CLI"
  plan_cli_url=""
  plan_cli_description=plan_cli_description
  plan_cli_thumbnail="/assets/project-cli.png"

  plan_viewer_title="Vivliostyle Viewer"
  plan_viewer_url=""
  plan_viewer_description=plan_viewer_description
  plan_viewer_thumbnail="/assets/project-viewer.png"

  plan_others_title="その他"
  plan_others_url=""
  plan_others_description=plan_others_description

  license_title="ライセンス"
  license_description=license_description

  community_title="コミュニティへの招待"
  community_description=community_description
%}
