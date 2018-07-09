---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Technical guide
description: Get started with Veteran Tools Platform developer tools. Find technical resources, tools, and examples you can use throughout the service lifecycle.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Getting started
  - Development
  - Internal Tools
  - Getting help
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/related/technical
#
---

### Using the technical guide

Before using this guide, make sure you've completed the steps in [onboarding your team](../getting-started#onboarding-your-team).

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Getting started

* Review the Vets Developer Docs starting with the section titled "<a title="Go to developer documentation" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started.html" target="_blank">Getting Started</a>."

* Confirm that you have access to the 3 code repositories, the shared testing environments, and to the Internal Tools. If you run into a problem or can't get access, [email us](mailto:{{ site.contact-handbook.email }}).

* Review the documentation for <a title="Go to Vets-Website readme" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/vets-website/vets-website-readme" target="_blank">Vets-Website</a>.

* Review the documentation for <a title="Go to Vets-API readme" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/vets-api/vets-api-readme" target="_blank">Vets-API</a>.

<a href="#">Return to top</a>

<hr>

### Development

To build a service on the Veteran Tools Platform, which can be anything from a digital form to a map-based facility locator, developers will create a Frontend experience in React on Vets-Website, and connect it to an Integration on Vets-API, which manages the data flow to and from VA systems.

**Code repositories**
The Veteran Tools Platform is broken into three parts:
1. <a title="Go to Vets-Website" href="https://github.com/department-of-veterans-affairs/vets-website" target="_blank">Vets-Website</a>, which contains frontend applications and components users interact with
2. <a title="Go to Vets-API" href="https://github.com/department-of-veterans-affairs/vets-api" target="_blank">Vets-API</a>, a JSON-based API used by the frontend to provide data to and from VA systems
3. <a title="Go to Vets-JSON-Schema" href="https://github.com/department-of-veterans-affairs/vets-json-schema" target="_blank">Vets-JSON-Schema</a>, which contains shared resources used to structure and validate form data between Vets-Website and Vets-API.

<a href="#">Return to top</a>

<hr>

### Internal Tools

To access metrics, build logs, deployment information, and exception details, see the <a title="Go to Internal Tools" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/internal-tools-access" target="_blank">Internal Tools</a> documentation.

<a href="#">Return to top</a>

<hr>

### Getting help

DSVA product and engineering resources are available to provide guidance and support through the development effort. If you encounter issues or have any questions, raise them in the #dsva-platform-project Slack channel.

<hr>
