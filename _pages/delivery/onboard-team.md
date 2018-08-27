---
#
# See the Github wiki for how to use Markdown in the editable content below:
# link here
#
# Title and Description display on the page and in HTML meta tags
#
title: Getting started
description: Get your team set up with the tools and resources they'll need throughout the digital delivery lifecycle.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - title: General team onboarding
  - title: Additional onboarding steps
    subsections:
    - title: For design
    - title: For development
    - title: For agile project management
#
# Editable - Pagination for bottom of page
#
pagination: yes
phase-prev: Overview
page-prev: none
phase-next: Research + Discovery
page-next: introduction
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-page-type: /delivery
# same name for sidebar + pagination include
permalink: /delivery/onboard-team
#
---

### Getting started

{% for item in page.sections %}

  {% if item.subsections %}

* [{{item.title}}](#{{item.title | downcase | replace: ' ', '-'}})

    {% for subitem in item.subsections %}

  * [{{subitem.title}}](#{{subitem.title | downcase | replace: ' ', '-'}})

    {% endfor %}

  {% else %}

* [{{item.title}}](#{{item.title | downcase | replace: ' ', '-'}})

  {% endif %}

{% endfor %}

<hr>

### General team onboarding

**Code of Conduct**

Read it.

**Github and Slack**

Github and Slack are the two primary tools we use to collaborate, share documents, and manage team workflows.

Follow the steps to [get your team set up on Github and Slack](https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Onboarding/github-and-slack.md).

<hr>

### Additional onboarding steps

#### For design

The design system for the Veteran Tools Platform is based on the <a title="Go to USWDS" href="https://designsystem.digital.gov/" target="_blank">United States Web Design System (USWDS)</a>, with some additional specifications to meet the needs of VA’s particular audiences.

> **Our design files use <a title="Go to Sketch" href="https://www.sketchapp.com/" target="_blank">Sketch App</a>, which is a Mac application.**
Designers should review the [Design guide](related/design) and [download the Sketch files](related/design#design-tools) so they can design using the latest Veteran Tools Platform templates.

<a href="#">Return to top</a>

#### For development

<!--
* Give developers access to repositories and tools they'll need to develop on the Veteran Tools Platform (see [Onboarding for developers](#onboarding-for-developers))
-->

Developers should complete the <a title="go to developer getting started" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started.html#getting-started" target="_blank">additional onboarding steps</a> as soon as they've received the email invitation to join the VA Github organization.

Zenhub for managing code.

<a href="#">Return to top</a>


### For agile project management

* coming soon
* Zenhub for managing agile workflow

<a href="#">Return to top</a>
