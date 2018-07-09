---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Discovery
description: Discovery is not about solutions; it’s about uncovering problems. Before you start designing or building a service, you need to find out who the potential users are and what problems your service could solve for them.
#
# Edit the discovery content below AND in /data/discovery.yml
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/discovery
#
---

### What is Discovery?

It's tempting to start brainstorming solutions right away based on your understanding of your project. Doing that leads to a solution-focused design process in which your team's primary question is: How do we build the solution?

Instead focus on a user-centered design process in which your team's primary questions are: Who are the potential users of my service, and how can we design a service that meets their needs?

Your goal in the discovery phase is to **learn about real users and identify the problem(s) your service could solve for them**. The best way to do this is to [talk to real users](related/user-research). Go out and find people who will be using the service. Talk to them, observe them, and learn what they need and want.

<hr>


{% if site.data.alpha %}

<ul class="usa-accordion secondary-accordion">

  {% for item in site.data.discovery %}

  <li>
    <h3 id="{{ item.title | downcase | replace: ' ', '-' }}" class="usa-accordion-button"
      aria-expanded="false"
      aria-controls="{{ item.number }}">
      {{ item.title }}
    </h3>
    <div id="{{ item.number }}" class="usa-accordion-content secondary-accordion-content">

      {{ item.copy | markdownify }}

      {% if item.title == "Completing discovery" %}
        {% include include-move-to-next-step.html phase="discovery" %}
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

{% include include-footer-service-design.html next-phase="alpha" prev-phase="getting-started" %}
