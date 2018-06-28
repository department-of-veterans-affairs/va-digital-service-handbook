---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Discovery
description: Discovery is not about solutions; it’s about problems. Before you start designing or building a service, you need to find out who the potential users are and what problems your service could solve for them.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Planning for discovery
  - During discovery
  - Completing discovery
  - Resources and help
#
# Don't edit items below - they control the page layout
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/discovery
#
---

### What is Discovery?

It's tempting to start brainstorming solutions right away based on your understanding of your project. Doing that leads to a solution-oriented design process in which your team's primary question is: How do we build the solution?

Instead focus on a user-centered design process in which your team's primary questions are: Who are the potential users of my service, and how can we design a service that meets their needs?

Your goal in the discovery phase is to learn about real users and identify the problem(s) your service could solve for them. The best way to do this is to [talk to real users](resources/research). Go out and find people who will be using the service. Talk to them, observe them, and learn what they need and want.

The following sections will guide you in meeting the Digital Standard for discovery.
{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Planning for discovery

#### Timeframe

It's important to start the project by putting a time constraint on your discovery work. Plan to spend
  * 2 to 4 weeks on discovery for a new feature
  * 4 to 8 weeks for a new service

#### The team you need

Discovery is not just the work of user researchers. Involve your whole team in the discovery phase and make sure they understand their responsibilities. This helps everybody on the team focus on building a user-centered service.

For discovery, you'll need people dedicated to the following roles

* Product manager
* User researcher
* User Experience designer
* Technology lead  
* Content writer
* Project manager
* <span class="todo">these could be made more specific to VA ?</span>

#### Project Management

Make sure to use your team's Github "Product" folder to share your discovery materials.

#### At the end of discovery

At least a week before discovery ends, schedule a **Next Steps workshop** to share your team's recommended next steps (and your reasons). [Find out how to schedule it, who will attend, and how to prepare]().

<a href="#">Return to top</a>

<hr>

### During discovery

#### Focus on answering these key questions

* Who are your users?
* What are they trying to do? What tasks are they trying to accomplish?
* How do they do that currently?
* What problems or frustrations do they experience in trying to achieve their goals?
* What do users need from your service to achieve their goals?
* If your research findings show a need for the service, how would you start building a technical solution?

#### Using these activities

* Conduct **[user research](resources/research)** to learn about potential users of your service through interviews, observation, and testing
* Decide who the primary user groups will be
* Analyze any existing VA or private-sector services that meet user needs
* Understand current VA policy, technology, and business process related to your service
* Identify policies or other barriers that could make it difficult to meet user needs
* Explore the **[technical landscape](resources/technical-research)**
* Document findings from your user research and technical exploration
* Use insights from your findings to create a plan for what the team will work on during the alpha phase

<a href="#">Return to top</a>

<hr>

### Completing discovery

#### By the end of discovery, your team should have answers to these questions

* What user problems and needs will the service solve (what is the scope of the service)?
* What are the specific user needs and user stories the service will address?
* What specific things do you plan to prototype and test during the alpha phase?
* What people and/or resources do you need to support the work during the alpha phase?
* What are the metrics you'll use to measure the success of the service, and what is your plan to get those metrics?

#### So you can confidently recommend one of these discovery outcomes

* **Move on to [alpha](alpha)** &mdash; The team feels confident they've answered the key questions and are ready to move to the alpha phase
* **Spend more time in discovery** &mdash; The team has additional questions that need to be answered before moving to the alpha phase
* **Stop the project** &mdash; The discovery findings indicate that the project should be stopped
  > **Stopping after the discovery phase is not a failure.**
  <br/>The purpose of discovery is to understand users and find out what they need. This may mean you need to change plans or take a new direction. **Finding this out in the discovery phase is the best possible outcome** (vs. finding out after you've built it or launched it).
  <br/>Your team should recommend stopping after discovery if your findings show
    > * There's no user need for the service you planned to build
    > * User needs are already being met by another service &mdash; whether government or private-sector
    > * Technology or policy constraints mean you won’t be able to build a service that meets the user needs you have found
    > * It’s not cost-effective to develop the service

<a href="#">Return to top</a>

<hr>

### Resources and help

<!--
#### Tools

* Github - how to use
* Slack - how to use
* <span class="todo">others ?</span>
-->

#### Resources

During the discovery phase, focus on answering questions (rather than focusing on specific deliverables or process).

Below you'll find example deliverables other teams have made in order to answer the discovery questions (along with blank templates you can use). Feel free to use these!

* [User research resources](resources/research)
* [Technical resources](resources/technical-ex)


#### How to get help during discovery

* If you have a question about something in the Handbook, or need help in a specific subject area or discipline, contact [{{site.data.resources.contact-handbook.email}}](mailto:{{site.data.resources.contact-handbook.email}}).


#### How discovery aligns with Veteran Integrated Process (VIP)

* fill in here

<hr>

<div style="float:left;"><a href="#">Return to top</a></div>
<div style="float:right;"><a href="alpha">Next phase: Alpha ></a></div>
