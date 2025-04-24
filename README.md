# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

This is my fifth project and it's responsive using flexbox.

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Solution URL here](https://github.com/MgMyatHtayKhant/product-preview-card-component-main)
- Live Site URL: [Live site URL here](https://previewing-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned a lot about flexbox, media query and resuable code.

```css
.d-flex {
  display: flex;
  align-items: center;
  justify-content: center;
}

@media only screen and (min-width: 48em) {
  html {
    font-size: 16px;
  }

  .container {
    flex-direction: row;
    align-items: stretch;
  }

  .container > * {
    max-width: 300px;
  }

  .left-side .product-image {
    height: 100%;
    border-radius: 0.5rem 0 0 0.5rem;
  }

  .fraunces-font {
    font-size: 2.25rem;
  }
}
```

## Author

- Website - [Saul](https://saul-homepage.netlify.app/)
- Frontend Mentor - [@Saul](https://www.frontendmentor.io/profile/MgMyatHtayKhant)

## Acknowledgments

This project is done by myslef and I'm proud of it.
