---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Alpha
description: Alpha is about testing hypotheses with users. Your goal in alpha is to figure out how to meet the user needs you identified in discovery. Use alpha as your chance to test many different approaches with real users before building your service.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Planning for alpha
  - During alpha
  - For designers and developers
  - Completing alpha
  - Resources and help
#
# Don't edit items below - they control the page layout
#
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/alpha
#
---

### What is Alpha?

* The primary objective of alpha is to answer the question: *How can your team best meet the user needs you identified in discovery?*

* The primary outcome of alpha is *a clear definition of your **Minimum Viable Product (MVP)** and a solid plan for how you'll build it.*
  > The MVP is the first working version of your service, which you'll build in the next phase &mdash; beta. Your MVP will be the smallest set of working functionality you can build that provides value to your users &mdash; by meeting their basic needs.
  <br/>The alpha phase is about figuring out what those basic user needs are, and how you'll meet them.

During the alpha phase, you'll iteratively design and test potential solutions. You'll build prototypes quickly and test them with users. You'll then use the feedback and testing results to improve the next prototype.

You'll repeat this process until the prototype meets your users' needs and your team is confident they know what the MVP will be and how to build it.

The following sections will guide you in meeting the Digital Standard for alpha.
{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### Planning for alpha

#### Timeframe

Different services will spend different amounts of time in alpha, depending on the complexity of what the team needs to prototype and test. In general, plan to spend
  * 2 to 4 weeks for a new feature
  * 6 to 8 weeks for a new service

#### The team you need

See [team structure](related/other-resources/team-structure) to understand the skillsets you'll need throughout the service lifecycle.

#### At the end of alpha

At least a week before alpha ends, schedule a [Next Steps checkpoint](related/other-resources/next-steps-checkpoint) to share your team's recommended next steps (and your reasons).

<a href="#">Return to top</a>

<hr>


### During alpha

#### 1. Test hypotheses quickly

To get to a clear definition of your MVP, you'll need to test many different hypotheses. Your objective is to identify potential issues &mdash; and learn from them &mdash; while you still have time to make corrections.

Different services will have different hypotheses to test during alpha. There's not a one-size-fits-all set of hypotheses to test. *But teams who are successful in the alpha phase do follow a similar process &mdash; design sprints.*

A design sprint takes 1-2 weeks and is designed to solve important design or business challenges. Each design sprint starts with brainstorming activities that lead to a prototype that is tested with real users &mdash; all within the span of 1-2 weeks.
<br/>

<hr>

#### 2. Create an alpha plan

Before you start your design sprints, map out your work over the course of the alpha phase. Start by identifying your team's goals for the alpha phase. Consider these questions:

* Based on your discovery research and findings, what kinds of solutions make the most sense in terms of meeting your users' needs?
* Which of those would you like to move forward with and test?
* What are the biggest *design risks* in those solutions?
* What are the biggest *technical risks* in those solutions?
* What are the biggest *business or policy risks* in those solutions?
* What are your hypotheses about these risks and solutions?
<br/>

<hr>

#### 3. Plan a design sprint

Using the goals, solutions, risks, and hypotheses you've identified, map out your first design sprint.

* Each design sprint takes 1-2 weeks. So in an 8-week period, you might (realistically) do 3-5 design sprints.
* Don't test all your hypotheses at once. Target each design sprint to specific hypotheses.
* Test the most risky hypotheses first &mdash; the ones that, if your hypothesis is proven wrong, will derail your solution concept.
* Test your design/user experience hypotheses &mdash; for example, a single-page vs multi-page user flow.
* Test your technical hypotheses &mdash; for example, whether a specific Vets-API provides data in the format you need.
* Be sure to leave enough time at the end of your alpha phase to prepare for the [Next Steps checkpoint](related/other-resources/next-steps-checkpoint).
<br/>

<hr>


#### 4. Conduct design sprints

Use the following steps for each design sprint:

1. Review the current goals, hypotheses, and solution concepts with your team.
2. Sketch &mdash; use individual and group brainstorming activities to explore design solutions that will test your hypotheses.
3. Decide &mdash; select a single option to move on to testing.
4. Prototype &mdash; [create a simple prototype](#tips-for-building-prototypes) that tests the solution.
5. Test &mdash; test the prototype with real users and collect their feedback.
    * **Tip**: Your goal is to iterate quickly. So make sure you plan far enough in advance to recruit participants for each design sprint.
6. Analyze &mdash; assess the user feedback and decide how it impacts your solution concept.
7. Plan &mdash; plan your next design sprint incorporating what you've just learned into the next prototype.

    * **Tips**:
      * Involve all team members in alpha prototyping. This leads to better design outcomes and helps the team create a common understanding of the service.
      * You can learn more about design sprints at <a title="Go to google ventures" href="http://www.gv.com/sprint/" target="_blank">Google Ventures</a>, as well as <a title="Go to design sprint kit" href="https://designsprintkit.withgoogle.com" target="_blank">Google's Design Sprint Kit</a> (a slight variation on the first link)

Keep iterating with your design sprints until your team can demonstrate you’ve met the user needs with the prototypes and the team is confident about moving on.

<hr>


#### <a name="tips-for-building-prototypes"></a>5. Tips for building prototypes

Prototypes only need to be realistic enough to get meaningful feedback that you can incorporate into your next prototype.

In earlier design sprints, your prototypes can be
* Simple paper sketches
* Wireframes that use images to show the functional elements of your service
* Clickable mockups that mimic the functionality of your service
* See <a title="Go to example" href="" target="_blank">an example</a>

In later prototypes, you can start mimicking your service's working logic. But these do not necessarily require back-end integration.

* **Tip**: You'll build the actual integrations in the beta phase. Use the alpha phase to figure out **how you'll do that** from a technical perspective. And only build and test the parts of the integration critical to **making decisions about how** to build them.

Think of each prototype as a proof of concept and use it to answer these questions:

* Do you have the right solution that meets your users' needs?
* Is your solution approach viable?
* Do the technologies exist to implement your solution?
* Do you understand how to use and/or integrate those technologies into our solution?
* Are there any parts of the solution that won't be easy to build or change later? If so, are you comfortable moving forward despite these?
* Are there existing processes or policies that will need to change to support your service?

<a href="#">Return to top</a>

<hr>


### For designers and developers

In the beta phase, you'll need to nail down answers to the following questions. But you may want to start thinking about them now.

**Designers and Writers**
* What will you call your service? Explore and test some options with users.
* How might VA promote the new service? Are there other VA websites where a callout would make sense?
* How will users find and get to your service? Think about how your service might be integrated into the sitewide navigation and from the main content hubs.
* Does the solution suggest a need for a new design pattern?

**Developers**
  * Does the order of the screens mean any changes to schema or suggest difficult data handling?
* If users need to upload something, how will the uploaded information be stored/sent?
* Can you submit structured data directly? Or do you need to create a PDF for submission? Both?
* Are any required backend services frequently (or predictably) unavailable? What kind of messaging to the user will you need?

<a href="#">Return to top</a>

<hr>


### Completing alpha

#### By the end of alpha, your team should have the following

* A clear vision and definition for the MVP service you'll build in beta (its scope)
* Thoroughly tested prototypes that demonstrate the design of the MVP service
* A list of user stories and features for the MVP service
* A clear understanding of the technology that will support the MVP service (and an understanding of how the technology might evolve for later releases)
* An understanding of other VA systems you need to replace or integrate with
* A proposed set of metrics to measure your service’s success
* Documentation of the user research you did in the alpha phase
* A plan and timeline for your beta phase
* An updated resource plan (if you need additional people or other resources for the beta phase)


#### So you can confidently recommend one of these alpha outcomes

* **Move on to [beta](beta)** &mdash; The team feels confident they've tested their hypotheses, understand how to build the MVP service, and are ready to move to the beta phase
* **Spend more time in alpha** &mdash; The team has additional (or new) hypotheses they want to test before moving to the beta phase
* **Stop the project** &mdash; The alpha findings indicate that the project should be stopped
  > **Stopping after the alpha phase is not a failure.**
  <br/>The purpose of alpha is to figure out how you might build a solution to meet your users' needs. This may mean you need to change plans or take a new direction. **Finding this out in the alpha phase is the best possible outcome** (vs. finding out after you've built it or launched it).
  <br/>Your team should recommend stopping after alpha if your findings show
    > * There's no user need for the service you planned to build
    > * User needs are already being met by another service &mdash; whether government or private-sector
    > * Technology or policy constraints mean you won’t be able to build a service that meets the user needs you've found
    > * It’s not cost-effective to develop the service

<a href="#">Return to top</a>

<hr>


### Resources and help

* Review [Next Steps checkpoint](related/other-resources/next-steps-checkpoint) to understand how to document your alpha findings and prepare for your Next Steps meeting.

* Review the following for information, examples, and templates you can use in the alpha phase:

  * [User research guide](related/user-research)
  * [Design guide](related/design)
  * <a title="Go to content guide" href="https://github.com/department-of-veterans-affairs/vets.gov-content-style-guide" target="_blank">Content guide</a>
  * [Technical guide](related/technical)
  * [Team management guide](related/team-mgmt)

* If you have a question about something in the Handbook, or need help in a specific subject area, [email us](mailto:{{site.contact-handbook.email}}). Or, post your question in the #dsva-platform-project Slack channel.

* To learn more about Agile project management, start with this <a title="Go to agile overview" href="https://www.gov.uk/service-manual/agile-delivery/agile-government-services-introduction" target="_blank">overview from Gov.UK</a>.
<br/>

<hr>

{% include include-service-design-footer-nav.html data="beta" %}
