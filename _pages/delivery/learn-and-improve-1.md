---
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on the page and in HTML meta tags
#
title: Learn and Improve introduction
description: Live description goes here.
#
# Editable - Pagination for bottom of page
#
pagination: yes
phase-prev: Build and Test
page-prev: checklist
phase-next: Learn and Improve
page-next: activities
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
# same name for sidebar + pagination include
sidebar-page-type: /delivery
permalink: /delivery/learn-and-improve/index.html
#
---

### What is Live?

Content in progress

<hr>

{% if site.data.phase-live %}

<ul class="usa-accordion secondary-accordion">

  {% for item in site.data.phase-live %}

  <li>
    <h3 id="{{ item.title | downcase | replace: ' ', '-' }}" class="usa-accordion-button"
      aria-expanded="false"
      aria-controls="{{ item.number }}">
      {{ item.title }}
    </h3>
    <div id="{{ item.number }}" class="usa-accordion-content secondary-accordion-content">

      {{ item.copy | markdownify }}

      <a href="#">Return to top</a>

    </div>

  </li>

  {% endfor %}

  {% if site.data.phase-resources %}
    {% include phase-resources.html phase="live" %}
  {% endif %}

</ul>

{% endif %}
