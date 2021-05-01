# Code Refactor Starter Code

## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria

GIVEN a webpage meets accessibility standards

- [x] WHEN I view the source code, THEN I find semantic HTML elements
- [x] WHEN I view the structure of the HTML elements, THEN I find that the elements follow a logical structure independent of styling and positioning
- [x] WHEN I view the image elements, THEN I find accessible alt attributes
- [x] WHEN I view the heading attributes, THEN they fall in sequential order
- [x] WHEN I view the title element, THEN I find a concise, descriptive title

Extra:

- [x] WHEN I tap on a nav link, THEN I see the corresponding section

## Semantic HTML Implementation

> WHEN I view the source code, THEN I find semantic HTML elements

Following the W3 standards, the html was updated to inmplement `header`, `nav`, `section`, `article` and `footer` . More details [here](https://www.w3schools.com/html/html5_semantic_elements.asp)

## HTML Structucture Implementation

> WHEN I view the structure of the HTML elements, THEN I find that the elements follow a logical structure independent of styling and positioning

As a best practice we installed the "prettier" formatter for VSCode as to ensure code follows convention standards. It was applied both to the HTML and CSS.

## Alt IMG Attributes

> WHEN I view the image elements, THEN I find accessible alt attributes

Added contextual `alt` attributes to all `img` elements

## Heading Hierarchy

> WHEN I view the heading attributes, THEN they fall in sequential order

The only missing item was an H4 element in the footer, other than that elements seems to follow a hierarchical structure as they were.

## Title

> WHEN I view the title element, THEN I find a concise, descriptive title

Title was update to reflect requirements.

## Links

> WHEN I tap on a nav link, THEN I see the corresponding section

Fixed a broken link from the nav menu
