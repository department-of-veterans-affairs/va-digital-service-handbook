---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
# Title and Description display on the page and in HTML meta tags
#
title: Content guide
description: Learn about the Veteran Tools Platform content strategy. Find content resources, tools, and examples you can use throughout the <i>Digital Delivery</i> lifecycle.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - Expectations
  - Content style guide
  - Getting help
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
# same name for sidebar + pagination include
sidebar-page-type: /resources
permalink: /resources/content
#
---

### Using the Content guide

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Expectations

Teams working on the Veteran Tools Platform are required to have "Content Strategy/Writing" as a skillset (see [Team Structure]({{site.baseurl}}/resources/more/team-structure#team-roles)).

Teams working on the Veteran Tools Platform are responsible for creating well-written, plain language content for their services. This content must adhere to the guidelines and rules laid out in the Content Style Guide.

If you have any questions, ask your DSVA contact.

<hr>

### Content style guide

Our content style guide evolves as we learn new information about how Veterans think about the services we provide.

* See the <a href="https://github.com/department-of-veterans-affairs/vets.gov-content-style-guide" target="_blank">content style guide</a>.

<hr>

### Getting help

DSVA content resources are available to provide guidance and support throughout development and deployment.

* For process-related questions, ask in the *#{{site.slack.support}}* Slack channel.
* For content-related questions, ask in your team's "Product" Slack channel.

<hr>
