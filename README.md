# Horiseon Social Solutions - Site Refactor

## Project Goal
For this project the customer requested we review their site for the following accessibility standards:
1. Semantic HTML elements
2. HTML elements which follow a logical structure
3. Ensure all image tags include alt attributes
4. Review Heading attributes for organization
5. Update Title element to be more descriptive and concise

## Changes
### index.html
- Changed page `<title>` to **Horiseon Social Solutions**.
- In the `<body>` changed `<div>` to `<header>`
- In the `<header>` changed `<div>` to `<nav>`
- Modified indentation of the `<nav>` `<ul>` `<li>`
- In the `<body>` changed `<div>` to `<figure>`
- In the `<body>` changed `<div>` to `<section>`
- In the `<section>` changed 3 instances of `<div>` to `<article>`
- In the `<section>` added alt attributes to 3 `<img>` tags
- In the `<section>` added missing *search-engine-optimization* id for navigation
- In the `<body>` changed `<div>` to `<aside>`
- In the `<aside>` added alt attributes to 3 `<img>` tags
- In the `<body>` changed `<div>` to `<footer>`
- Included comments noting code changes as appropriate

### style.css
- renamed `.header div` selector to `.header nav`
- renamed `.header div ul` selector to `.header nav ul`
- renamed `.header div ul li` selector to `.header nav ul li`
- reorganized selectors to group like classes
- included comments identifying logical groupings
- Included comments noting code changes as appropriate

## Sources Referenced
[w3schools](https://www.w3schools.com/html/html5_semantic_elements.asp),
[markdownguide](https://www.markdownguide.org/cheat-sheet/),
[makeareadme](https://www.makeareadme.com/)