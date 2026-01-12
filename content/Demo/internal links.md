---
title: Internal links
draft: false
tags:
  - feature
---
 
Internal links are ways to reference existing sites documentation, or create links to documents that have not been created yet.  This allows us to connect all of our related articles easily.  We can then also create links to documents, thoughts, and content that we haven't created yet.  Creating and referencing links is incredibly easy, only needed to use `[[Double Brackets]]` to generate the markdown syntax.

---
### How we plan on using internal links

There are several different ways we hope to utilize internal links.  Each of which we have made some written use cases below.

#### Connecting knowledge without bloat

One of the hardest parts about writing knowledge for the IOC is the balance of having enough information to understand how to complete a task, while not including so much information that the task becomes confusing or overwhelming.  

> [!example]-
> When creating creating an article for our spectrum alarm response, we can individually internal link to set of instructions.  To scale even further down, when we reference a term like [[spectrum]] or [[foreseer]] in our documentation, we can link to our #training docs for those tools.  This will keep the overall instructions clean, while still giving plenty of connection points to expand knowledge for new team members.

#### Creating institutional definitions

Another great feature of internal links is the ability to create a link to a specific `## Header` inside of a document.  Combining this with the ability to preview internal links when hovering your mouse over them, we can create definitions for both general and institutional nomenclature.  

> [!example]-
> Instead of seeing the entire page for the [[IOC]] team, we can link to the header of the article like so:  [IOC](IOC.md#IOC).  By doing this, it ensures that whenever we make changes to the definitions of IOC, it will be reflected in every article that references it.  If were to have an additional name change in the future, we could change the name of the original file to our new acronym, and all of our documentation would update instantly.


#### Visualizing connections

You may have noticed the interactive graph view on in the top right of the website.  This is a visual representative of all the documents that have an internal link for this web page, and any documents that share the same [[tags]].  