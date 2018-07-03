---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Discovery
description: Discovery is not about solutions; it’s about uncovering problems. Before you start designing or building a service, you need to find out who the potential users are and what problems your service could solve for them.
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

Your goal in the discovery phase is to **learn about real users and identify the problem(s) your service could solve for them**. The best way to do this is to [talk to real users](guides/user-research). Go out and find people who will be using the service. Talk to them, observe them, and learn what they need and want.

The following sections will guide you in meeting the Digital Standard for discovery.
{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Planning for discovery

#### Timeframe

It's important to start the project by putting a time constraint on your discovery work. Plan to spend
  * 2 to 4 weeks for a new feature
  * 4 to 8 weeks for a new service

#### The team you need

See [team structure](resources/team-structure) to understand the skillsets you'll need throughout the service lifecycle.

#### At the end of discovery

At least a week before discovery ends, schedule a [Next Steps checkpoint](resources/next-steps-checkpoint) to share your team's recommended next steps (and your reasons).

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

* Define a **[problem statement](resources/problem-statement)** that you think your service will solve for your users
* Conduct **[user research](guides/user-research)** to learn about potential users of your service through interviews, observation, and testing
* Decide who the primary user groups will be
* Analyze any existing VA or private-sector services that meet user needs
* Understand current VA policy, technology, and business process related to your service
* Identify policies or other barriers that could make it difficult to meet user needs
* Review the <a title="Go to developer documentation" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started" target="_blank">**developer documentation**</a> and conduct **[technical discovery](resources/technical-discovery)**
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

* Review [Next Steps checkpoint](resources/next-steps-checkpoint) to understand how to document your discovery findings and prepare for your Next Steps meeting.

* Review the following for information, examples, and templates you can use in the discovery phase:

  * [User research guide](guides/user-research)
  * [Design guide](guides/design)
  * <a title="Go to content guide" href="https://github.com/department-of-veterans-affairs/vets.gov-content-style-guide" target="_blank">Content guide</a>
  * [Technical guide](guides/technical)
  * [Team management guide](guides/team-mgmt)

* If you have a question about something in the Handbook, or need help in a specific subject area, [email us](mailto:{{site.contact-handbook.email}}). Or, post your question in the #dsva-platform-project Slack channel.
<br/>


<hr>

{% include include-service-design-footer-nav.html data="alpha" %}
