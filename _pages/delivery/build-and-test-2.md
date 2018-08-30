---
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

<!--
### Key questions to answer



<hr>
-->

### Activities

Map out a *Build and Test* plan that groups the user stories and features from your backlog into small, testable chunks that you can build, deploy, and test iteratively.

#### 1. Develop incrementally by coding locally and deploying to staging as you go.

* See the <a title="Go to developer workflow" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/development-workflow.html" target="_blank">example development workflow</a>.

* Do automated testing each time you deploy to staging.

  * <a title="Go to 508 testing" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/building-and-testing/automated-testing" target="_blank">Automated accessibility (508 compliance) testing</a>
  * <a title="Go to testing" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/vets-website/forms/tests" target="_blank">Automated unit and end-to-end tests</a>

#### 2. Plan and conduct [research sprints]({{site.baseurl}}/resources/user-research#plan-a-research-sprint).

  * Focus on <a title="Go to usability testing" href="https://methods.18f.gov/validate/usability-testing/" target="_blank">usability testing</a> to ensure that your staged user stories and features work well for your users.

  * Analyze and synthesize the user feedback you've collected.
  * Document your research findings.
  * Use your research findings to refine your *Build and Test* plan &mdash; adjusting existing features and adding new features (if these are critical to supporting your users' basic needs).

#### 3. Repeat this cycle

  * *Until* you've deployed all the features you planned for the MVP service

  * *Or, until* the MVP provides value by meeting basic user needs

<hr>

### Preparing to launch the MVP

**Note**: Some of these tasks impact one another. For example, if you change the information architecture, you'll need to test and QA again, and you may need to update the metrics you've set up in Google Analytics.

1. Finalize the [information architecture]({{site.baseurl}}/resources/more/info-architecture) for your service.

2. Finalize [ATO]({{site.baseurl}}/resources/more/ato) details.

3. Finalize [marketing and communications materials]({{site.baseurl}}/resources/more/marcom)

4. Conduct <a title="Go to qa testing" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/building-and-testing/qa" target="_blank">end-to-end QA testing</a>.

5. Set up and test <a title="Go to Google Analytics setup" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/google-analytics" target="_blank">Google Analytics</a>.

6. Load test your service.

7. Perform [user acceptance testing (UAT)]({{site.baseurl}}/resources/more/uat).

8. Set up [live service details]({{site.baseurl}}/resources/more/service-details).

9. Review your MVP with [VA's 508 office]({{site.baseurl}}/resources/more/va508).

10. Review your MVP with the [Call Center]({{site.baseurl}}/resources/more/call-center).
<br/>
