---
title: Vivliostyle — Enjoy CSS Typesetting!
layout: page
jumbotron_image: true
excerpt: "open source, web browser based CSS typesetting engine project"
---

{% capture section1_description %}
With Vivliostyle Pub  <small>(initial version will be released later this year)</small> you can create EPUBs and print-ready PDFs in your browser.

With Vivliostyle CLI, you can create PDFs with HTML and CSS.
{% endcapture %}


{% capture section2_description %}
With Vivliostyle Viewer, you can read EPUB or HTML files in your preferred style.
{% endcapture %}


{% capture section3_description %}
Various projects are derived from Vivliostyle Core.
{% endcapture %}


{% capture section5_description %}
The Vivliostyle project discusses development matters on Slack. Please take a look. Click the button below for the development guide and documentation.
{% endcapture %}


{% assign posts = site.posts | where: "lang", page.lang | slice: 0, 3 %}


{% include page/index.html
  section1_title="Want to make a book with CSS typesetting!"
  section1_description=section1_description

  section2_title="Want to read EPUBs or Web documents in preferred style!"
  section2_description=section2_description

  section3_title="What is the Vivliostyle project?"
  section3_description=section3_description

  section4_title="Recent blogs"
  section4_description=section4_description

  section5_title="Let's develop together"
  section5_description=section5_description

  slack_buttontext="Join our Slack"
  github_buttontext="Join development"
  document_buttontext="See Documents"
  document_buttonlink="/documents"

  posts=posts

  animation1_src="/assets/animation1.png"
  animation2_src="/assets/animation2.png"
  animation3_src="/assets/animation3.png"

  core_thumbnail=site.data.project.core.thumbnail
  pub_thumbnail=site.data.project.pub.thumbnail
  cli_thumbnail=site.data.project.cli.thumbnail
  viewer_thumbnail=site.data.project.viewer.thumbnail

  project1_src="/assets/project1.png"
  project2_src="/assets/project2.png"
  project3_src="/assets/project3.png"
  project4_src="/assets/project4.png"
  project_core_description="TypeScript library that implements various CSS typesetting specifications"
  project_pub_description="Enter markdown and you can see the typesetting results immediately."
  project_cli_description="Typesetting from command line and generate PDF."
  project_viewer_description="Load HTML and display the typesetting results on the browser."

  pub_buttontext="Make with browser"
  pub_buttonsampletext="View samples"
  cli_buttontext="Make with command"
  viewer_buttontext="Read with Vivliostyle Viewer"
  or_text="or"

  core_link=site.data.project.core.github
  pub_samplelink=site.data.project.pub.sample
  pub_link=site.data.project.pub.github
  cli_link=site.data.project.cli.github
  viewer_link=site.data.project.cli.sample
%}
