---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Beta
description: Beta is about incrementally building (and testing along the way) the MVP user stories and features you've identified, so you can launch the first working version of your service at the end of the beta phase.  
#
# Edit the research-guide content in /data/beta.yml
#
# Don't edit items below - they control the page layout
#
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/beta
#
---

### What is Beta?

In the beta phase, it's tempting to try to build all the features and functionality you imagine for your service. But stay focused on your vision for the MVP. **As soon as your service can provide value by meeting your users' basic needs, it’s ready to launch!**

During beta, you'll build the user stories and features from your backlog in small batches of functionality. As you build these batches, you'll test them with your users to ensure they work well. Then you'll use that user feedback to refine your service, adding and adjusting features until your MVP service is complete.

<hr>


{% if site.data.beta %}

<ul class="usa-accordion secondary-accordion">

  {% for item in site.data.beta %}

  <li>
    <h3 id="{{ item.title | downcase | replace: ' ', '-' }}" class="usa-accordion-button"
      aria-expanded="true"
      aria-controls="{{ item.number }}">
      {{ item.title }}
    </h3>
    <div id="{{ item.number }}" class="usa-accordion-content secondary-accordion-content">

      {{ item.copy | markdownify }}

      {% if item.title == "Completing beta" %}
        {% include include-move-to-next-step.html phase="beta" %}
      {% endif %}

      <a href="#">Return to top</a>

    </div>

  </li>

  {% endfor %}

  {% if site.data.resources-help %}
  <li>
    <h3 id="{{ site.data.resources-help.title | downcase | replace: ' ', '-' }}" class="usa-accordion-button"
      aria-expanded="false"
      aria-controls="{{ site.data.resources-help.number }}">
      {{ site.data.resources-help.title }}
    </h3>
    <div id="{{ site.data.resources-help.number }}" class="usa-accordion-content secondary-accordion-content">

      {{ site.data.resources-help.copy | markdownify }}

      <a href="#">Return to top</a>

    </div>

  </li>
  {% endif %}

</ul>

{% endif %}


<hr>

{% include include-service-design-footer-nav.html data="live" %}
