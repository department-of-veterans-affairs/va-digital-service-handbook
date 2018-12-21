---
#
modified-date: December 20, 2018
#
# Editable - Title and Description display on the page and in HTML meta tags
#
title: Agile delivery guide
description: Information and resources about using agile methodologies as you work on the Veteran-facing Services Platform.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - Expectations
  - Managing your agile workflow
  - VA VIP deliverables
  - Getting help
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
# same name for sidebar + pagination include
sidebar-page-type: /resources
permalink: /resources/agile
#
---

### Using the Agile guide

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Expectations

Teams working on the Veteran-facing Services Platform are required to practice <a href="https://en.wikipedia.org/wiki/Agile_software_development" target="_blank">agile software development</a>. Teams working on the Veteran-facing Services Platform are responsible for organizing their own work into Epics, User Stories, and related sprints and code.

Because teams are all working on the same platform, *teams must use the same agile tools in the same way.* We do that using Github Issues and Zenhub (see [Managing your agile workflow](#managing-your-agile-workflow)).

If you have any questions, ask your DSVA contact.

<hr>


### Managing your agile workflow

Every Github repository (repo) has a section called "Issues." <a href="https://guides.github.com/features/issues/" target="_blank">Learn about Github Issues</a>.

The "Issues" section of the <a href="https://github.com/department-of-veterans-affairs/vets.gov-team" target="_blank">vets.gov-team repo</a> is where all teams working on the Veteran-facing Services Platform manage their Epics, User Stories, and agile workflow. *After completing the onboarding steps, you'll be able to see the vets.gov-team repo.*

All teams manage their agile workflow in 2-week sprints using Github and a Github integration called Zenhub, which turns Github Issues into a <a href="https://en.wikipedia.org/wiki/Scrum_(software_development)" target="_blank">scrum board</a>.

* Get started <a href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Work%20Practices/Onboarding%20and%20Offboarding/zenhub_onboarding.pdf" target="_blank">using Zenhub</a> ({{ site.vets-team }}).

* See <a href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Work%20Practices/Product%20Management/zenhub_product_management.pdf" target="_blank">how we use Zenhub for agile workflow</a> ({{site.vets-team}}).


<hr>

### VA VIP deliverables

Your contract may require you to submit specific VIP deliverables to VA. For some VIP deliverables, you may need information from the DSVA team and/or copies of our VA documents. Please reach out to your DSVA Contact if you have any questions about these documents.

For reference, we've colllected some example VIP deliverables created by other teams who have worked on the Veteran-facing Services Platform.

* [Project 1 examples](https://github.com/department-of-veterans-affairs/vets.gov-team/tree/master/Products/Disability%20Compensation/BAH-526/Deliverables)
* [Project 2 examples](https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Products/Facilities_Locator/community_care/VA-VIP-deliverables/README.md)
* If you need a copy of the DSVA Configuration Management Plan or the DSVA Production Operations Manual, please ask your DSVA Contact.


<hr>

### Getting help

DSVA resources are available to provide guidance and support throughout development and deployment.

* For process-related questions, ask in the *#{{site.slack.support}}* Slack channel.
* For product-related questions, ask in your team's "Product" Slack channel.

<hr>
