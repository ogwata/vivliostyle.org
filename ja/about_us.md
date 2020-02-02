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
一般社団法人ビブリオスタイル

Vivliostyle Foundation

2018年8月 設立
{% endcapture %}


{% capture devteam_description %}
〜〜
{% endcapture %}


{% capture sponsor_description %}
〜〜
{% endcapture %}


{% include page/about_us.html
  foundation_title="Vivliostyle Foundation について"
  foundation_description=foundation_description
  foundation_text=foundation_text
  foundation_members=site.data.people

  devteam_title="開発チーム"
  devteam_description=devteam_description
  slack_buttontext="Slackに参加"

  sponsor_title="スポンサー募集"
  sponsor_description=sponsor_description
%}
