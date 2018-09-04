---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on the page and in HTML meta tags
#
title: Technical guide
description: Get started with Veteran Tools Platform developer tools. Find technical resources, tools, and examples you can use throughout the <i>Digital Delivery</i> lifecycle.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - Expectations
  - Getting started
  - Development
  - Getting help
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
# same name for sidebar + pagination include
sidebar-page-type: /resources
permalink: /resources/technical
#
---

### Using the Technical guide

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Expectations

Teams working on the Veteran Tools Platform are required to have "Technical" as a skillset, including architecture, development, quality assurance, testing, and deployment (see [Team Structure]({{site.baseurl}}/resources/more/team-structure#team-roles)).

Teams working on the Veteran Tools Platform are responsible for building services that follow guidelines in this Technical guide and in the <a href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started.html" target="_blank">Veteran Tools Platform Developer Documentation</a>.

If you have any questions, ask your DSVA contact.

<hr>


### Getting started

* Complete all the <a href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started.html#getting-started" target="_blank">"Getting Started" tasks for developers</a>.

* Be sure to confirm that you have access to the code repositories and shared testing environments and that you can use the Internal Tools.

<hr>

### Development

* Review the developer documentation <a href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started.html#development" target="_blank">starting with the "Development" section</a>.

* If you're creating a form, use the <a href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/vets-website/forms/form-tutorial.html" target="_blank">Basic Form Tutorial</a> to get familiar with how form work on the Veteran Tools Platform.

* If you'll be interacting with an API, review <a href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/vets-api/vets-api-readme.html" target="_blank">the API documentation</a>.

<hr>

### Getting help

DSVA technical and engineering resources are available to provide guidance and support throughout development and deployment.

* For process-related questions, ask in the *#{{site.slack.support}}* Slack channel.
* For product-related questions, ask in your team's "Product" Slack channel.

<hr>
