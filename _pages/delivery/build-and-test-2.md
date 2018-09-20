---
#
modified-date: September 19, 2018
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on the page and in HTML meta tags
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

* Is the MVP solution consistent with other Veteran Tools Platform design patterns?

* Is the MVP solution accessible?

* Which metrics make sense to measure the success of the MVP?

* What business or policy changes are needed for the MVP?

<hr>

### MVP activities

* Create a *Build and Test* plan that groups the user stories and features you've identified for the MVP into small, testable chunks that you can build, deploy, and test iteratively.

* **<a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-ia-review.md#prepare-for-an-ia-review" target="_blank">Define the information architecture</a>** for your MVP.

* **<a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-ato-reviews.md#request-a-preliminary-ato-review" target="_blank">Request a preliminary ATO review</a>** for your MVP.

* **<a title="Go to developer workflow" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/development-workflow.html" target="_blank">Incrementally develop, deploy, and test</a>** small chunks of the MVP.

  1. Code locally and deploy to staging (with automated testing).

      * <a title="Go to 508 testing" href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Testing/508-automated-testing.md" target="_blank">Automated accessibility (508 compliance) testing</a>

      * <a title="Go to testing" href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Testing/unit-testing.md" target="_blank">Automated unit testing</a> and <a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Testing/end-to-end-testing.md" target="_blank">automated end-to-end testing</a>

  1. **Conduct [user research]({{site.baseurl}}/resources/user-research#plan-a-research-sprint)** to test the deployed features.

      * Focus on <a title="Go to usability testing" href="https://methods.18f.gov/validate/usability-testing/" target="_blank">usability testing</a> to ensure that your staged user stories and features work well for your users.

      * Analyze and synthesize the user feedback you've collected.

      * Document your research findings.

      * Use your research findings to refine your *Build and Test* plan &mdash; adjusting existing features and adding new features (if these are critical to supporting your users' basic needs).

  3. Repeat the cycle of developing incrementally and conducting user research until one of the following is true

      * You've deployed all the features you planned for the MVP service

      * The MVP provides value by meeting basic user needs

* **<a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-ia-review.md#request-an-ia-review" target="_blank">Request an IA Review</a>** for your MVP.


* When you've deployed and tested all your MVP features on staging, 
  * **<a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-design-qa.md" target="_blank">Request a Design QA</a>**.

  * **<a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-content-qa.md" target="_blank">Request a Content QA</a>**.

  * **[Complete the Pre-launch activities](#pre-launch-activities)**.

* Define the metrics you'll use to measure the success of the MVP.

* Create a prioritized backlog of features you plan to build after the MVP launches.

* Create a plan for the *Learn and Improve* phase &#8212; how you’ll monitor, evaluate, user research/test, and build from your backlog.

<hr>

### Pre-launch activities

**Note**: Some of these tasks impact one another. For example, if you change the information architecture, you'll need to test and QA again, and you may need to update the metrics you've set up in Google Analytics.

1. If you've made any changes to your service's information architecture (page titles, URLs, navigation) since your last IA Review with DSVA, you must <a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-ia-review.md#request-an-ia-review" target="_blank">request another IA Review</a>.

1. Request <a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-508-review.md" target="_blank">an Accessibility/508 review</a>.

1. Conduct <a title="Go to qa testing" href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Testing/cross-browser-manual-testing.md" target="_blank">cross-browser QA testing</a>.

1. Set up <a title="Go to Google Analytics setup" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/google-analytics" target="_blank">Google Analytics</a>.

1. Request a <a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Reviews-External-Contractors/request-ato-reviews.md#request-a-pre-launch-ato-review" target="_blank">Pre-launch ATO review</a>.

1. Load test your service.

1. Finalize [marketing and communications materials]({{site.baseurl}}/resources/more/marcom).

1. Perform [user acceptance testing (UAT)]({{site.baseurl}}/resources/more/uat).

1. Review your MVP with the [Call Center]({{site.baseurl}}/resources/more/call-center).

<!--1. Set up [live service details]({{site.baseurl}}/resources/more/service-details).-->


<br/>
