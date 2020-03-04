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


{% include assign/hash.html
  title="Vivliostyle Core"
  url=site.data.project.core.github
  description=plan_core_description
  thumbnail=site.data.project.core.thumbnail
%}{% assign core = hash %}


{% include assign/hash.html
  title="Vivliostyle Pub"
  url=site.data.project.pub.github
  description=plan_pub_description
  thumbnail=site.data.project.pub.thumbnail
%}{% assign pub = hash %}


{% include assign/hash.html
  title="Vivliostyle CLI"
  url=site.data.project.cli.github
  description=plan_cli_description
  thumbnail=site.data.project.cli.thumbnail
%}{% assign cli = hash %}


{% include assign/hash.html
  title="Vivliostyle Viewer"
  url=site.data.project.viewer.github
  description=plan_viewer_description
  thumbnail=site.data.project.viewer.thumbnail
%}{% assign viewer = hash %}


{% include assign/hash.html
  title="その他"
  description=plan_others_description
%}{% assign others = hash %}


{% assign plans = "" | split: "" | push: core | push: pub | push: cli | push: viewer | push: others %}


{% include page/documents.html
  guide_title="ガイド"
  guide_description=guide_description

  reference_title="リファレンス"
  reference_description=reference_description

  plan_title="今後の開発予定"
  plan_description="あなたもコントリビュートしてみませんか？"
  plans=plans

  license_title="ライセンス"
  license_description=""

  community_title="コミュニティへの招待"
  community_description="Vivliostyle プロジェクトでは、開発方針などをSlack上で話し合っています。"
  slack_buttontext="Slackに参加"
%}
