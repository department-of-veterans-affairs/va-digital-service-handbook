---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Design guide
description: Learn about the Veteran Tools Platform design strategy. Find design resources, tools, and examples you can use throughout the service lifecycle.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - General design guidance
  - Design philosophy
  - Document every interaction
  - Design for accessibility
  - Content guidelines
  - Design tools
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-type: /service-design
permalink: /service-design/related/design
#
---

### Using the design guide

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### General design guidance

**Mobile-first design**

All services on the Veteran Tools Platform must work well in desktop, tablet, and mobile. We typically design flows and screens as a mobile experience, so we determine if they work well at the smallest screen size. The design files are set up so you can design a mobile-first experience, and the design patterns are responsive.

**New design patterns**

As we've built out the Veteran Tools Platform, we've focused the <a title="Go to design patterns" href="https://department-of-veterans-affairs.github.io/design-system/" target="_blank">design patterns</a> on the immediate design tasks. This means we have not designed for every possible VA scenario.

In your work, you may find a need for a new design pattern. If that happens, [contact the DSVA team](../../contact), and we'll work together to solve it.

**Using the patterns as designed**

The design patterns are meant to be used as solutions to specific design patterns. For instance, the "what does this mean?" pattern is meant to be used in that context only. We don't want it to be used in a "get more information" context.

If you have any questions about how or when to use specific design patterns, [contact the DSVA team](../../contact).

<a href="#">Return to top</a>

<hr>

### Design philosophy

#### Keep it simple

We try not to add complexity to existing VA policies and procedures.
* Limit the number of decisions a Veteran needs to make in one screen. We usually try to keep the number of questions under five. Two or three is even better.
* Find out what questions we need to ask. Sometimes we will add a question to simplify things. For example, a paper form might have a multicolumn table to ask questions about dependents. Instead we will ask if they have any dependents. If the answer is no, we skip the table entirely. We apply the same approach for any fields that match an "if yes, please explain" pattern.
* Prefer simplicity over flexibility. It can feel helpful to give Veterans multiple ways or places to enter data. But this increases complexity and makes the design more brittle. It can also confuse (rather than reassure) Veterans.
* Minimize the number of fields. Social Security numbers and phone numbers are one field (not three). And we deal with dashes and other formatting on the back end.
- Minimize masking. For example, we don't do the •••••••••• thing with social security numbers because we want people to see the data they're entered and correct it *before submission.*

#### Reduce data entry

People get frustrated entering data repeatedly, especially if it is stuff they think the VA should already know. Once someone is signed in, we do everything we can to reduce this.

* Prefill data. We get as much data from VA systems as we can. If VA already knows it, we present it for review and help Veterans update it if needed.
* Embed small forms. If there is a small second form involved, we add the unique questions conditionally. We fill the common stuff (name, date of birth, etc.) in from the data we've already collected and submit both forms if necessary.
* Save in-progress work. Any Vets.gov form can save progress so that a Veteran who is interrupted can pick it up again later.

#### Limit required fields

* We work with stakeholders to make sure we only collect data that we *need* in order to deliver a benefit.

#### Be specific

* We try not to assume too much context. Most people are not expert in VA benefits. So we try to provide context for form sections and labels. Review some of the current Veteran Tools Platform forms to get a feel for where and how we do this.
* Some forms ask for the similar information about multiple parties, for example, contact information on multiple family members.
  * In these situations, we clearly label these at both the chunk and field level.
  * Depending on the form, another approach is to build a list of people first, and then loop through the questions for each.
  * These approaches are especially helpful to folks with memory issues, common in cases of Traumatic Brain Injury (TBI).

#### Simplify digital signatures

Every VA paper form has at least one signature line. Our approach is that when a user agrees to terms in a form and/or submits a form, those actions stand in for the person's literal signature.

We have not yet dealt with multi-party signatures. If you come need for a multi-party signature, [contact the DSVA team](../../contact)), and we'll figure it out together.

<a href="#">Return to top</a>

<hr>


### Design for accessibility

1. Start with well-structured content (and design to make this easy) that assistive devices can make sense of.

2. Well-structured, plain language is a great start. But users with different education levels may understand your content differently. And some of your users may have memory or cognitive challenges.
<br/>Help these users maintain context through design.

    * Use clear labeling. For example, clearly label different address fields for different people, so that your users aren't wondering "Whose address are you asking for here?"
    * Use contextual help. For example, provide context that helps your users answer questions like "Why would I choose this option over another?"

