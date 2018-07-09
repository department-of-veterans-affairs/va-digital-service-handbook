---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Alpha
description: Alpha is about prototyping and testing hypotheses with users. Your goal in alpha is to figure out how to meet the user needs you identified in discovery. Use alpha as your chance to test many different approaches with real users before building your service.
#
# Edit the alpha content below AND in /data/phase-alpha.yml
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/alpha
#
---

### What is Alpha?

* The primary objective of alpha is to answer the question: *How can your team best meet the user needs you identified in discovery?*

* The primary outcome of alpha is *a clear definition of your **Minimum Viable Product (MVP)** and a solid plan for how you'll build it.*
  <blockquote class="plain-blockquote">
  <b>The MVP is the first working version of your service</b>, which you'll build in the next phase &mdash; beta.
  <br/><br/>Your MVP will be the smallest set of working functionality you can build that provides value to your users &mdash; by meeting basic user needs.
  <br/><br/>The alpha phase is about figuring out what those basic user needs are, and how you'll meet them.
  </blockquote>

During the alpha phase, you'll iteratively design and test potential solutions. You'll build prototypes quickly and test them with users. You'll then use the feedback and testing results to improve the next prototype.

You'll repeat this process until the prototype meets your users' needs and your team is confident they know what the MVP will be and how to build it.

<hr>


{% if site.data.phase-alpha %}

<ul class="usa-accordion secondary-accordion">

  {% for item in site.data.phase-alpha %}

  <li>
    <h3 id="{{ item.title | downcase | replace: ' ', '-' }}" class="usa-accordion-button"
      aria-expanded="false"
      aria-controls="{{ item.number }}">
      {{ item.title }}
    </h3>
    <div id="{{ item.number }}" class="usa-accordion-content secondary-accordion-content">

      {{ item.copy | markdownify }}

      {% if item.title == "Completing alpha" %}
        {% include include-move-to-next-step.html phase="alpha" %}
      {% endif %}

      <a href="#">Return to top</a>

    </div>

  </li>

  {% endfor %}

  {% if site.data.resources-help %}
    {% include include-resources-help.html %}
  {% endif %}

</ul>

{% endif %}


<hr>

{% include include-footer-service-design.html next-phase="beta" prev-phase="discovery" %}
