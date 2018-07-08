---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Getting started
description: Get your team set up with the tools and resources they'll need throughout the service lifecycle.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Onboarding your team
  - Tools for designers
  - Tools for developers
  - Tools for agile
#
# Don't edit items below - they control the page layout
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/getting-started
#
---
### Getting started

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Onboarding your team

**Github**
Veteran Tools Platform teams use <a title="Go to VA Github" href="https://github.com/department-of-veterans-affairs" target="_blank">Github</a> for sharing project documents. We do this so all Veteran Tools Platform teams can learn from what other teams are doing.

Starting in the Alpha phase, your developers will start integrating with the Veteran Tools Platform release management process. We use Github Issues to manage that process.

To get started
* Have everyone on your team create a Github account.
* [Email a list](mailto:{{ site.contact-handbook.email }}) of all names, email addresses, and Github usernames.
  * On the list, indicate which people are developers, so that we can give them access to the code repositories and developer tools.
  * Developers also need to <a title="Go to help" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/internal-tools-access#ssh-key" target="_blank">create new SSH keys</a> and include their ***public SSH key*** in the information you email to us.

* We'll add the team to the VA Github organization and give them access to a team folder on Github, which you'll use to store and share project documents.
* If your team is new to Github, we can arrange a short meeting to show you how to use it share documents.

**Slack**

We use <a title="Go to Slack" href="https://slack.com" target="_blank">Slack</a> as our team chat tool; we'll create a Slack channel for your team to use during the project.

<a href="#">Return to top</a>

<hr>

### Tools for designers

The Veteran Tools Platform design system based on the <a title="Go to USWDS" href="https://designsystem.digital.gov/" target="_blank">United States Web Design System (USWDS)</a> with some additional specifications to meet the needs of VA’s particular audiences.

> **Our design files use <a title="Go to Sketch" href="https://www.sketchapp.com/" target="_blank">Sketch App</a>, which is a Mac application.**
<br/>Although you can use other platforms/tools, we strongly recommend using Sketch to ensure your designers are working with our latest templates.
<br/>Designers should download the design files from the [design guide](related/design) so they can effectively design for the Veteran Tools Platform.

<a href="#">Return to top</a>

<hr>

### Tools for developers

Once a developer's Github account is added to the VA Github organization and their SSH public key is set up, they will be given access to Veteran Tools Platform code repositories, credentials for shared testing environments, and internal tools.

Developers should review the [technical guide](related/technical) to complete the onboarding steps and confirm that they have access to all the tools.

<a href="#">Return to top</a>

<hr>

### Tools for agile

* coming soon

<hr>

{% include include-service-design-footer-nav.html data="discovery" %}
