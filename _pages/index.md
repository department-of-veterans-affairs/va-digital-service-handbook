---
#
# See the Github wiki for how to use Markdown in the editable content below:
# link here
#
# You can edit this SECTION CONTENT
#
section-1-image: assets/img/home-section-1.png
section-1-title: Modern, user&#8209;friendly digital services
section-1-link: digital-standard
section-1-alt: Design modern, user-friendly digital services
section-1-copy: The <a title="Digital Service Standard" href="digital-standard">Digital Service Standard</a> describes the quality standards for modern, user&#8209;friendly digital services on the Veteran Tools Platform.
#
section-2-image: assets/img/home-section-2.png
section-2-title: Agile, user&#8209;centered delivery
section-2-link: service-design/
section-2-alt: Agile, user-centered delivery
section-2-copy: The <a title="Service Design Guide" href="service-design/">Service Design Guide</a> helps VA teams meet the <a title="Digital Service Standard" href="digital-standard">Digital Service Standard</a> by engaging with users and using best practices for agile delivery.
#
section-3-image: assets/img/home-section-3.png
section-3-title: Veteran Affairs<br/>APIs
section-3-link: https://department-of-veterans-affairs.github.io/vets-contrib
section-3-alt: Veteran Affairs APIs
section-3-target: yes
section-3-copy: <a title="Veteran Affairs APIs" href="https://department-of-veterans-affairs.github.io/vets-contrib" target="_blank">Veteran Affairs APIs</a> empower our partners to build innovative, Veteran&#8209;centered, cutting edge solutions they can use to manage their care, services, and benefits.
#
# You can edit this DESCRIPTION CONTENT
#
subhead: Empowering VA teams to build digital services on the Veteran Tools Platform
p1: We created this Handbook based on VA's experience with <a title="Vets.gov" href="https://www.vets.gov" target="_blank">Vets.gov</a>, as well as best practices from government digital services, government agencies, and the technology industry. It's a tool to help VA teams create the best possible user experience for people interacting with Veteran-facing digital services.
p2: This Handbook provides direction for teams who want to build on the <i>Veteran Tools Platform</i> (the technologies and processes that support Vets.gov). But we hope other VA teams find it useful when building their own digital services.
alert-title: Work in progress
alert-copy: We're currently expanding and refining this Handbook.<br/>We encourage you to adopt as much of it as possible and <a title="Share feedback" href="contact">share your feedback</a>.
#
#
# Don't edit items below - they control the page layout
return-top: no
layout: home
permalink: /
page-type: home
twitter_card: large
section-image-1: assets/img/square-90.png
section-image-2: assets/img/square-90.png
section-image-3: assets/img/square-90.png
#
---

{{ content }}

<!--
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
-->
