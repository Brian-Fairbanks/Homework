# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.


## Completed

Much of the css merged when elements had the same formatting
reordered CSS, including all header fields nearby near the top of the page
Added id of the same name to class="search-engine-optimization" so that the anchor actually works
enclosed anchors at the top of the page in a new Id "anchors", and set it to float at 45% to the right, so it will not push underneath the header on smaller windows
added alt text to each image (note, this is alt text, not title text, so it will not popup in ballon text when hovering over.)
added a more descriptive title text to in the header.
changed the footer h2 to an h4 to follow sequential order.  adjusted this in CSS to refelct changes.


- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
