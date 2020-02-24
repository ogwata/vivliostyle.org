---
layout: page
title: ドキュメント
lang: ja
---


{% capture guide_description %}
### ユーザーガイド

- [User Guide](https://docs.vivliostyle.org/#/ja/user-guide)
 - [Introduction](https://docs.vivliostyle.org/#/ja/user-guide#introduction)
 - [Vivliostyle Viewer](https://docs.vivliostyle.org/#/ja/user-guide#vivliostyle-viewer)
 - [Supported document types](https://docs.vivliostyle.org/#/ja/user-guide#supported-document-types)
 - [Load document to render](https://docs.vivliostyle.org/#/ja/user-guide#load-document-to-render)
 - [Fine-grained config](https://docs.vivliostyle.org/#/ja/user-guide#fine-grained-config)
 - [Save and Print as PDF](https://docs.vivliostyle.org/#/ja/user-guide#save-and-print-as-pdf)
 - [Supported CSS features](https://docs.vivliostyle.org/#/ja/user-guide#supported-css-features)
 - [Contribution Guide]()

### コントリビューションガイド

- [Contribution Guide](https://docs.vivliostyle.org/#/ja/contribution-guide)
  - [Module structure](https://docs.vivliostyle.org/#/ja/contribution-guide#module-structure)
  - [Setup a development environment](https://docs.vivliostyle.org/#/ja/contribution-guide#setup-a-development-environment)
  - [Build and serve](https://docs.vivliostyle.org/#/ja/contribution-guide#build-and-serve)
  - [Viewer and test files](https://docs.vivliostyle.org/#/ja/contribution-guide#viewer-and-test-files)
  - [Testing](https://docs.vivliostyle.org/#/ja/contribution-guide#testing)
  - [Building production version](https://docs.vivliostyle.org/#/ja/contribution-guide#building-production-version)
  - [Development mode](https://docs.vivliostyle.org/#/ja/contribution-guide#development-mode)
  - [Maintaining documents](https://docs.vivliostyle.org/#/ja/contribution-guide#maintaining-documents)
  - [Code](https://docs.vivliostyle.org/#/ja/contribution-guide#code)
  - [Other dev documents](https://docs.vivliostyle.org/#/ja/contribution-guide#other-dev-documents)
{% endcapture %}


{% capture reference_description %}
- [API Reference](https://docs.vivliostyle.org/#/ja/api)
- [Supported Features](https://docs.vivliostyle.org/#/ja/supported-features)
- [Available Properties](https://docs.vivliostyle.org/#/ja/available-properties)
{% endcapture %}


{% capture plan_description %}
あなたもコントリビュートしてみませんか？
{% endcapture %}


{% capture plan_core_description %}
- 2020年のリリース計画を策定中
- バージョン表記がvX.X.X形式になります
{% endcapture %}


{% capture plan_pub_description %}
- [〜〜機能の追加]()
{% endcapture %}


{% capture plan_cli_description %}
- [PDF/X-1a に適合したPDFファイルの出力]()
{% endcapture %}


{% capture plan_viewer_description %}
- [UIテストの更新]()
- 多言語化
{% endcapture %}


{% capture plan_others_description %}
- Chrome拡張の作成
{% endcapture %}


{% capture license_description %}
{% endcapture %}


{% capture community_description %}
Vivliostyle プロジェクトでは、開発方針などをSlack上で話し合っています。
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
  slack_buttontext="Slackに参加"
%}
