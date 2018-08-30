---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Conducting technical discovery
description: Complete a technical review during the <i>Research and Discovery</i> phase and do ongoing technical discovery throughout the Digital Delivery lifecycle.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Overall philosophy
  - Questions to ask about existing APIs
  - Questions to ask about creating a new API
  - Ongoing technical discovery
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-page-type: /resources
permalink: /resources/more/technical-discovery
#
---

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Overall philosophy

Use an existing <a title="Go to Vets-API" href="https://github.com/department-of-veterans-affairs/vets-api" target="_blank">Vets-API</a> if it will provide what you need to meet core service functionality and performance standards.

Consider the possibility of creating a new API, if existing Vets-APIs would deliver an impaired experience (either for end-users or for the VA business).

* **Tip**: Talk to a DSVA engineer if you're considering a new API.
* See the <a title="" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/vets-api/vets-api-readme.html" target="_blank">documentation for Vets-APIs</a>.

<a href="#">Return to top</a>

<hr>


### Questions to ask about existing APIs
* What kinds of simplifications would​ be​ required when building against this service?
* Do you anticipate needing additional branch logic or conditions?
* What data is available in the service beyond what you would likely need (i.e., is it too bloated or complex for what you need)?
* Is there data you think you'll need that's not included in the service?
* How reliable is it?
* Are there decent routes available for resolving issues between sources?

<a href="#">Return to top</a>

<hr>


### Questions to ask about creating a new API
* Is the data underneath changing frequently?
* For Getting or Posting data, will it have to communicate with more than one system?
* Is there a lot of logic needed to transform the data into what you need for the product?

* If you're leaning towards creating a new API, who should do that?
  * Should someone build a middle service?
  * Should it be a direct connection?

<a href="#">Return to top</a>

<hr>

### Ongoing technical discovery

Conduct ongoing technical discovery as your team learns more about the problem you're trying to solve &mdash; and the solution you're planning to build.

Questions to consider

* Does the order of the screens mean any changes to schema or suggest difficult data handling?
* If users need to upload something, how will the uploaded information be sent and/or stored?
* Can you submit structured data directly? Or do you need to create a PDF for submission? Both?
* Are any required backend services frequently (or predictably) unavailable? What kind of messaging to the user will you need?
* How well does the design line up with the technical limitations uncovered in discovery?
* Are there parts of the design that need to be reconsidered due to technical issues?
* Is there additional back end development that needs to happen before the project can proceed?
