---
type: policy
code: XA
section: X
title: OVERVIEW
date-adoption: 
date-first-reading:
date-second-reading:
revision: 
review: 
previous-adoption-dates: 
comment: "Section X 'policies' are not actual policies, but instead extra guides and resources for maintaining this policy site."
comment-date: 2020-03-20
---

You are reading a post on a static web site intended to present a complete and up-to-date policy manual.

This site was generated by an open-source software package called GatsbyJS, using its 'gatsby-starter-blog' boilerplate, and subsequently revised by Jim Gammill for the purpose of hosting a school policy manual.

#### Use of Markdown Syntax

The site as built expects the policy documents to be in the form of a 'markdown' file.  Markdown is a simple, spare formating language.  A policy file written in markdown is a plain text file with a few formating commands that do not obscure the meaning of the policy.  

There are several benefits from writing policy files in the markdown syntax:

* markdown files are handled routinely by Gatsby and other web apps which convert them to html files available for posting on a static web site
* markdown files can be easily read and understood
* as a plain text file, markdown files can be stored in a repository system and readily 'differenced', so that the changes from one version to another are easy to see

(In contrast, a policy manual for which the source documents are Word documents does not have these advantages.  Word mixes substance with formating in a way that is hard to separate.) 

One resource on the markdown syntax is the [markdownguide.org](https://www.markdownguide.org/cheat-sheet).  This and similar resources provide information about the markdown syntax (and thus that topic is not covered here).

#### Maintaining a School Policy Site

There are two key roles for those that wish to maintain this site, or to use this site as a template for another school's policy manual:  

* Policy Editor
* Site Administrator

#### Role:  Policy Editor

The Policy Editor, who ideally should be designated by the school committee, is responsible for maintaining the policy and section markdown files.  

The minimum software app needed to maintain markdown files is a simple text editor, like Notebook (windows) or TextEdit (mac).  Of course, any text-editing software is appropriate, and the Policy Editor should feel free to use what they prefer.

My recommendation is that the Policy Editor also use a repository service, such as GitHub, to maintain the current and past versions of the policies and the section descriptions.  Many code editor programs can connect to a repository and show the differences between the current and previous versions of files.

The Policy Editor should also help set and maintain templates and formating guides for policies and sections. 

#### Role:  Site Administrator

The site administrator is the person that manages the deployment of the site, using some version of a Gatsby site.  This site is based on code available at Jim Gammill's GitHub account, [school-policy-site](https://github.com/JimGammill), and his version of the Minuteman School Policy [Manual](https://www.github.com/JimGammill/MMPolicy).

The Policy Administrator needs to have enough comfort with tweeking the Gatsby-based code, such as changing the gatsby-config.js file or the components and template files.  

In addition, the Policy Administrator needs to decide where to host the site, and whether to have an internal