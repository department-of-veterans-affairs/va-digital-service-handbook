---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title displays on page and in meta
title: Welcome
#
# Don't edit items below - they control the page layout
return-top: no
layout: base
permalink: /
page-type: home
twitter_card: large
section-image-1: assets/img/square-90.png
section-image-2: assets/img/square-90.png
section-image-3: assets/img/square-90.png
#
# Title+Tagline in header are defined in config.yml
#
# To edit the Home Page content,
# see _data/homepage.yml
#
#
---

<main id="main-content"></main>

<section class="usa-hero">
  <div class="usa-grid">
    <div class="usa-hero-callout usa-section-dark hero-text">

      <h1>
        <span class="usa-hero-callout-alt">{{ site.title }}</span>
      </h1>

      <p>{{ site.tagline }}</p>

    </div>
  </div>
</section>


<section class="usa-section home-section">
  <div class="usa-grid home-block-container">

{% for item in site.data.homepage %}

  {% if item[0] == 'sections' %}

    {% for section in item[1] %}

    <div class="home-block">
      <img alt="{{ section.alt }}" src="{{ section.image }}" height="90">

      <h2>
        <a title="{{ section.alt }}" href="{{ section.link | relative_url }}"{%if section.target == true%} target="_blank"{% endif %}>{{ section.title }}</a>
      </h2>

      <p>{{ section.copy }}</p>
    </div>

    {% endfor %}

  {% endif %}

{% endfor %}

  </div>
</section>


<section class="usa-section home-secondary">
  <div class="usa-grid">

{% for item in site.data.homepage %}

  {% if item[0] == 'description' %}

    <div class="usa-width-one-third">
      <h3>{{ item[1].subhead }}</h3>
    </div>

    <div class="usa-width-two-thirds">
      <p>{{ item[1].p1 }}</p>

      <p>{{ item[1].p2 }}</p>

      <div class="usa-alert usa-alert-info" >
        <div class="usa-alert-body">
          <h4 class="usa-alert-heading">{{ item[1].alert-title}}</h4>
          <p class="usa-alert-text">{{ item[1].alert-copy }}</p>
        </div>
      </div>
    </div>

  {% endif %}

{% endfor %}

  </div>
</section>
