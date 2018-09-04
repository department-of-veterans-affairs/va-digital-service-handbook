---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Prototype activities
description: Plan, prepare, and conduct prototyping activities.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Identify your goals
  - Plan your design sprints
  - Conduct a design sprint
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-page-type: /resources
permalink: /resources/more/prototype-activities
#
---

### What are prototyping activities?

Prototyping activities are designed to quickly test different hypotheses about potential design and technical solutions. Whether you're trying to define your MVP or define a release in the *Learn and Improve* phase, your objective is to identify potential issues &mdash; and learn from them &mdash; while you still have time to make corrections.

There's not a one-size-fits-all set of hypotheses to test during specific *Digital Delivery* phases. But successful teams tend to use *design sprints to prototype and test their hypotheses.*

A design sprint takes 1-2 weeks and is designed to solve important design or business challenges. Each design sprint starts with brainstorming activities that lead to a prototype that is tested with real users &mdash; all within the span of 1-2 weeks.

* Learn more about design sprints at <a title="Go to google ventures" href="http://www.gv.com/sprint/" target="_blank">Google Ventures</a>, as well as <a title="Go to design sprint kit" href="https://designsprintkit.withgoogle.com" target="_blank">Google's Design Sprint Kit</a> (a slight variation on the first link).

<hr>

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>


### Identify your goals

Begin by identifying your team's goals. Consider these questions:

* Based on your research findings, what **kinds of solutions** make the most sense in terms of meeting your users' needs?

* Which of those would you like to move forward with and test?

* What are the biggest **design risks** in those solutions?

* What are the biggest **technical risks** in those solutions?

* What are the biggest **business or policy risks** in those solutions?

* What are your hypotheses about those risks and solutions?

<hr>

### Plan your design sprints

Based on the goals and hypotheses you've identified, map out your design sprints during this phase.

* Each design sprint takes 1-2 weeks. Because each design sprint involves talking with your users, plan some extra time for recruiting and screening activities, as well as analysis and synthesis activities. For example, in an 8-week period, you might (realistically) do 3-5 design sprints.

* Don't test all your hypotheses at once. Target each design sprint to specific hypotheses.

* Test the most risky hypotheses first &mdash; the ones that, if your hypothesis is proven wrong, will derail your solution concept.

* Test your design/user experience hypotheses &mdash; for example, a single-page vs multi-page user flow.

* Test your technical hypotheses &mdash; for example, whether a specific Vets-API provides data in the format you need.

<hr>

### Conduct a design sprint

1. **Review** &mdash; review current goals, hypotheses, and solution concepts with your team.

2. **Sketch** &mdash; use individual and group brainstorming activities to explore design solutions that will test your hypotheses.

3. **Decide** &mdash; select a single option to prototype.

4. **Prototype** &mdash; create a a simple prototype to test the solution (see [Prototyping Tips]({{site.baseurl}}/resources/more/prototyping-tips)).

5. **Test** &mdash; test the prototype with real users and collect their feedback.
    * Your goal is to iterate quickly. So make sure you plan far enough in advance to recruit participants for each design sprint.

6. **Analyze** &mdash; assess the user feedback and decide how it impacts your solution concept.

7. **Plan** &mdash; plan your next design sprint incorporating what you've just learned into the next prototype.
    * Involve all team members in prototyping. This leads to better design outcomes and helps the team create a common understanding of the service.


8. **Keep iterating** with your design sprints **until your prototypes meet the goals you've identified.**
    * For the *Build and Test* phase, this means meeting your users' basic needs for the MVP launch.
    * For later releases, this means meeting the User Stories you identified for the release.


<br/>
<hr>
