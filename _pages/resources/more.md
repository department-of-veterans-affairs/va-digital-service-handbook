---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on the page and in HTML meta tags
#
title: More resources
description: Activity-specific guides to help you throughout the service lifecycle.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - Doing user research
  - During the discovery phase
  - During the alpha phase
  - During the beta phase
  - During the live phase
  - Tools, resources, and examples
#
# Editable - Pagination for bottom of page
#
pagination: yes
phase-prev: none
page-prev: none
phase-next: none
page-next: none
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
# same name for sidebar + pagination include
sidebar-page-type: /resources
permalink: /resources/more
---

{{ site.pages }}


{% for pageit in site.pages.resources.more %}
{{ pageit }}

{% endfor %}










{% for item in site.data.navigation %}

  {% for subitem in item.subitems %}

    {% if subitem.title == "Related guides" %}

      {% for section in subitem.tertitems %}

        {% if section.target == true %}

* <a title="{{ section.title }}" href="{{ section.linkto}}" target="_blank">{{ section.title }}</a>
  {{ section.description }}

        {% else %}

* [{{ section.title }}]({{ section.linkto  | relative_url }})
  {{ section.description }}

        {% endif %}

      {% endfor %}

    {% endif %}

  {% endfor %}

{% endfor %}

<hr>
