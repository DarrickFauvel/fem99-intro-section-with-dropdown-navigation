# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Mobile screenshot](./screenshot-mobile.png)
![Desktop screenshot](./screenshot-desktop.png)

### Links

- Solution URL: [https://github.com/DarrickFauvel/fem09-single-price-grid-component](https://github.com/DarrickFauvel/fem09-single-price-grid-component)
- Live Site URL: [https://fem09-single-price-grid-component-drrck.netlify.app/](https://fem09-single-price-grid-component-drrck.netlify.app/)

## My process

### Built with

- Mobile-first workflow
- Semantic HTML5 markup
- CSS Grid
- Flexbox
- [Sass](https://www.sass-lang.com/) - CSS with superpowers
- [Vite](https://vitejs.dev/) - Superfast bundling tool

### What I learned

I learned to create a Sass function that converts px units to rem units. Here is the function I use for font sizing:

```scss
@use 'sass:math';

@function pxToRem($pxValue) {
  @return math.div($pxValue, 16) * 1rem;
}
```

### Continued development

I would like to possibly redo this solution using [Open Props](https://open-props.style/) sub-atomic styles.

### Useful resources

- [Sass: math.div function](https://www.sass-lang.com/documentation/modules/math#other-functions) - This is the modern method of dividing two numbers

## Author

- Frontend Mentor - [@DarrickFauvel](https://www.frontendmentor.io/profile/DarrickFauvel)
- LinkedIn - [Darrick Fauvel](https://www.linkedin.com/in/darrickfauvel/)

## Acknowledgments
