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
return-top: yes
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
* Have everyone on your team create a Github account. Github requires Two-Factor authentication (2FA) to create an account.
* [Email a list](mailto:{{ site.contact-handbook.email }}) of all names, email addresses, and Github usernames.
  * On the list, indicate which people are developers, so that we can give them access to the code repositories and developer tools.
  * Developers also need to <a title="Go to help" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/internal-tools-access#ssh-key" target="_blank">create new SSH keys</a> and include their ***public SSH key*** in the information you email to us.

* We'll add the team to the VA Github organization and give them access to a team folder on Github, which you'll use to store and share project documents.
* If your team is new to Github, we can arrange a short meeting to show you how to use it share documents.

**Slack**

* We'll create a <a title="Go to Slack" href="https://slack.com" target="_blank">Slack</a> channel for your team to use. This channel may include people from other Veteran Tools Platform teams working on a similar service, so you can share findings and ask each other questions.
<!--* We'll also give you access to the *#dsva-platform-project channel*, which you can use if you have questions about the process described in this Handbook.-->

<a href="#">Return to top</a>

<hr>

### Tools for designers

The design system for the Veteran Tools Platform is based on the <a title="Go to USWDS" href="https://designsystem.digital.gov/" target="_blank">United States Web Design System (USWDS)</a>, with some additional specifications to meet the needs of VA’s particular audiences.

> **Our design files use <a title="Go to Sketch" href="https://www.sketchapp.com/" target="_blank">Sketch App</a>, which is a Mac application.**
<br/>Designers should download the Sketch files from the [design guide](related/design) so they can design using the latest Veteran Tools Platform templates.

<a href="#">Return to top</a>

<hr>

### Tools for developers

Once a developer's Github account is added to the VA Github organization and their SSH public key is set up, they'll be given access to the code repositories, credentials for shared testing environments, and internal tools.

Developers should review the [technical guide](related/technical) to complete the onboarding steps and confirm that they have access to all the tools.

<a href="#">Return to top</a>

<hr>

### Tools for agile

* coming soon

<hr>

{% include include-footer-service-design.html next-phase="discovery" prev-phase="overview" prev-phase-index="yes" %}
