---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: User research guide
description: User research isn't just something you do during the discovery phase. You'll do it throughout the service lifecycle, checking in with your users to answer questions you have about how to improve your service.
#
# Edit the research-guide content in /data/research-guide.yml
#
# Internal page menu - titles here match titles in /data/research-guide.yml
sections:
  - User research and the Paperwork Reduction Act
  - User privacy
  - Create a research plan
  - Plan a research sprint
  - Additional resources
#
# Don't edit items below - they control the page layout
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/related/user-research
#
---

### Using the research guide

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### User research and the Paperwork Reduction Act

The Paperwork Reduction Act (PRA) limits the burden placed on people when interacting with the federal government. *To avoid going through the lengthy PRA approval process (+ 60 days), stay within PRA limits.*

PRA does allow you to observe people and ask them questions about the experience you are observing. However, some pre- and post-research activities must follow PRA guidelines.

Follow the specific PRA guidance we've included in the sections below. If you're not certain if an activity is subject to PRA, [email us](mailto:site.contact-handbook). <span class="todo">MS to review this guidance</span>

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

### Additional resources

 * <span class="todo">TODO - add more resources</span>

<hr>

<a href="#">Return to top</a>