3. Create a clear hierarchy on each page/screen.

4. Don't hide critical information in images or complicated diagrams. <!--That stuff should support the written word.-->

5. Understand that many low-vision people don't use screen&nbsp;readers. So you should

    * Make type large enough
    * Consider how your design will adjust when the user zooms in
    * Keep critical elements in the center of the screen. For example, an edit link that is flush right may never be seen by low-vision visitors. <!--A "straw test is a helpful check"-->

6. Don't rely on color alone, or sound alone, to communicate critical information or cues.

    * Color blindness tools like "Sim Daltonism" can help you avoid color contrast problems.

    * Combine color or sound with additional cues like font weight (e.g., bold) or text transformations (e.g., uppercase) to make sure people with low-vision or low-hearing can understand the point your interface is trying to make.
  <!--* Don't rely on sound for UI cues-->

7. Animation can be a helpful cue to reenforce the impact of choices.

    * But &mdash; be careful about motion effects that can trigger vertigo or other motion sensitivities.

8. Design with low motor skills in mind.

    * Use large targets for interactions.
    * Don't necessarily move the UI (no dancing monkeys ;)

**References**:
* <a title="Go to Section 508 office" href="https://www.section508.va.gov/" target="_blank">VA Section 508 office</a>
* <a title="Go to Section 508 law" href="https://www.section508.gov/manage/laws-and-policies" target="_blank">Section 508 law</a>

<a href="#">Return to top</a>

<hr>


### Document every interaction

#### Why design documentation?

Clear design documentation communicates how a thing works, and looks, to developers who will build the service and make it real.

Clear design documentation also

* Creates a record of decisions the team made for easier recall when having sign-off discussions later

* Creates an easy-to-follow "history" for new team members or stakeholders who may not know the full project history

* Creates a valuable source of information for teams who are working on similar or related projects on the Veteran Tools Platform

* Communicates new services (or features) to the Call Center, who support users of the Veteran Tools Platform
  * **Tip**: a video walkthrough is a great way to help Call Center staff understand your service (or feature). Videos are especially helpful if your service (or feature) includes a change to an existing VA process.

#### Communicating with developers

It's important to "design" all the interactions for each screen in your service. These include

* Different states of UI widgets
* Different conditions, e.g., when X happens, do Y
* All contextual help interactions, including the content in each contextual help area
* All errors
* All notifications

Designers should document these in the lowest-possible fidelity in a format that makes it easy to communicate to developers. For example, because error states and notifications have standard visual design, you just need to communicate the content to developers; the easiest way to do this is in a spreadsheet or other flat file (vs. creating a mockup for each error).







<a href="#">Return to top</a>

<hr>


### Content guidelines

**Plain-language content is a cornerstone of the Veteran Tools Platform design philosophy.**

When you're designing mockups or prototypes, be sure they include well-written content that follow the <a title="Go to content guide" href="https://github.com/department-of-veterans-affairs/vets.gov-content-style-guide" target="_blank">content guidelines</a>.

<a href="#">Return to top</a>

<hr>


### Design tools

**Review the <a title="Go to design patterns" href="https://department-of-veterans-affairs.github.io/design-system/" target="_blank">design patterns</a>**

The Veteran Tools Platform design patterns make it much easier for developers to quickly prototype new pages and forms. The design patterns are the source of truth for the latest templates, interaction design patterns, and visual design.

**Download design files**

* *The design files are created in <a title="Go to Sketch" href="https://www.sketchapp.com/" target="_blank">Sketch App</a>, which is a Mac application.* Although you can use other platforms/tools, we strongly recommend using Sketch to ensure your designers are working with our latest templates.
  * <a title="Go to instructions" href="https://github.com/department-of-veterans-affairs/vets.gov-team/tree/master/Work%20Practices/Design/Design%20Resources/Pattern%20Library" target="_blank">Instructions for downloading and using the Sketch files</a>
  *Once a designer been added to the VA Github organization, they'll be able to download the Sketch files.*
  * <a title="Go to fonts" href="https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Work%20Practices/Design/Design%20Resources/Pattern%20Library/vets-fonts.md" target="_blank">Instructions for fonts and icons</a>

<hr>
