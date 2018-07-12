---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Service Design Guide
description: The <i>Service Design Guide</i> helps VA teams meet the <a title="Digital Service Standard" href="../digital-standard">Digital Service Standard</a> by engaging with users and using best practices for agile delivery.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - What is service design?
  - Using the Service Design Guide
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: page
page-description: yes
sidebar-type: /service-design
permalink: /service-design/index.html
header-image: /assets/img/image-service-design.png
header-image-alt: Service Design Guide icon
#
---

> To launch a service (or feature) on the Veteran Tools Platform, you must follow the steps in this Service Design Guide.

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-' | replace: '?', ''}})
{% endfor %}

<hr>

### What is service design?

Service Design helps us to understand the people who will use a service in order to create solutions that work for them.

Service Design uses these methods to engage with users throughout the lifecycle of any service:
* Conduct user research to learn about users and their needs
* Test possible solutions (prototypes) with users
* Continuously test the live service with users to check that it continues to serve their needs

Using these methods ensures that we make decisions based on observations about users and their needs (rather than relying on our assumptions).

<hr>

### Using the Service Design Guide

1. [Getting started](getting-started)
2. [Discovery](discovery)
3. [Alpha](alpha)
4. [Beta](beta)
5. [Live](live)
6. [Related guides](related)

<!--span class="todo">TODO - explain the overall process with visual</span-->

<hr>

{% include include-footer-service-design.html next-phase="getting-started" prev-phase="none" %}
