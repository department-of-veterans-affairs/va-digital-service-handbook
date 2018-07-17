---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Creating a product outline
description: Use a product outline to describe your problem statement and hypotheses and keep track of how your service evolves after the discovery phase.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Example - Product outline
  - Template - Product outline
#
# Don't edit items below * they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/related/other-resources/product-outline
#
---

### Creating a product outline

Each product outline is different depending on the service and how the team wants to use it.

The sections in the template below are suggestions, not requirements. Use them if your team finds them useful.

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Example - Product outline

#### Problem Statement
 Veterans have trouble applying for dependent benefits. Currently the only way they can apply is with paper form that they have to mail in. This leads to a lot of missing data that makes processing their applications difficult and they often have to wait a long time to receive a declaration.

#### Solution Goals
Our goal is to offer a way for to submit the 686 Dependents form on their computer or smartphone and reduce the amount of applications that come in with incomplete data.

#### Business Requirements
Veterans must be able to upload supporting documents in certain scenarios to support their dependent claim.

#### Research Insights
Veterans have indicated that one of most difficult parts of the 686 Form is gathering information on their Spouse's previous marriages. In addition, they don't understand why this information is relevant when applying to declare a dependent.

#### Solution Approach
We plan on building a digital form with React.js on the frontend and a backend submission connection to the Central Mail API. This will enable users to quickly submit the 686 form with supporting documentation on Vets.gov. We're shooting to launch a first version (MVP) of this form on June 1st, 2018.

#### Key Performance Indicators
- Decrease the time it takes for a user to get a dependents declaration
- Decrease the number of applications that are received with incomplete data
- Increase the number applications submitted

<a href="#">Return to top</a>

<hr>


### Template - Product outline


### [Service/Product Name] Outline
* GitHub Label:
* Slack channel:
* Vets.gov link:
* Demo video link:

### Table of contents

* **Summary**
  * [Problem statement](#user-problem-statement)
  * [Solution goals](#solution-goals)
  * [Assumptions](#assumptions)
  * [Requirements and constraints](#requirements-and-constraints)
  * [Discovery takeaways](#discovery-takeaways)
  * [Solution approach](#solution-approach)
  * [Value propositions](#value-propositions)
  * [KPIs](#kpis)

* **Implementation Information**
  * [Status](#status)
  * [Solution narrative](#solution-narrative)
  * [Team](#team)
  * [Resources and documentation](#resources-and-documentation)

<hr>

### Summary

#### Problem statement
<br/>

#### Solution goals

* **User goals**
<br/>

* **Business goals**
<br/>

#### Assumptions
<br/>

#### Requirements and constraints
<br/>

#### Discovery takeaways
<br/>

#### Solution approach
<br/>

#### Value propositions

* **User value**
<br/>

* **Business value**
<br/>

#### KPIs
<br/>

<hr>

### Implementation information

#### Status
<br/>

#### Solution narrative
* **Date**: summary of any big changes and why
* **Date**: summary of any big changes and why
<br/>

#### Team

* VA Executive Sponsor `*`:
* VA Policy Expert(s):
* VA Digital Strategist(s) `*`:
* Product Manager `*`:
* Design Lead:
* Engineering Lead:
* VA Web Comms Partner:
* VA Call Center Partner(s):
* Production Testing Partner(s):
* Designer(s):
* Content Writer(s):
* Front-end Engineer(s):
* Back-end Engineer(s):

  `*` = approval required for launch
  <br/>

#### Resources and documentation

* **Resources**
*provide links to the following*
  * Discovery and research
  * Technical documentation
  * Product specs
  * Design
  * Roadmap
  * ATO documentation
<br/>

* **How to access in staging**
  * Link:
  * Password protection info:
  * User authentication info:

<hr>
