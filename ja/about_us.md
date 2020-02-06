---
layout: page
title: About Us
lang: ja
---

{% capture foundation_description %}
私たちは、オープンな標準技術で Web と出版・印刷の世界をひとつにするオープンソースの組版ソフトウェア Vivliostyle の開発、公開、普及を促進することにより、これまで印刷の歴史とともに培われてきた組版の技術を Web と電子出版において継承・進化させて、これからの世界の学術・文芸・情報コミュニケーションの発展に欠かせない出版の電子化とアクセシビリティの向上に寄与することを目指し、次のような活動を行います。

- Vivliostyle オープンソース・プロジェクトとコミュニティの維持管理
- Vivliostyle と関連技術の研究開発
- Vivliostyle と CSS 組版の普及啓発・教育
- Web・出版・アクセシビリティ等の標準技術に関する諸団体と連携して標準化推進
- Vivliostyle と連携する外部のプロジェクトとの協力
{% endcapture %}


{% capture foundation_text %}
### 一般社団法人ビブリオスタイル (Vivliostyle Foundation)

- 代表者：村上真雄
- 設立：2018 年 8 月
- 所在地：〒336-0015 埼玉県さいたま市南区太田窪1941-84
- 電話：090-3688-2212
- mail：[info@vivliostyle.org](mailto:info@vivliostyle.org)

### メンバー
{% endcapture %}


{% capture devteam_description %}
{% endcapture %}


{% capture sponsor_description %}
### このサイトに広告を出稿する

### クレジットカード決済で寄付する（congrantへ）

### GitHubスポンサーに応募する
{% endcapture %}


{% include page/about_us.html
  foundation_title="Vivliostyle Foundation について"
  foundation_description=foundation_description
  foundation_text=foundation_text
  foundation_members=site.data.foundation_members.ja

  devteam_title="コントリビューター一覧"
  devteam_description=devteam_description
  slack_buttontext="Slackに参加"

  sponsor_title="Vivliostyleのスポンサーになりませんか"
  sponsor_description=sponsor_description
%}
