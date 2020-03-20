---
type: policy
code: XE
section: X
title: SUGGESTED STYLE GUIDE
also-codes:
  - XE
cross-refs:
  - XEA
  - AA
legal-refs:
  - M.G.L. ch 74, sec 12C
  - MGL(74,12C)
  - "MGL 74:12C"
  - "603 CMR 6.04; 603 CMR 6.06"
date-adoption: 2020-03-04
date-first-reading: 2020-02-11
date-second-reading: 2020-03-04
revision: "This can be a quoted string."
review: "This can be a quoted string too."
previous-adoption-dates: "The previous dates are in a quoted string."
comment: "The comment tag in the frontmatter is a place to put comments that are not a formal part of the policy, like this."
comment-date: 2020-03-20
---

This page suggests a guide for using markdown to write a policy file.  Keep in mind that the markdown syntax is used to create html pages, and then the presentation of the html is controlled by settings within the Gatsby app, in particular the choice of a "typography" plug-in.

That is, if you don't like the way the web page works, you don't necessarily need to change the markdown style guide -- perhaps a custom typography plug-in that controls the css styles in a different way will satisfy you.

*Me, I am pretty easy to satisfy with the available typography plug-ins.  Maybe I would like to see some more control over indentations, but I am not going to sweat it at this point.*

#### Section Headers are h4

In this suggested style, sections are separated by h4 tags, which in markdown are created with "####":

    #### Section Headers are h4


#### Subject Titles in bold

Sometimes the policy writer doesn't want an h4 section header, but just a bold subject title:

**Subject Title**

A blank line starts a new paragraph 
with a line space.

**Subject Title with extra spaces on this line**      
In this case there are at least three spaces after the 
double-asterisks, which has the paragraph text 
follow on the next line.  This makes sure that the
paragraph starts just below the subject title.

**Subject Title with NO extra spaces on this line**
In this case there are NO extra spaces after the 
double-asterisks, which means this text appears
starting on the same line as the subject title, 
probably not what you wanted.

Here is how the code looks for these two examples:

    **Subject Title**
    
    A blank line starts a new paragraph 
    with a line space.

    **Subject Title with extra spaces on this line**      
    In this case there are at least three spaces after the 
    double-asterisks, which has the paragraph text 
    follow on the next line.  This makes sure that the
    paragraph starts just below the subject title.

    **Subject Title with NO extra spaces on this line**      
    In this case there are NO extra spaces after the 
    double-asterisks, which means this text appears
    starting on the same line as the subject title, 
    probably not what you wanted.

#### Common markdown styles:  bold and italic

Any string of text can appear 
**in bold, if it is surrounded by two asterisks**.

Similarly, any string of text can appear 
*in italics, it is surrounded by single asterisks*.

Here is how it looks in markdown:

    Any string of text can appear **in bold, 
    if it is surrounded by two asterisks**.
    
    Similarly, any string of text can appear *in italics, 
    it is surrounded by single asterisks*.

#### Use of Code Blocks

The above examples show how markdown can format text as code -- using a fixed font and indented.  To do this in markdown, one just inputs the line by (at least) 4 spaces.

In terms of writing policies, the suggested guide here is that the code block markdown be used for contact information with mailing addresses, such as:

	Civil Rights/Title IX Coordinator 
	758 Marrett Road
	Lexington, MA 02421 
	781-861-6500 ext 7301

#### List styles -- bullets and numbers and alpha

A perusal of existing policies show a divergence of style for creating lists.

Sometimes the lists are bullet items:

* item one
* item two
* item three

Sometimes the lists are numbered:

1. item 1
2. item 2
3. item 3

And sometimes the lists are marked by letters:

a) item a

b) item b

(c) item c, with matching parentheses

Markdown accomodates bullet lists and numbered lists, but not alpha-lists.  The example above of the alpha list just treats each item like a new paragraph.

Here is the markdown code for the three lists above:

    * item one
    * item two
    * item three

    1. item 1
    2. item 2
    3. item 3

    a) item a
    
    b) item b
    
    (c) item c, with matching parentheses

The suggestion is to come up with a style guideline that ranks these three styles in preference; for instance, prefer bullet lists unless some reference to a list item is needed in the policy text, in which case use a numbered list.  Alpha lists, since they are not supported in the basic markdown syntax are not encouraged if a bullet or numbered list is appropriate.  Alpha lists can be used, in the separate paragraph style, if clearly needed.

#### Markdown for Tables

Fortunately, markdown can be used to format tables.  A basic table has three pieces:

1. the first row, which is the header row
2. the second row, which has column headers as lines
3. the third and following rows, which are the rows of the table

Markdown uses "Pipes", shown on the keyboard as "|", to separate text into columns.

Here is a simple table example, and below the code that generates the table:

|Head 1   |   Head 2|  Head 3|
|---------|---------|--------|
|first    | second  | third  |
|columns don't have to line up; this wrapping is automatic  | but lining them up in markdown|  makes it easier to read|
| nice    |  and    |   neat |

    |Head 1   |   Head 2|  Head 3|
    |---------|---------|--------|
    |first    | second  | third  |
    |columns don't have to line up; this wrapping is automatic | but lining them up in markdown|  makes it easier to read|
    | nice    |  and    |   neat |

Some markdown guides say you can control whether columns are left-justified, right-justified, or center-justified.  I have not found that it works here.  Let me know if you can make that feature work.

#### End of Policy Items

At the end of policy are the legal references, the cross references, and the "also included as" codes.