---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
# Title and Description display on the page and in HTML meta tags
#
title: User Research guide
description: User research isn't just something you do during the discovery phase. You'll do it throughout the Digital Delivery lifecycle, checking in with your users to answer questions you have about how to improve your service.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - Expectations
  - User privacy
  - Create a research plan
  - Plan a research sprint
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
permalink: /resources/user-research
#
---

### Using the User Research guide

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

<!--### User research and the Paperwork Reduction Act

The Paperwork Reduction Act (PRA) limits the burden placed on people when interacting with the federal government. *To avoid going through the (often lengthy) PRA approval process, stay within PRA limits.*

PRA does allow you to observe people and ask them questions about the experience you are observing. However, some pre- and post-research activities must follow PRA guidelines.

<Follow the PRA guidance we've included in the sections below. If you're not certain if an activity is subject to PRA, [contact the DSVA team](../../contact).

<a href="#">Return to top</a>

<hr-->

### Expectations

Teams working on the Veteran Tools Platform are required to have "User Research" as a skillset (see [Team Structure]({{site.baseurl}}/resources/more/team-structure#team-roles)).

Teams working on the Veteran Tools Platform are responsible for conducting their own user research studies, including recruiting. User research/testing studies must adhere to the guidelines laid out in this User Research guide.

If you have any questions, ask your DSVA contact.

<a href="#">Return to top</a>

<hr>

### User privacy

Whatever people say or do during user research sessions is considered private information that your team must protect.

**Tips**:
* Don't post recruiting files with names, emails, or phone numbers. Keep these locally on your computer.
* All session notes should to refer to research participants as "Participant 1", "Participant 2", and so on. Any PII in the session notes must be deleted before posting or sharing with your team.
* If audio or video recordings contain PII, you must delete that information before posting or sharing the files with your team.

<a href="#">Return to top</a>

<hr>

### Create a research plan

Create a research plan at the start of each development phase, especially discovery, alpha, and beta. Then regularly update your research plan as you learn more about your users.

{% for group in site.data.research-guide %}

  {% if group[0] == 'plan' %}

  <ul class="usa-accordion">

    {% for item in group[1] %}
      {% if forloop.first %}
      <li>
        <button class="usa-accordion-button"
          aria-expanded="true"
          aria-controls="{{ item.number}}">
          {{ item.title }}
        </button>
        <div id="{{ item.number }}" class="usa-accordion-content">

          {{ item.copy | markdownify }}

        </div>
      </li>      
      {% else %}
      <li>
        <button class="usa-accordion-button"
          aria-controls="{{ item.number}}">
          {{ item.title }}
        </button>
        <div id="{{ item.number }}" class="usa-accordion-content">

          {{ item.copy | markdownify }}

        </div>
      </li>
      {% endif %}
    {% endfor %}

  </ul>

  {% endif %}

{% endfor %}

<a href="#">Return to top</a>

<hr>


### Plan a research sprint

This [research sprint planning template](other-resources/research-sprints) may be useful as you're planning your research sprint.

{% for group in site.data.research-guide %}

  {% if group[0] == 'sprints' %}

  <ul class="usa-accordion">

    {% for item in group[1] %}
      {% if forloop.first %}
      <li>
        <button class="usa-accordion-button"
          aria-expanded="true"
          aria-controls="{{ item.number}}">
          {{ item.title }}
        </button>
        <div id="{{ item.number }}" class="usa-accordion-content">

          {{ item.copy | markdownify }}

        </div>
      </li>
      {% else %}
      <li>
        <button class="usa-accordion-button"
          aria-controls="{{ item.number}}">
          {{ item.title }}
        </button>
        <div id="{{ item.number }}" class="usa-accordion-content">

          {{ item.copy | markdownify }}

        </div>
      </li>  
      {% endif %}    
    {% endfor %}

  </ul>

  {% endif %}

{% endfor %}

<a href="#">Return to top</a>

<hr>

### Getting help

DSVA design resources are available to provide guidance and support throughout development and deployment.

* For process-related questions, ask in the *#support-external* Slack channel.
* For research-related questions, ask in your team's "Product" Slack channel.

<hr>
