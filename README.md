# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-article-preview-component-56J8uh5qM4)
- Live Site URL: [GitHub Pages](https://valeriamontoya.github.io/article-preview-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

From this project I've learned how to implement the following with JS:

- How to use `classList.toggle()` to show or hide an element by adding or removing a class
- How to dynamically change the appearance of elements using inline styles

```js
function toggleSection()  {
  shareSection.classList.toggle('visible');
  changeButtonColors();
}

function changeButtonColors() {
  if (shareSection.classList.contains('visible')) {
    shareButton1.style.backgroundColor = 'var(--grey-500)';
    shareIcon.style.fill = 'var(--white)';
  } else {
    shareButton1.style.backgroundColor = '';
    shareIcon.style.fill = '';
  }
}
```

## Author

- Frontend Mentor - [@ValeriaMontoya](https://www.frontendmentor.io/profile/ValeriaMontoya)
- Twitter - [@val_smf](https://twitter.com/val_smf)
