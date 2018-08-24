---
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Live
description: Live description goes here.
#
# Edit the discovery content below AND in /data/phase-live.yml
#
# The Planning for Live content is in /data/planning-for.yml
#
# The Next Steps content is in /data/next-steps.yml
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-type: /delivery
permalink: /delivery/learn-improve
pagination: yes
phase-prev: Build + Test
page-prev: none
phase-next: none
page-next: none
#
# To edit the Live content,
# use Markdown in the copy below.
#
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

  {% if site.data.resources-help %}
    {% include include-resources-help.html phase="live" %}
  {% endif %}

</ul>

{% endif %}

