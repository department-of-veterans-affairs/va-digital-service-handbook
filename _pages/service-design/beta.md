---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Beta
description: Beta is about incrementally building &mdash; and testing along the way &mdash; the user stories and features from your backlog, so you can launch the first working version of your service at the end of the beta phase.  
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Planning for beta
  - Build and deploy to staging
  - Prepare for launch
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

In the beta phase, it's tempting to try to build all the features and functionality you imagine for your service. But stay focused on your MVP. **As soon as your service can provide value by meeting your users' basic needs, it’s ready to launch!**

During beta, you'll build the user stories and features from your backlog in small batches of functionality. As you build these batches, you'll test them with your users to ensure they work well. Then you'll use that user feedback to refine your service, adding and adjusting features until your MVP service is complete.

The following sections will guide you in meeting the Digital Standard for beta.

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>


<div id="planning-for-beta" class="usa-accordion secondary-accordion">

  <h3 class="usa-accordion-button" aria-expanded="false" aria-controls="planning">
    Planning for beta
  </h3>

</div>

<div id="planning" class="usa-accordion-content secondary-accordion-content" markdown="1">

Different services will spend different amounts of time in beta, depending on what the team plans to build as the MVP. In general, plan to spend

* 6-8 weeks for a new feature
* 8-12 weeks for a new service
* **Tip**: If your planned MVP will take longer than 12 weeks to build and test, you should reconsider the [scope of your MVP](alpha#scoping-your-mvp) &mdash; make it smaller!

#### The team you need

See [team structure](related/other-resources/team-structure) to understand the skillsets you'll need throughout the service lifecycle.

#### At the end of beta

At least a week before beta ends, schedule a [Next Steps checkpoint](related/other-resources/next-steps-checkpoint) to share your team's recommended next steps (and your reasons).

<a href="#">Return to top</a>

</div>

<hr>


### Build and deploy to staging

Map out a beta plan that groups the user stories and features from your MVP backlog into small, testable chunks that you can build, deploy, and test iteratively.

Then use your beta plan to

#### 1. Develop incrementally by coding locally and deploying to staging as you go

* See the <a title="Go to developer workflow" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/development-workflow.html" target="_blank">example development workflow</a>.

* Do automated testing each time you deploy to staging

  * <a title="Go to 508 testing" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/building-and-testing/automated-testing" target="_blank">Automated accessibility (508 compliance) testing</a>
  * <a title="Go to testing" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/vets-website/forms/tests" target="_blank">Automated unit and end-to-end tests</a>

#### 2. Plan and conduct [research sprints](related/user-research#plan-a-research-sprint)

* These sprints should focus on <a title="Go to usability testing" href="https://methods.18f.gov/validate/usability-testing/" target="_blank">usability testing</a> to ensure that your staged user stories and features work well for your users.

    * Analyze and synthesize the user feedback you collect.
    * Document your research findings.
    * Use your research findings to refine your beta plan &mdash; adjusting existing features and adding new features (if these are critical to supporting your users' basic needs).

#### 4. Continue this cycle  

* Until you've deployed all the features you planned for the MVP service

* Or, until the MVP provides value by meeting your users' basic needs

<a href="#">Return to top</a>

<hr>


### Prepare for launch

**Note**: Some of these tasks impact each other. For example, if you change the information architecture, you'll need to test and QA again, and you may need to update the metrics you've set up in Google Analytics.

#### 1. Finalize [information architecture](related/ia) for your service

* [Contact the DSVA team](mailto:{{ site.contact-handbook.email }}) to coordinate.


#### 2. Finalize [ATO](related/ato) details

* [Contact the DSVA team](mailto:{{ site.contact-handbook.email }}) to coordinate.


#### 3. Finalize [marketing and communications materials](related/marcom)


#### 4. Conduct <a title="Go to qa testing" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/building-and-testing/qa" target="_blank">end-to-end QA testing</a>


#### 5. Set up and test <a title="Go to Google Analytics setup" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/google-analytics" target="_blank">Google Analytics</a>

#### 6. Load test your service


#### 7. Perform [user acceptance testing (UAT)](related/uat)


#### 8. Set up live service details

* Monitoring and logging
* Alert configuration
* Rate limits


#### 9. Schedule a walkthrough with VA's 508 office


#### 10. Review your MVP with the [Help Desk](related/helpdesk)

* Finalize your Help Desk content after you've completed all the steps above.
* Then schedule the review.


#### 11. [Create a post-launch plan](related/post-launch-plan) that describes

* Your revised backlog of user stories and features
* How you plan to continue improving the live service after you launch it


<a href="#">Return to top</a>

<hr>


### Completing beta

#### By the end of beta, your team should have the following

* A fully-functioning version of your service that meets your users' basic needs
* A list of major bugs and usability issues that have been identified and fixed
* Documentation of the user research and testing you did in the beta phase
* The metrics you've set up to measure your service's success (and a plan for how you'll monitor and evaluate those metrics)
* A backlog of features to complete post-launch in order to improve the service
* A proposed plan for how you'll monitor, evaluate, user research/test, and build those features during the live phase
* An updated resource plan (if you need additional people or other resources for the live phase)


#### So you can confidently recommend one of these beta outcomes

* **Move on to [live](live)** &mdash; The team feels confident the MVP meets users' basic needs, and they are ready to move to the live phase
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


<div id="resources-and-help" class="usa-accordion secondary-accordion">

  <h3 class="usa-accordion-button" aria-controls="resources">
    Resources and help
  </h3>

</div>

<div id="resources" class="usa-accordion-content secondary-accordion-content" markdown="1">

* Review [Next Steps checkpoint](related/other-resources/next-steps-checkpoint) to understand how to document your beta findings and prepare for your Next Steps meeting.

* Review the following for information, examples, and templates you can use in the beta phase:

  * [User research guide](related/user-research)
  * [Design guide](related/design)
  * <a title="Go to content guide" href="https://github.com/department-of-veterans-affairs/vets.gov-content-style-guide" target="_blank">Content guide</a>
  * [Technical guide](related/technical)
  * [Team management guide](related/team-mgmt)

* If you have a question about something in the Handbook, or need help in a specific subject area, [email us](mailto:{{site.contact-handbook.email}}). Or, post your question in the #dsva-platform-project Slack channel.

* To learn more about Agile project management, start with this <a title="Go to agile overview" href="https://www.gov.uk/service-manual/agile-delivery/agile-government-services-introduction" target="_blank">overview from Gov.UK</a>.

</div>

<br/>

{% include include-service-design-footer-nav.html data="live" %}
