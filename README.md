# Hidden-Search-Widgets

This is apart of the 50 projects in 50 days challenge and is the fourth project.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

- To create a search bar that expands, once clicked. The challenge involves HTML, CSS and Javascript.

### Screenshot

# Mobile Preview 

![screenshot](https://github.com/romila2003/Hidden-Search-Widgets/blob/main/Mobile%20preview.PNG)

# Mobile Preview - active

![screenshot](https://github.com/romila2003/Hidden-Search-Widgets/blob/main/Mobile%20preview-%20active.PNG)

# Desktop Preview 

![screenshot](https://github.com/romila2003/Hidden-Search-Widgets/blob/main/Desktop%20preview.PNG)

# Desktop Preview - active

![screenshot](https://github.com/romila2003/Hidden-Search-Widgets/blob/main/Desktop%20preview%20-%20active.PNG)


### Links

 - Source code: [https://github.com/romila2003/Hidden-Search-Widgets](https://github.com/romila2003/Hidden-Search-Widgets)
 - Live website: [https://hidden-search-widgets.netlify.app/](https://hidden-search-widgets.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Vanilla Javascript
- Flexbox

### What I learned

I learned more about the `toggle` feature within Javascript and feel more confident with this concept.

Javascript - close and open navbar:

```javascript

const search = document.querySelector(".search");
const btn = document.querySelector(".btn");
const input = document.querySelector(".input");

btn.addEventListener("click", () => {
    search.classList.toggle("active");
    input.focus()
});

```

### Continued development

For future developments, I should implement the `toggle` feature within Javascript into future projects such as the frontendmentor.io projects.


## Author

- Twitter - [@romila003](https://www.twitter.com/romila003)
- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
