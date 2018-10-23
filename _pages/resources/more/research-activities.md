---
#
modified-date: September 4, 2018
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: User research activities
description: Plan, prepare, and conduct user research activities.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Create a research plan
  - Plan a research sprint
  - Conduct a research session
  - Document your findings
  - Decide your next steps
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-page-type: /resources
permalink: /resources/more/research-activities
#
---

### Overview



<hr>

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>


### Create a research plan

Create a research plan at the start of each *Digital Delivery* phase. Then regularly update your research plan as you learn more about your users.

#### 1. Agree on your research questions

* No matter which research method you choose or what phase you're in, your first step is to clearly define what you want to get out of the research. This helps your team build a service that meets the needs of your users.

* In *Research and Discovery*, your research questions are likely to be broad and evolve quickly as you learn. They should become more specific in later *Digital Delivery* phases, as you focus on particular user groups and parts of your service.

* **Activity:** Run a team workshop at the beginning of each *Digital Delivery* phase [to prioritize your team's questions and the assumptions you want to test]({{site.baseurl}}/resources/more/research-questions).


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

* Decide which <a title="Go to 18f research methods" href="https://methods.18f.gov/discover/" target="_blank">research methods</a> to use. Your choices will depend on what you want to learn and the *Digital Delivery* phase you’re in.

* **Tips**:

  * Choose research activities that will provide strong evidence and reliable answers to your questions, for the least time, effort, and cost.
  * If the team doesn’t have much experience with user research, choose simple methods like interviews and usability testing that your team can easily understand and join in with.


#### 4. Map out your research sprints

* Once you’ve decided on your research questions, user groups and research methods, start planning your [research sprints](#plan-a-research-sprint).

* For each *Digital Delivery* phase, map out just the research sprints you need to answer your highest priority questions. You can arrange more research sprints as you learn more about your users and your service.

* Each research sprint should answer specific research questions with specific user groups. A sprint usually lasts about two weeks, beginning from when you recruit users to when you complete your research findings.

* **Tips**:
  * Focus your research sprints on the most immediate questions to be answered. Don’t do lots of research that the team can't respond to right away.
  * Be flexible. As you learn more about your users from each research sprint, revise your research plan accordingly.
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

#### 2. Identify participant types

* **Numbers**
  * 4-8 participants for qualitative research (user interviews, usability testing, etc.)
  * Hundreds for quantitative research (A/B testing, card sorting, etc.)

* **Types**

  * Identify the kinds of people you want to research. Depending on the questions you want to answer, these may be all users of your service or a subset of them (for example, Veterans who have applied for disability benefits).
  * **Be inclusive**: Recruit a representative sample of your potential users. Aim to talk to people across the full range of age, ethnicity, gender, geography, service branches, service eras, and digital experience that you'd expect to find in people using your service.

#### 3. Recruit, screen, and obtain consent  

* Create a list of the criteria people must meet in order to match the participant types you've identified.
* Use [the DSVA screening process](../user-research#participant-recruiting) to create a pool of potential participants.
* Phone potential participants to make sure they meet your screener criteria.
* Once you've identified the best participants, [get their consent to participate](../user-research#participant-consent) in the research study.

#### 3. Prepare for the research sessions

* Plan sessions to last from 30-60 minutes.

* Plan to record the research sessions (video preferred) so your team can review them later and so other Veteran Tools Platform teams can learn from them.
  * For reference, the DSVA team uses <a title="Go to GoToMeeting" href="https://www.gotomeeting.com/" target="_blank">GoToMeeting</a> for remote usability testing and interviews.

* If you're doing user interviews or usability testing, prepare a [conversation guide]({{site.baseurl}}/resources/more/conversation-guide).

* If the research session involves a prototype (or other digital artifact), make sure it works properly and is viewable from inside the recording software (or testing venue).

* [Prepare participant thank-yous](../user-research#participant-thank-yous)

* Involve the whole team in user research. Make sure they understand their roles during the session.
  * Moderator conducts the research session
  * Notetaker tries to record the session as close to verbatim as possible
  * Observers listen silently and make their own notes

* Do a practice research session (including recording) with your team so you can make any modifications before running the sessions with real participants.

<a href="#">Return to top</a>

<hr>


### Conduct a research session

Follow best practices.

* Observers should mute their audio and disable their video camera. If the remote recording software asks Observers to input a name, have them use a generic name like "Observer 1."
* Plan sessions so there's at least a 30 minute break between each session.
* For user interviews and usability sessions, don't plan more than 4 per day.
* Aim to have team members write up their observations immediately after a session. The longer people take to do this, the fewer specific details they're able to remember about the session.
* Ask the participant if they would like to participate in a future research study. Also ask them if they'd be willing to share that information with other Veterans in their community. This will help you expand your participant pool for future research studies.
* The [conversation guide template]({{site.baseurl}}/resources/more/conversation-guide) has some additional tips for conducting your research session.

<a href="#">Return to top</a>

<hr>


### Document your findings

#### 1. Analyze and synthesize the research data

* You need to filter, organize, and interpret your research data (notes, photos, audio, video) so you can produce useful insights that will help you design and build your service.

* Do analysis with your whole team as soon as you can after each round of research, while it is still fresh in people’s minds.

* Involving lots of people helps your team make better decisions. It reduces the risk of researcher bias and limits the influence of individual team members or stakeholders. It also means you can decide as a group what the next most important thing to work on should be.

* <a title="Go to article" href="https://uxdesign.cc/synthesis-how-to-make-sense-of-your-design-research-d67ad79b684b" target="_blank">Example analysis/synthesis activity</a>

#### 2. Prepare a research readout
* Summarize what you did and what you learned in a research readout.
  * See an <a title="" href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Products/MHV%20Account%20Creation/MHV%20Upgrade/Research/MHV-upgrade-research-readout_v1.1.pdf" target="_blank">example research readout</a> ({{ site.vets-team }}).
  * <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Templates/research-readout-generic.key" target="_blank">Research readout template - Keynote</a>
  * <a href="https://github.com/department-of-veterans-affairs/vets-external-teams/blob/master/Templates/research-readout-generic.pptx" target="_blank">Research readout template - Powerpoint</a>
* Arrange a time with your team and your stakeholders to go over the findings in your research readout.

#### 3. Document your research

* Document the following in your team's Github *Product/Research* folder:

  * Research sprint plan
  * Session notes - any notes taken by the Notetaker and Observers (scrub any PII before posting)
  * Notes, photos, etc. from the team's synthesis activities
  * Your research readout

* Document participant recordings

  * **Scrub all PII (names, addresses, emails, etc.) from participant video and audio recordings.**
    * Due to the nature of the research questions, some recordings contain a lot of PII. 
    * Use your best judgement here. If there's so much PII that the recording loses meaning without it, skip the rest of this process.
  * After scrubbing PII, do the following:
     1. Create a message in your team's Slack channel (e.g., *#claimsmodern*) and upload the file.
     1. Copy the link to the Slack message (click the "three dots" icon and choose "Copy link").
     1. Create a new Github page called "Participant Recordings" in your team's Github *Product/Research* folder. <a href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Products/Declare%20Dependent%20686/Design/Usability%20Research%20April%202018/686%20usability%20recordings.md" target="_blank">See an example</a> ({{site.vets-team}}).
       * List each participant on that page.
       * Link each participant to the link you copied for each file uploaded to Slack.
     1. Then create a new entry on the <a href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Work%20Practices/Research/Research%20History.md" target="_blank">Research History page</a> by following the instructions at the top of that page ({{site.vets-team}}).

<a href="#">Return to top</a>

<hr>


### Decide your next steps

* Review the questions you wanted to answer in your research sprint. Use those to guide your team as you agree on what you'll work on next.

  * How do the answers you just learned impact what you were planning to do next?
  * Do you need to modify how you were thinking about designing or building some portion of the service?
  * Do you have new questions? How can you get answers to those questions in the team's next chunk of work?

* Be agile. Adjust your team's plan for the next sprint (or phase) in response to the research findings.
* Be user-centered. The purpose of talking with users is to ensure you design a service that meets their needs. Your research findings may show you need to re-think the next chunk of design or development work.

<br/>
<hr>
