---
#
modified-date: September 4, 2018
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Authority to Operate (ATO)
description: Coordinate with the DSVA team to determine if the Veteran Tools Platform ATO needs to be updated for your service.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Request a preliminary ATO assessment
  - Request a security review
  - Request a final ATO review
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-page-type: /resources
permalink: /resources/more/ato
#
---

### What is an Authority to Operate (ATO)?

The purpose of an Authority To Operate (ATO) is to ensure the risks to VA (operations, assets, or individuals) are acceptable. If the risks are low, VA issues an ATO for the system involved.

The Veteran Tools Platform has **a platform-wide ATO from VA** (dated March 2, 2017). The DSVA team is responsible for maintaining that ATO. DSVA updates the ATO (and any related RiskVision items) when new applications are added to the platform (or when new features are added to existing applications).

<hr>

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>


### Request a preliminary ATO assessment

**Connect with the DSVA team as early as possible to start this process.**

1. Create an issue in the <a href="https://github.com/department-of-veterans-affairs/vets.gov-team" target="_blank">vets.gov-team</a> repository. *When you've completed the onboarding steps, you'll be able to view that repo.*

1. Assign the issue to Brian Gryth (**@briangryth**).

1. Label the issue with the **devops** label.

1. Title the issue **Request for preliminary ATO assessment**.

1. Provide the following information in the issue content.

    * What data are you collecting? For example, what data are you requesting from users?
    * What data are you using? For example, what data are you requesting from some VA service?
    * Where does that data come from? For example, what API endpoint are you getting the data from?

1. DSVA will examine the existing ATO documents and determine if they need to be updated based on the information you've provided.
    * Plan for some back and forth conversation in the Github issue to get all the information DSVA needs.

1. DSVA will provide a preliminary ATO assessment of whether or not the ATO needs to be updated.

<a href="#">Return to top</a>

<hr>

### Request a security review

You'll need a **security review** before you can launch your tool or service. Complete this step when you know that your tool/service **will not** change before launch.

#### in progress!

<a href="#">Return to top</a>

<hr>

### Request a final ATO review

You'll need a **final ATO review** before you can launch your tool or service. Complete this step **after the security review** when you know that your tool/service **will not** change before launch.

1. Create an issue in the <a href="https://github.com/department-of-veterans-affairs/vets.gov-team" target="_blank">vets.gov-team</a> repository. *When you've completed the onboarding steps, you'll be able to view that repo.*

1. Assign the issue to Brian Gryth (**@briangryth**).

1. Label the issue with the **devops** label.

1. Title the issue **Request for final ATO review**.

1. Provide the following information in the issue content.

    * What data are you collecting? For example, what data are you requesting from users?
    * What data are you using? For example, what data are you requesting from some VA service?
    * Where does that data come from? For example, what API endpoint are you getting the data from?

1. DSVA will examine the existing ATO documents and determine if they need to be updated based on the information you've provided.
    * Plan for some back and forth conversation in the Github issue to get all the information DSVA needs.

1. If the ATO needs to be updated:
    * DSVA will update the relevant ATO documents.
    * DSVA will make all necessary updates in RiskVision.
    * DSVA will let you know the ATO has been updated.

1. If the ATO does not need to be updated:
    * DSVA will let you know that the current ATO still applies.

<br/>
<hr>
