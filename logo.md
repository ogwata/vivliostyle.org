---
layout: page
title: Logo
---

{% capture about_logo_description %}
The old logo (left) was designed to look like a giant book floating above the Earth. The earth symbolizes the World Wide Web, and the book symbolizes Vivliostyle as you can see from the "V" shape. The design is by Tomoyuki Ishida and the illustration is by Satoshi Ohtera.

The new logo (right) was designed in January 2020 by Yasuaki Uechi to renew the old one. The intention is to refresh the image by changing to flat and vivid colors and trimming boldly, for upgrading to Vivliostyle 2.0.
{% endcapture %}


{% capture use_logo_description %}
{% endcapture %}


{% include page/logo.html
  about_logo_title="About the logo"
  about_logo_description=about_logo_description

  use_logo_title="Use of the logo"
  use_logo_description=use_logo_description
%}
