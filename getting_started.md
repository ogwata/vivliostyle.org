---
layout: page
title: Getting Started
---

{% capture pub_description %}
Edit text/Markdown/HTML in the left pane and preview the formatted results in the right pane.

![](/assets/screenshot-pub.png)
{% endcapture %}


{% capture cli_description %}
CSS typesetting on command line, and save as print-ready PDF/X-1a.
{% endcapture %}


{% capture cli_frame1_description %}
Vivliostyle CLI will be released as an npm package. Also, Node.js must be installed.

```shell
$ npm install -g @vivliostyle/cli
```
{% endcapture %}


{% capture cli_frame2_description %}
In the Terminal command line, run it with your HTML file to output PDF file with CSS typesetting. There is also the preview option.

```shell
$ vivliostyle preview
$ vivliostyle build
```
{% endcapture %}


{% capture viewer_description %}
A typesetting engine that runs on the browser. Read HTML and display the formatted result on the browser.
{% endcapture %}


{% capture viewer_frame1_description %}
Prepare HTML and CSS files and view the formatted result with Vivliostyle Viewer. This can be output as PDF.
{% endcapture %}


{% include page/getting_started.html
  pub_title="Vivliostyle Pub <small>(Initial version will be released later this year)</small>"
  pub_tip=site.data.project.pub.version
  pub_description=pub_description
  pub_buttontext="Use Vivliostyle Pub"
  pub_buttonlink=site.data.project.pub.url
  pub_buttonlink_github=site.data.project.pub.github

  cli_title="Vivliostyle CLI <small>(To be released in February)</small>"
  cli_tip=site.data.project.cli.version
  cli_description=cli_description
  cli_buttonlink_github=site.data.project.cli.github
  cli_frame1_title="How to install"
  cli_frame1_description=cli_frame1_description
  cli_frame2_title="Create PDF from HTML"
  cli_frame2_description=cli_frame2_description

  viewer_title="Vivliostyle Viewer"
  viewer_tip=site.data.project.viewer.version
  viewer_description=viewer_description
  viewer_buttontext="Use Vivliostyle Viewer"
  viewer_buttonlink=site.data.project.viewer.sample
  viewer_buttonlink_github=site.data.project.viewer.github
  viewer_frame1_title="Want to make a book with CSS typesetting!"
  viewer_frame1_description=viewer_frame1_description
  viewer_gallery=site.data.pub.gallery.en
%}
