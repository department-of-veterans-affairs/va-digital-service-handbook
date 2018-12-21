---
#
modified-date: December 20, 2018
#
# Editable - Title and Description display on the page and in HTML meta tags
#
title: Build and Test activities
description: During the <i>Build and Test</i> phase, focus on building features in small batches and testing those with real users.
#
# Editable - Pagination for bottom of page
#
pagination: yes
phase-prev: Build and Test
page-prev: introduction
phase-next: Build and Test
page-next: checklist
#
# Don't edit items below - they control the page layout
#
return-top: yes
layout: page
page-type: subpage
page-description: yes
# same name for sidebar + pagination include
sidebar-page-type: /delivery
permalink: /delivery/build-and-test/activities
#
---

### Key questions to answer

* Which user stories for the MVP are best suited to address basic user needs?

* Does the technical solution work at scale, and do its integrations with other services work well?

* Is the MVP solution consistent with other Veteran-facing Services Platform design patterns?

* Is the MVP solution accessible?

* Which metrics make sense to measure the success of the MVP?

* What business or policy changes are needed for the MVP?

<hr>

### MVP activities

During this phase, you'll build your MVP. You'll also complete other activities to support the launch of your service and to evaluate the readiness of your service to launch on the Veteran-facing Services Platform.

When you plan for this phase, be sure to include enough time for these activities. *Your Build and Test plan should include time before launch to fix any issues found during UAT and/or load testing.*

**Communications**
Talk with your DSVA Contact about how to create a communications plan for the launch of your service.

**Building and testing**
Group the user stories and features you've identified for the MVP into small, testable chunks that you can <a title="Go to developer workflow" href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/DeveloperDocs/development-workflow.md" target="_blank">build, deploy, and test iteratively</a>.

  1. Code locally and deploy to staging (with automated testing).

      * <a title="Go to 508 testing" href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/DeveloperDocs/testing/TEMP-508-automated-testing.md" target="_blank">Automated accessibility (508 compliance) testing</a>

      * <a title="Go to testing" href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/DeveloperDocs/testing/unit-testing.md" target="_blank">Automated unit testing</a> and <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/DeveloperDocs/testing/end-to-end-testing.md" target="_blank">automated end-to-end testing</a>

  1. **Conduct [user research]({{site.baseurl}}/resources/user-research)** to test the features you've deployed to staging.

      * Focus on <a title="Go to usability testing" href="https://methods.18f.gov/validate/usability-testing/" target="_blank">usability testing</a> to ensure that user stories and features work well for your users.

      * Analyze and synthesize the user feedback you've collected.

      * Document your research findings.

      * Use your research findings to refine your *Build and Test* plan &mdash; adjusting existing features and adding new features (if these are critical to supporting your users' basic needs).

  3. Repeat the cycle of developing incrementally and conducting user research until

      * You've deployed all the features you planned for the MVP service, or

      * The MVP provides value by meeting basic user needs

**Information architecture**
<a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-ia-review.md#prepare-for-an-ia-review" target="_blank">Define the information architecture</a> for your MVP. Then request an <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-ia-review.md#request-an-ia-review" target="_blank">Request an IA Review</a>.

**ATO**
<a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-ato-reviews.md#request-a-preliminary-ato-review" target="_blank">Request a preliminary ATO review</a> for your MVP.

**Success metrics**
Define the metrics you'll use to measure the success of the MVP.

**Continuous improvement**
* Create a prioritized backlog of features you plan to build after the MVP launches.

* Create a plan for the *Learn and Improve* phase &#8212; how you’ll monitor, evaluate, user research/test, and build from your backlog.

**[Complete pre-launch activities](#pre-launch-activities)**
Complete the pre-launch activities after you've completed all the MVP activities.
  

<hr>

### Pre-launch activities

Start these activities when the complete and final build is on staging and you've completed all the MVP activities.

1. Conduct <a title="Go to qa testing" href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/DeveloperDocs/testing/cross-browser-manual-testing.md" target="_blank">cross-browser QA testing</a>.

1. If you've made any changes to your service's information architecture (page titles, URLs, navigation) since your last IA Review with DSVA, <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-ia-review.md#request-an-ia-review" target="_blank">request another IA Review</a>.

1. <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-design-qa.md" target="_blank">Request a Design QA</a>.

1. <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-content-qa.md" target="_blank">Request a Content QA</a>.

1. Request <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-508-review.md" target="_blank">an Accessibility/508 review</a>.

1. Request a <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-contact-center-review.md" target="_blank">Call Center Review</a>.

1. Request a <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-ato-reviews.md#request-a-pre-launch-ato-review" target="_blank">Pre-launch ATO review</a>.

1. Set up <a title="Go to Google Analytics setup" href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-google-analytics.md" target="_blank">Google Analytics</a>.

1. Perform <a href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Work%20Practices/Product%20Management/UserAcceptanceTesting.md" target="_blank">user acceptance testing</a>.

1. <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Request-Reviews/request-load-testing.md" target="_blank">Load test</a> your service.

<!--1. Set up [live service details]({{site.baseurl}}/resources/more/service-details).-->


<br/>
