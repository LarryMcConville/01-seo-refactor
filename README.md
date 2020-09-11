# Horiseon Social Solutions - Site Refactor

## Project Goal
For this project the customer requested we review their site for the following accessibility standards:
1. Semantic HTML elements
2. HTML elements which follow a logical structure
3. Ensure all image tags include alt attributes
4. Review Heading attributes for organization
5. Update Title element to be more descriptive and concise
6. Refactor code where appropriate for maintainability

## Change Log
### index.html
- Changed page `<title>` to **Horiseon Social Solutions**.
- In the `<body>` changed `<div>` to `<header>`
- In the `<header>` changed `<div>` to `<nav>`
- Modified indentation of the `<nav>` `<ul>` `<li>`
- In the `<body>` changed `<div>` to `<figure>`
- In the `<body>` changed `<div>` to `<section>`
- In the `<section>` changed 3 instances of `<div>` to `<article>`
- In the `<section>` added alt attributes to 3 `<img>` tags
- In the `<section>` added missing `search-engine-optimization` id for navigation
- In the `<section>` renamed the following classes:
  - `search-engine-optimization` to `content-article`
  - `online-reputation-management` to `content-article`
  - `social-media-marketing` to `content-article`
- In the `<body>` changed `<div>` to `<aside>`
- In the `<aside>` added alt attributes to 3 `<img>` tags
- In the `<body>` changed `<div>` to `<footer>`
- Included comments noting code changes as appropriate

### style.css
- Renamed `header div` selector to `header nav`
- Renamed `header div ul` selector to `header nav ul`
- Renamed `header div ul li` selector to `header nav ul li`
- Combined like properties of the following selectors under `.content-article`:
  - `search-engine-optimization`
  - `online-reputation-management`
  - `social-media-marketing`
- Combined like properties of the following selectors under `.content-article img`:
  - `.search-engine-optimization img`
  - `.online-reputation-management img`
  - `.social-media-marketing img`
- Combined like properties of the following selectors under `.content-article h2`:
  - `.search-engine-optimization h2`
  - `.online-reputation-management h2`
  - `.social-media-marketing h2`
- Combined like properties of the following selectors under `.benefits section`:
  - `.benefit-lead`
  - `.benefit-brand`
  - `.benefit-cost`
- Combined like properties of the following selectors under `.benefits h3`:
  - `.benefit-lead h3`
  - `.benefit-brand h3`
  - `.benefit-cost h3`
- Combined like properties of the following selectors under `.benefits img`:
  - `.benefit-lead img`
  - `.benefit-brand img`
  - `.benefit-cost img`
- Reorganized selectors to group related page elements
- Included comments identifying logical groupings
- Included comments noting code changes as appropriate

## Sources Referenced
[w3schools](https://www.w3schools.com/html/html5_semantic_elements.asp),
[markdownguide](https://www.markdownguide.org/cheat-sheet/),
[makeareadme](https://www.makeareadme.com/)