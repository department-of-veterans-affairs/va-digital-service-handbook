---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Beta
description: Beta description goes here.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Planning for beta
  - During beta
  - For designers and developers
  - Completing beta
  - Resources and help
#
# Don't edit items below - they control the page layout
#
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/beta
#
---

### What is Beta?

In the alpha phase, your team created a prioritized list of user stories and features (the backlog) for your MVP. Your goal in the beta phase is to turn that backlog into a working version of your service, which you'll launch at the end of the beta phase.

During beta, you'll build the user stories and features from your backlog in small batches of functionality. As you build these batches, you'll test them with your users to ensure they work well. Then you'll use that user feedback to refine your service, adding and adjusting features until your MVP service is complete.

In the beta phase, it's tempting to try to build all the features and functionality you imagine for your service. But stay focused on your MVP. **As soon as your service can provide value by meeting your users' basic needs, it’s ready to launch!**

> The backlog is never complete. Throughout the beta and lives phases, you'll collect new user feedback and update your backlog with more features and improvements.

The following sections will guide you in meeting the Digital Standard for beta.

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>


### Planning for beta

Different services will spend different amounts of time in beta, depending on what the team plans to build as the MVP. In general, plan to spend
  * 6-8 weeks for a new feature
  * 8-12 weeks for a new service
  * **Tip**: If your planned MVP will take longer than 12 weeks to build and test, you should reconsider the [scope of your MVP](alpha#scoping-your-mvp) &mdash; make it smaller!

#### The team you need

See [team structure](related/other-resources/team-structure) to understand the skillsets you'll need throughout the service lifecycle.

#### At the end of beta

At least a week before beta ends, schedule a [Next Steps checkpoint](related/other-resources/next-steps-checkpoint) to share your team's recommended next steps (and your reasons).

<a href="#">Return to top</a>

<hr>


### During beta

1. Develop incrementally.
2. Put on staging - see the workflow info in platform docs; do automated 508 testing as part of that plus unit and end to end tests;
3. validate with users what you put on staging - follow the steps in the user research guide to test/validate with users
4. do qa testing
5. set up analytics
6. load test
7. content review?
8. urls and ia ? - how to integrate post merger?
9. marketing plus communications
10. written a Help Desk guide
11.

improve your service by testing it with users based on the user stories you created in the alpha phase
solve any technical or process-related challenges so that your service meets the Digital Service Standard
get the service accredited
make a plan for the launch of your service (get a GOV.UK domain name and start and end pages and arrange SSL certificates)
release updates and improvements into the development environment
measure the effect of any changes to the Key Performance Indicators (KPIs) you established in discovery and alpha, for example if you changed KPIs because of new data
carry out regular accessibility testing and get an accessibility audit
test the assisted digital support model you designed for your service

<a href="#">Return to top</a>

<hr>


### For designers and developers


<a href="#">Return to top</a>

<hr>


#### By the end of beta, your team should have the following

* list


#### So you can confidently recommend one of these beta outcomes

* **Move on to [live](live)** &mdash; The team feels confident they've sdfsdf, and are ready to move to the live phase
* **Spend more time in beta** &mdash; The team has sdfsdf before moving to the live phase
* **Stop the project** &mdash; The beta findings indicate that the project should be stopped
  > **Stopping after the beta phase is not a failure.**
  <br/>The purpose of beta is to figure out how you might build a solution to meet your users' needs. This may mean you need to change plans or take a new direction. **Finding this out in the beta phase is the best possible outcome** (vs. finding out after you've launched it).
  <br/>Your team should recommend stopping after beta if your findings show
    > * There's no user need for the service you planned to build
    > * User needs are already being met by another service &mdash; whether government or private-sector
    > * Technology or policy constraints mean you won’t be able to build a service that meets the user needs you've found
    > * It’s not cost-effective to develop the service

<a href="#">Return to top</a>

<hr>


### Resources and help

* Review [Next Steps checkpoint](related/other-resources/next-steps-checkpoint) to understand how to document your beta findings and prepare for your Next Steps meeting.

* Review the following for information, examples, and templates you can use in the beta phase:

  * [User research guide](related/user-research)
  * [Design guide](related/design)
  * <a title="Go to content guide" href="https://github.com/department-of-veterans-affairs/vets.gov-content-style-guide" target="_blank">Content guide</a>
  * [Technical guide](related/technical)
  * [Team management guide](related/team-mgmt)

* If you have a question about something in the Handbook, or need help in a specific subject area, [email us](mailto:{{site.contact-handbook.email}}). Or, post your question in the #dsva-platform-project Slack channel.

* To learn more about Agile project management, start with this <a title="Go to agile overview" href="https://www.gov.uk/service-manual/agile-delivery/agile-government-services-introduction" target="_blank">overview from Gov.UK</a>.
<br/>

<hr>

{% include include-service-design-footer-nav.html data="live" %}
