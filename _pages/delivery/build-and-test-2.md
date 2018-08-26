---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on the page and in HTML meta tags
#
title: Build and Test activities
description: Beta is about incrementally building (and testing) the MVP user stories and features you've identified, so you can launch the first working version of your service at the end of the beta phase.
#
# Editable - Pagination for bottom of page
#
pagination: yes
phase-prev: Build and Test
page-prev: introduction
phase-next: Build and Test
page-next: checklist
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
# same name for sidebar + pagination include
sidebar-page-type: /delivery
permalink: /delivery/build-and-test/activities
#
---

### What is Beta?

In the beta phase, it's tempting to try to build all the features and functionality you imagine for your service. But stay focused on your vision for the MVP. **As soon as your service can provide value by meeting basic user needs, it’s ready to launch!**

During beta, you'll build the user stories and features from your backlog in small batches of functionality. As you build these batches, you'll test them with your users to ensure they work well. Then you'll use that user feedback to refine your service, adding and adjusting features until your MVP service is complete.``

<hr>


{% if site.data.phase-beta %}

<ul class="usa-accordion secondary-accordion">

  {% for item in site.data.phase-beta %}

  <li>
    <h3 id="{{ item.title | downcase | replace: ' ', '-' }}" class="usa-accordion-button"
      aria-expanded="false"
      aria-controls="{{ item.number }}">
      {{ item.title }}
    </h3>
    <div id="{{ item.number }}" class="usa-accordion-content secondary-accordion-content">

    {% if item.title == "Planning for beta" %}
      {% include phase-planning.html phase="beta" %}
    {% endif %}

      {{ item.copy | markdownify }}

      {% if item.title == "Completing beta" %}
        next steps
      {% endif %}

      <a href="#">Return to top</a>

    </div>

  </li>

  {% endfor %}

  {% if site.data.phase-resources %}
    {% include phase-resources.html phase="beta" %}
  {% endif %}

</ul>

{% endif %}
