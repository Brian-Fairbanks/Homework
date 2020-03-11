# HTML Code Refactor

This project demonstrates the ability to take an existing webpage more SEO friendly.


This was a homework assignment to Ensure that all links are functioning correctly, clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

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

## Completed

* Much of the CSS merged when elements had the same formatting
* Reordered CSS, including all header fields nearby near the top of the page
* Added id of the same name to class="search-engine-optimization" so that the anchor actually works
* Enclosed anchors at the top of the page in a new Id "anchors", and set it to float at 45% to the right, so it will not push underneath the header on smaller windows
* Added alt text to each image (note, this is alt text, not title text, so it will not popup in ballon text when hovering over.)
* Added a more descriptive title text to in the header.
* Changed the footer h2 to an h4 to follow sequential order.  adjusted this in CSS to refelct changes.
* Changed Div to more reasonable Semantics in accordance to - http://html5doctor.com/downloads/h5d-sectioning-flowchart.pdf

## Screenshot of File
![screenshot of website](https://raw.githubusercontent.com/Brian-Fairbanks/Homework/master/screenshot.PNG)
