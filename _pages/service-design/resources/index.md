---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Service Design Resources
description: Resources you can use throughout the service lifecycle.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - User research resources
  - Technical resources
  - Project management resources
#
# Don't edit items below - they control the page layout
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/resources
#
---
### Introduction

Be sure to read through the Service Design Guide to understand how you to use these resources in each project phase.
{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### User research resources

* [Prioritizing your research questions ]({{site.data.resources.workshop-research-questions}})
  * If you have remote team members, you'll need to modify the workshop instructions to include those team members.

* Creating a research plan - [example]({{site.data.resources.research-plan-ex}}) - [template]({{site.data.resources.research-plan-template}})

* [Learn how to identify user groups]({{site.data.resources.identify-user-groups}})

* [Choosing a research method]({{site.data.resources.choose-research-method}})

* Creating personas - [example1]({{site.data.resources.persona-1}}) - [example2]({{site.data.resources.persona-2}})

* Creating user profiles - [example1]({{site.data.resources.user-profiles-1}}) - [example2]({{site.data.resources.user-profiles-2}})


### Technical resources
* [Technical exploration](linkhere)

### Project management resources
