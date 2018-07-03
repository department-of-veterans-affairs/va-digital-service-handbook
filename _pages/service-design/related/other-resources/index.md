---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Additional resources
description: The Service Design Guide refers to the following resources. They're collected here for easy reference.
#
# Don't edit items below - they control the page layout
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/related/other-resources
#
---

### Research resources

{% for item in site.data.navigation %}

  {% for subitem in item.subitems %}

    {% if subitem.title == "Related guides" %}

      {% for tertitem in subitem.tertitems %}

        {% if tertitem.title == "Other resources" %}

          {% for quaditem in tertitem.quaditems %}

            {% if quaditem.phase == "research" %}

* <a title="{{ quaditem.title }}" href="{{ quaditem.linkto}}"{% if quaditem.target == true %} target="_blank"{% endif %}>{{ quaditem.title }}</a>
{{ quaditem.description }}

            {% endif %}

          {% endfor %}

        {% endif %}

      {% endfor %}

    {% endif %}

  {% endfor %}

{% endfor %}

<hr>

### Technical resources

{% for item in site.data.navigation %}

  {% for subitem in item.subitems %}

    {% if subitem.title == "Related guides" %}

      {% for tertitem in subitem.tertitems %}

        {% if tertitem.title == "Other resources" %}

          {% for quaditem in tertitem.quaditems %}

            {% if quaditem.phase == "technical" %}

* <a title="{{ quaditem.title }}" href="{{ quaditem.linkto}}"{% if quaditem.target == true %} target="_blank"{% endif %}>{{ quaditem.title }}</a>
{{ quaditem.description }}

            {% endif %}

          {% endfor %}

        {% endif %}

      {% endfor %}

    {% endif %}

  {% endfor %}

{% endfor %}


<hr>

### Resources for managing work

{% for item in site.data.navigation %}

  {% for subitem in item.subitems %}

    {% if subitem.title == "Related guides" %}

      {% for tertitem in subitem.tertitems %}

        {% if tertitem.title == "Other resources" %}

          {% for quaditem in tertitem.quaditems %}

            {% if quaditem.phase == "work" %}

* <a title="{{ quaditem.title }}" href="{{ quaditem.linkto}}"{% if quaditem.target == true %} target="_blank"{% endif %}>{{ quaditem.title }}</a>
{{ quaditem.description }}

            {% endif %}

          {% endfor %}

        {% endif %}

      {% endfor %}

    {% endif %}

  {% endfor %}

{% endfor %}
