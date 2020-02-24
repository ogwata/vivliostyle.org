---
layout: page
title: Documents
---


{% capture guide_description %}
### User Guide

- [User Guide](https://docs.vivliostyle.org/#/user-guide)
 - [Introduction](https://docs.vivliostyle.org/#/user-guide#introduction)
 - [Vivliostyle Viewer](https://docs.vivliostyle.org/#/user-guide#vivliostyle-viewer)
 - [Supported document types](https://docs.vivliostyle.org/#/user-guide#supported-document-types)
 - [Load document to render](https://docs.vivliostyle.org/#/user-guide#load-document-to-render)
 - [Fine-grained config](https://docs.vivliostyle.org/#/user-guide#fine-grained-config)
 - [Save and Print as PDF](https://docs.vivliostyle.org/#/user-guide#save-and-print-as-pdf)
 - [Supported CSS features](https://docs.vivliostyle.org/#/user-guide#supported-css-features)
 - [Contribution Guide]()

### Contribution Guide

- [Contribution Guide](https://docs.vivliostyle.org/#/contribution-guide)
  - [Module structure](https://docs.vivliostyle.org/#/contribution-guide#module-structure)
  - [Setup a development environment](https://docs.vivliostyle.org/#/contribution-guide#setup-a-development-environment)
  - [Build and serve](https://docs.vivliostyle.org/#/contribution-guide#build-and-serve)
  - [Viewer and test files](https://docs.vivliostyle.org/#/contribution-guide#viewer-and-test-files)
  - [Testing](https://docs.vivliostyle.org/#/contribution-guide#testing)
  - [Building production version](https://docs.vivliostyle.org/#/contribution-guide#building-production-version)
  - [Development mode](https://docs.vivliostyle.org/#/contribution-guide#development-mode)
  - [Maintaining documents](https://docs.vivliostyle.org/#/contribution-guide#maintaining-documents)
  - [Code](https://docs.vivliostyle.org/#/contribution-guide#code)
  - [Other dev documents](https://docs.vivliostyle.org/#/contribution-guide#other-dev-documents)
{% endcapture %}


{% capture reference_description %}
- [API Reference](https://docs.vivliostyle.org/#/api)
- [Supported Features](https://docs.vivliostyle.org/#/supported-features)
- [Available Properties](https://docs.vivliostyle.org/#/available-properties)
{% endcapture %}


{% capture plan_description %}
Would you like to contribute?
{% endcapture %}


{% capture plan_core_description %}
- Planning for the 2020 releases
- Version notation is vX.X.X format
{% endcapture %}


{% capture plan_pub_description %}
- [Features added]()
{% endcapture %}


{% capture plan_cli_description %}
- [PDF/X-1a compliant PDF file output]()
{% endcapture %}


{% capture plan_viewer_description %}
- [Update UI tests]()
- Multilingualization
{% endcapture %}


{% capture plan_others_description %}
- Chrome Extension
{% endcapture %}


{% capture license_description %}
{% endcapture %}


{% capture community_description %}
Vivliostyle project discusses development matters on Slack.
{% endcapture %}

{% include page/documents.html
  guide_title="Guide"
  guide_description=guide_description

  reference_title="Reference"
  reference_description=reference_description

  plan_title="Development Plan"
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

  plan_others_title="Others"
  plan_others_url=""
  plan_others_description=plan_others_description

  license_title="License"
  license_description=license_description

  community_title="Community invitation"
  community_description=community_description
  slack_buttontext="Join our Slack"
%}

