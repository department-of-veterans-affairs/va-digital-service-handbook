---
#
modified-date: September 4, 2018
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
# Title and Description display on the page and in HTML meta tags
#
title: User Research guide
description: User research isn't just something you do during the discovery phase. You'll do it throughout the <i>Digital Delivery</i> lifecycle, checking in with your users to answer questions you have about how to improve your service.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - Expectations
  - The Paperwork Reduction Act
  - Participant privacy
  - Participant recruiting
  - Participant consent
  - Participant thank-yous
  - User research activities
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
permalink: /resources/user-research
#
---

### Using the User Research guide

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: " ", "-" | replace: "'", "" }})
{% endfor %}

<hr>


### Expectations

Teams working on the Veteran Tools Platform are required to have "User Research" as a skillset (see [Team Structure]({{site.baseurl}}/resources/more/team-structure#team-roles)).

Teams working on the Veteran Tools Platform are responsible for conducting their own user research studies, including recruiting. User research/testing studies must adhere to the guidelines laid out in this User Research guide.

If you have any questions, ask your DSVA contact.

<a href="#">Return to top</a>

<hr>


### The Paperwork Reduction Act

The <a href="https://www.opm.gov/about-us/open-government/digital-government-strategy/fitara/paperwork-reduction-act-guide.pdf" target="_blank">Paperwork Reduction Act (PRA)</a> limits the burden placed on people when interacting with the federal government. To avoid violating the PRA, follow the guidelines below.

#### User research

1. Research activities involving "direct observation" are **exempt from PRA**.

    * Whether remote or in-person, if you are looking at users (or their actions), the activity is exempt from PRA. This includes remotely observing a user interacting with a website or an application.

1. Research activities that ask people questions outside of the observed experience are **subject to PRA**.

    * This includes recruiting screeners, surveys (pre- or post-activity), and questions at the beginning or the end of an automated activity like card-sorting.

3. *If you aren't sure if a research activity is subject to PRA, ask your DSVA contact.*


#### Form design

If your team is working on an existing VA form, your researchers and designers will probably have some ideas about how to improve it. Great! But be sure your team understands the limitations of modifying existing VA forms.

1. If you plan to make look, feel, or language changes to a form, those are considered "de minimis," so you **don't need PRA approval to make the changes**.

1. If you're adding fields to an existing form (or creating a new form), you **do need PRA approval** and will need to go through the (often lengthy) approval process.

1. *If you aren't sure if your design changes qualify as "de minimis," ask your DSVA contact.*

#### PRA references

* <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/inforeg/memos/2014/appendix-data-search-tools-calculators.pdf" target="_blank">Types of data collection exempt from PRA</a>
* <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/inforeg/memos/2015/behavioral-science-insights-and-federal-forms.pdf" target="_blank">Explanation of "de minimis" changes</a>
* <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/assets/inforeg/PRAPrimer_04072010.pdf" target="_blank">General PRA primer</a>

<a href="#">Return to top</a>

<hr>


### Participant privacy

All information about research participants, including what they say and do during a research session, is *private information that your team must protect.*

* Do not share information about research participants with anyone outside of your team.

* Protect all PII &#8212; names, email addresses, addresses, phone numbers, and any other identifying information.

* Do not post files containing PII on Github. Keep these locally on your computer.

* Use encrypted email if you must send files containing PII to someone on your team.

* Anonymize all participants in session notes and research readouts. E.g., "Participant 1", "Participant 2", and so on.

* Anonymize all PII in session notes. E.g., replace "123 Main Street" with "Home address" or "Lynn, my sister" with "Sister."

* After a session is over, delete all PII from all video or audio files.

<a href="#">Return to top</a>

<hr>


### Participant recruiting

**All teams are required to follow <a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/User-Research/recruiting.md#screening-participants-for-external-contractors" target="_blank">the DSVA screening process</a> for any research study related to the Veteran Tools Platform.** 

After you've screened participants, follow your normal recruiting process.

If your team doesn't have an existing recruiting process, see <a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/User-Research/recruiting.md#tips" target="_blank">tips for recruiting</a>.


<a href="#">Return to top</a>

<hr>


### Participant consent

All research participants must sign a <a href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Templates/va-consent-form-generic.docx" target="_blank">consent form</a> *before taking part* in any research sessions.

* Be sure to update the generic email address with your own!

<a href="#">Return to top</a>

<hr>


### Participant thank-yous

The DSVA team thanks research participants for their time with $25 Amazon digital giftcards (or direct payment through PayPal). We encourage your team to do the same.

* **Note**: don't refer to participant thank-yous as "payments" or as "paying participants."

* Contact your COR to get approval for participant thank-yous.
  * The cost can be billed to your contract.
  * Other teams have successfully worked with their CORs by requesting a "not to exceed" amount for all participant thank-yous during their project.
  * The DSVA team has approval from the VA legal team to provide participant thank-yous. If your COR would like to see that approval, ask your DSVA contact.

<a href="#">Return to top</a>

<hr>


### User research activities

* [Create a research plan]({{site.baseurl}}/resources/more/research-activities#create-a-research-plan)
* [Plan a research sprint]({{site.baseurl}}/resources/more/research-activities#plan-a-research-sprint)
* [Conduct a research session]({{site.baseurl}}/resources/more/research-activities#conduct-a-research-session)
* [Document your findings]({{site.baseurl}}/resources/more/research-activities#document-your-findings)
* [Decide your next steps]({{site.baseurl}}/resources/more/research-activities#decide-your-next-steps)


<a href="#">Return to top</a>

<hr>


### Getting help

DSVA research resources are available to provide guidance and support throughout development and deployment.

* For process-related questions, ask in the *#{{site.slack.support}}* Slack channel.
* For research-related questions, ask in your team's "Product" Slack channel.

<br/>
<hr>
