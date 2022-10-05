# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [Challenge](#challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size.
- See a hover state on desktop for the Sign Up call-to-action.

### Screenshot

![Screenshot of the solution](./images/screenshot.png)

### Links

- Solution URL: [See the code on GitHub](https://github.com/KristinaRadosavljevic/single-price-grid-component)
- Live Site URL: [View live site](https://single-price-grid-component-weld-mu.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS/Sass
- CSS grid

### What I learned

In this challenge, I got to practice using CSS grid in multiple situations. I also found an opportunity to try using Sass mixins, with both mandatory and optional arguments, as in the following code snippet:

```scss
@mixin secondary-heading($color, $margin: 1rem) {
  color: $color;
  margin-bottom: $margin;
  font-size: 1.1rem;
  font-weight: 700;
}
```

This proved very useful in terms of code reusability as I used this mixin with the `@include` statement in three declarations.

### Useful resources

I used [this article](https://sass-lang.com/documentation/at-rules/mixin) to help me understand how mixins work and how they're declared in the code.

## Author

- LinkedIn - [Kristina Radosavljevic](https://www.linkedin.com/in/radosavljevic-kristina/)
- GitHub - [KristinaRadosavljevic](https://github.com/KristinaRadosavljevic)
- Frontend Mentor - [@KristinaRadosavljevic](https://www.frontendmentor.io/profile/KristinaRadosavljevic)
