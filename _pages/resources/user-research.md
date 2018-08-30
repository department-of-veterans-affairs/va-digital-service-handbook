---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
# Title and Description display on the page and in HTML meta tags
#
title: User Research guide
description: User research isn't just something you do during the discovery phase. You'll do it throughout the Digital Delivery lifecycle, checking in with your users to answer questions you have about how to improve your service.
#
# Editable - Internal page menu
# Match titles here with H3s (###) below
#
sections:
  - Expectations
  - Research guidelines
  - Create a research plan
  - Plan a research sprint
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
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>


### Expectations

Teams working on the Veteran Tools Platform are required to have "User Research" as a skillset (see [Team Structure]({{site.baseurl}}/resources/more/team-structure#team-roles)).

Teams working on the Veteran Tools Platform are responsible for conducting their own user research studies, including recruiting. User research/testing studies must adhere to the guidelines laid out in this User Research guide.

If you have any questions, ask your DSVA contact.

<a href="#">Return to top</a>

<hr>

### Research guidelines

<!--

#### User research and the Paperwork Reduction Act

The Paperwork Reduction Act (PRA) limits the burden placed on people when interacting with the federal government. *To avoid going through the (often lengthy) PRA approval process, stay within PRA limits.*

PRA does allow you to observe people and ask them questions about the experience you are observing. However, some pre- and post-research activities must follow PRA guidelines.

<Follow the PRA guidance we've included in the sections below. If you're not certain if an activity is subject to PRA, [contact the DSVA team](../../contact).

<a href="#">Return to top</a>

<hr-->

#### User privacy

Whatever people say or do during user research sessions is considered private information that your team must protect.

* **Tips**:
  * Don't post recruiting files with names, emails, or phone numbers. Keep these locally on your computer.
  * All session notes should to refer to research participants as "Participant 1", "Participant 2", and so on. Any PII in the session notes must be deleted before posting or sharing with your team.
  * If audio or video recordings contain PII, you must delete that information before posting or sharing the files with your team.

<a href="#">Return to top</a>

<hr>


### Create a research plan

Create a research plan at the start of each development phase, especially discovery, alpha, and beta. Then regularly update your research plan as you learn more about your users.

#### 1. Agree on your research questions

* No matter what research method you choose or what phase you're in, your first step is to clearly define what you want to get out of the research. This helps your team build a service that meets the needs of your users.

* In *Research and Discovery*, your research questions are likely to be broad and evolve quickly as you learn. They should become more specific in later development phases, as you focus on particular user groups and parts of your service.

* **Activity:** Run a team workshop at the beginning of each development phase [to prioritize your team's questions and the assumptions you want to test]({{site.baseurl}}/resources/more/research-questions).


#### 2. Identify user groups

* Decide who you need to research with. Depending on what you need to learn, this might include all the different users of your service or just specific groups.

* In the *Research and Discovery* phase for a new service, you may not have a clear idea of who your potential users will be. Research this as a priority.

* **Tips**:
  * Consider creating <a title="Go to 18f personas" href="https://methods.18f.gov/decide/personas/" target="_blank">personas</a> to help you identity your user groups. See <a title="Go to example personas" href="https://github.com/18F/federalist-design/wiki/Personas" target="_blank">some examples</a>.
  * VA employees who interact with the potential users of your service can provide early insight into the challenges your users might face. So you may also find it useful to talk to them informally. Questions you might ask:
    * What do you need from Veterans in order to help them?
    * What are common errors you see people making that slow or derail the process?
    * What's working well?
    * What technical or policy issues are a challenge?


#### 3. Choose research methods and activities

* Decide which <a title="Go to 18f research methods" href="https://methods.18f.gov/discover/" target="_blank">research methods</a> to use. Your choices will depend on what you want to learn and the development phase you’re in.

* **Tips**:

  * Choose research activities that will provide strong evidence and reliable answers to your questions, for the least time, effort, and cost.
  * If the team doesn’t have much experience with user research, choose simple methods like interviews and usability testing that your team can easily understand and join in with.


#### 4. Map out your research sprints

* Once you’ve decided on your research questions, user groups and research methods, start planning your [research sprints](#plan-a-research-sprint).

* For each development phase, map out just the research sprints you need to answer your highest priority questions. You can arrange more research sprints as you learn more about your users and your service.

* Each research sprint should answer specific research questions with specific user groups. A sprint usually lasts about two weeks, beginning from when you recruit users to when you complete your research findings.

* **Tips**:
  * Focus your research sprints on the most immediate questions to be answered. Don’t do lots of research that the team can't respond to right away.
  * Be flexible. As you learn more from each research sprint, revise your research plan accordingly. For example, a question answered in Research Sprint #1 may mean that Research Sprint #2 should answer different questions than you originally planned.
  * Aim to do one round of research every 2-3 weeks.


<a href="#">Return to top</a>

<hr>


### Plan a research sprint


#### 1. Document the questions you want to answer during this research sprint

* Create clear objectives for each research sprint (try [using this template]({{site.baseurl}}/resources/more/research-sprints)).

* Before starting a research sprint, be sure you know

  * What you’re trying to achieve (do you want to understand your users’ behavior, try out new features, or both?)
  * Which problems you’re trying to solve
  * Which assumptions about your users or your service you want to test
  * What you need to know now to be able to make an informed decision about what to do next

* Once you’ve agreed on your objectives, agree on the research methods you’ll use to meet those.

#### 2. Identify and recruit participants

* **Participant numbers**
  * 4-8 participants for qualitative research (user interviews, usability testing, etc.)
  * Hundreds for quantitative research (A/B testing, card sorting, etc.)

* **Identify participant types**

  * Identify the kinds of people you want to research. Depending on the questions you want to answer, these may be all users of your service or a subset of them (for example, Veterans who have applied for disability benefits).
  * **Be inclusive**: Recruit a representative sample of your potential users. Aim to talk to people across the full range of age, ethnicity, gender, geography, service branches, service eras, and digital experience that you'd expect to find in people using your service.

* **How to recruit**

  * **Timeframe**: Start recruiting at least 2 weeks before you plan to run the research sessions.

  * **Where**: You can recruit Veteran participants in person at Veteran-focused events, through VSO relationships, and through your personal networks and social media.
    * <a title="Go to examples" href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Work%20Practices/Research/Request%20or%20Do%20Research/PRA%20and%20Recruiting/Outreachrecruiting-language-proposed.md" target="_blank">Examples of recruiting emails at different points in the recruiting process</a>. *Once you've completed the onboarding steps, you'll be able to see this content.*

* **Screen participants**

  * Once you've identified participant types and established a pool of potential participants, create a screener &mdash; a list of the criteria people must meet in order to match the participant types you identified above.
  * Then get in touch with potential participants to make sure they meet your screener criteria.

<!--* **Tip**: The screener is subject to the Paperwork Reduction Act (PRA). To stay within PRA guidelines, limit your questions to 9 questions.-->

* **Consent forms**

  * Participants must sign a [consent form](https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Templates/va-consent-form-generic.docx) prior to taking part in any research sessions. Be sure to update the generic email address with your own!

#### 3. Plan the research sessions

* If you're doing user interviews or usability testing, prepare a conversation guide. Plan sessions to last from 30-60 minutes.
* If you're doing other types of research, set up the equipment (or software or other artifacts) well in advance of your research sessions.
* Whatever method you use, do a practice run with your team so you can make any modifications before running the sessions with real participants.
  * <a title="Go to example" href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Products/MHV%20Account%20Creation/MHV%20Upgrade/Research/conversation-guide.md" target="_blank">Example conversation guide</a>. *Once you've completed the onboarding steps, you'll be able to see this content.*
  * [Conversation guide template]({{site.baseurl}}/resources/more/conversation-guide)

  <!--
  > **Post-session surveys and questions**
  If your survey or followup questions occur after the research session ends, for example, after a user has completed a card sorting activity, it is subject to PRA. You can only ask up to 9 questions.
  -->

#### 4. Prepare for the research sessions

* **Research prototype**
  * If you're prototyping your service (or showing other artifacts), make sure it works properly and is accessible from inside the testing venue (or recording software).

* **Recording sessions**
  * We record research sessions so the project team can review them later and so other Veteran Tools Platform teams can learn from them.
  * We use <a title="Go to GoToMeeting" href="https://www.gotomeeting.com/" target="_blank">GoToMeeting</a> to record remote user interviews and usability testing, but you can use other recording software if you like.

* **Prepare participant thank-yous**
  * We thank participants for their time with $25-$50 Amazon giftcards (or direct payment through PayPal). *Don't refer to the "thank you" as "paying" the participant or as a "payment."*

* **Team roles**
  * Involve the whole team in user research, and make sure they understand their roles during each research session.
    * Moderator conducts the research session
    * Notetaker tries to record the session as close to verbatim as possible
    * Observers listen silently and make their own notes

#### 5. Run the research sessions

* **Best practices**

  * Observers should mute their audio and disable their video camera. If the remote recording software asks Observers to input a name, have them use a generic name like "Observer 1."
  * Plan sessions so there's at least a 30 minute break between each session.
  * For user interviews and usability sessions, don't plan more than 4 per day.
  * Aim to have team members write up their observations immediately after a session. The longer people take to do this, the fewer specific details they're able to remember about the session.
  * Ask the participant if they would like to participate in a future research study. Also ask them if they'd be willing to share that information with other Veterans in their community. This will help you expand your participant pool for future research studies.
  * The [conversation guide template]({{site.baseurl}}/resources/more/conversation-guide) has some additional tips for conducting your research session.

#### 6. Analyze and synthesize the research data

* You need to filter, organize, and interpret your research data (notes, photos, audio, video) so you can produce useful insights that will help you design and build your service.

* Do analysis with your whole team as soon as you can after each round of research, while it is still fresh in people’s minds.

* Involving lots of people helps your team make better decisions. It reduces the risk of researcher bias and limits the influence of individual team members or stakeholders. It also means you can decide as a group what the next most important thing to work on should be.

* <a title="Go to article" href="https://uxdesign.cc/synthesis-how-to-make-sense-of-your-design-research-d67ad79b684b" target="_blank">Example analysis/synthesis activity</a>.

#### 7. Document and share your findings

* **Prepare a research readout**
  * Summarize what you did and what you learned in a [research readout]({{site.baseurl}}/resources/more/research-readout).
  * Arrange a time with your team and your stakeholders to go over the findings in your research readout.

* **Document research**
  * Be sure to document the following in your team's Github "Product" folder

    * Research sprint plan
    * Recordings of research sessions &mdash; scrub any PII (names, addresses, emails, etc.) from these before putting them on Github
    * Session notes - any notes taken by the Notetaker and Observers (scrub any PII before posting)
    * Notes, photos, etc. from the team's synthesis activities
    * Your research readout

#### 8. Decide on your next steps

* Review the questions you wanted to answer in your research sprint plan. Use those to guide your team as you agree on what you'll work on next.

  * How do the answers you just learned impact what you were planning to do next?
  * Do you need to modify how you were thinking about designing or building some portion of the service?
  * Do you have new questions? How can you get answers to those questions in the team's next chunk of work?

* **Tips**:

  * Be agile. Adjust your team's plan for the next sprint (or phase) in response to the research findings.
  * Be user-centered. The purpose of talking with users is to ensure you design a service that meets their needs. Your research findings may show you need to re-think the next chunk of design or development work.


<a href="#">Return to top</a>

<hr>

### Getting help

DSVA research resources are available to provide guidance and support throughout development and deployment.

* For process-related questions, ask in the *#support-external* Slack channel.
* For research-related questions, ask in your team's "Product" Slack channel.

<br/>
<hr>
