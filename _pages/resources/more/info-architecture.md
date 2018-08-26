---
#
# See the Github wiki for how to edit content on this page and markdown styles you can use:
# link here
#
# Title and Description display on page and in meta
title: Defining information architecture
description: Learn how to integrate your service into the Veteran Tools Platform so your users can easily find (and search for) your service.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - Define the service name
  - Define the information architecture (IA)
  - Define the URLs
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-page-type: /service-design
permalink: /resources/more/info-architecture
#
---

### Coordinating with the DSVA team

You'll need to coordinate these tasks with the DSVA team.

The DSVA team will make sure your service doesn't collide with other services and provide suggestions based on Veteran experiences with other services.

> [Contact the DSVA team](../../../contact) to review the items in each task below.

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-' | replace: '(', '' | replace: ')', '' }})
{% endfor %}

<hr>


### Define the service name

*If you're building on to an existing service, you can skip this section.*

If you're building a new service, you'll need to create a name for it.

* Be sure to test the service name with your users.
<!--* <span class="todo">TODO - provide an example</span>-->

<a href="#">Return to top</a>

<hr>


### Define the information architecture (IA)

The IA determines where in the Veteran Tools Platform your service will live, and it defines the URL of your service.

#### Think about how your service will integrate into the existing Veteran Tools Platform

* How will your users find and get to your service?

* Where does your service live within the existing content hubs?

* Will the service live in the primary navigation of the site? If so, where?

* What are the primary entry points to the service?

* Would cross-linking from other tools on the Veteran Tools Platform help Veterans find and use your service? If so, what are those secondary entry points?


#### Test the proposed IA with Veterans

* Your service's IA should map to Veteran mental models &mdash; even (and especially) if this differs from how VA thinks about your service.

* Use card sorting, tree testing, or user interviews to test the IA.

<a href="#">Return to top</a>

<hr>


### Define the URLS

In [creating the IA for your service](#define-the-information-architecture-ia), you identified the main part of your service's URL &mdash; the directory (or sub-directory) in which the service lives.

Now you need to create URLs that include the end of the URL path &mdash; the last directory or page name.

#### Guidelines for creating URLs

* Keep directory and page URLs as short as possible, without losing their meaning.

* URLs should be all lowercase.

* Use hyphens, not underscores. Underscoring can change two words into one word, for example, "health care" becomes "healthcare."

* Use the HTML page title as your guide, but you do not need to match it exactly.

* Use the most descriptive of all the keywords used on the page. Include only keywords that help the reader understand the point of the page.

* Do not load or repeat keywords in the URL &mdash; search engines will pick up other keywords from other elements on the page.

* Don't include words that don't add meaning, such as "the" or "a."

* Avoid repetition of words. In some cases it may naturally happen, but avoid it when possible.

* For form URLs, use both the form number, as well as keywords, to create the URL:

  * **structure**
    <code>/form-1234-keywords-from-form-name</code>

  * **example** *(page is not live)*
    <code>https://www.vets.gov/pension/application/form-527EZ-veteran-pension</code>

<hr>
