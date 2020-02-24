---
layout: page
title: About Us
---

{% capture foundation_description %}
Our purpose is to promote the development,
public release,
and adoption of the open source typesetting software Vivliostyle
which unifies the Web and publishing/printing world,
so that the typesetting technique that has been cultivated throughout the history of printing
is inherited and evolved on Web and digital publishing,
and contribute to digitization of publishing indispensable
for the advancement of academic,
literary and informational communication around the world and improve accessibility.
For this purpose, we carry out activities such as:

- Maintenance and management of Vivliostyle open source project and community
- Research and development of Vivliostyle and related technologies
- Promotion and education of Vivliostyle and CSS typesetting
- Promote standardization in cooperation with groups related to standard technologies such as Web, publishing, and accessibility
- Cooperation with external projects working with Vivliostyle
{% endcapture %}


{% capture foundation_text %}
### Vivliostyle Foundation

- Representative: Shinyu Murakami
- Founded: August 2018
- Location: 1941-84 Daitakubo, Minami-ku, Saitama-shi, Saitama 336-0015, Japan
- Phone: +81-90-3688-2212

### Members
{% endcapture %}


{% capture devteam_description %}
{% endcapture %}


{% include page/about_us.html
  foundation_title="About Vivliostyle Foundation"
  foundation_description=foundation_description
  foundation_text=foundation_text
  foundation_members=site.data.foundation_members.en

  devteam_title="Contributors"
  devteam_description=devteam_description
  slack_buttontext="Join our Slack"

  sponsor_title="Be a Sponsor of Vivliostyle"
  advertisement_buttontext="Advertise on this site"
  advertisement_buttonlink=""
  congrat_buttontext="Donate by credit card payment (to congrant)"
  congrat_buttonlink=""
  github_buttontext="Apply for the GitHub Sponsors"
  github_buttonlink=""
%}
