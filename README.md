# Frontend Mentor - Stats preview card component solution

This is a solution from Dimitris Kaffes to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

Mobile-first design was implemented.

For a simple project like this, the CSS naming convention chosen uses hyphen delimeter class names.

CSS Grid was used for both mobile and desktop version.

The `picture` element was implemented for loading the mobile and desktop version of the image.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot of the solution](./images/screenshot-solution.jpg)

### Links

- Solution URL: [stats-preview-card-component solution on Github](https://github.com/dkaffes/stats-preview-card-component)
- Live Site URL: [stats-preview-card-component live site](https://dkaffes.github.io/stats-preview-card-component/)

## My process

The HTML was structured using semantic elements.

The CSS styling was done trying to avoid unnecessary declarations.

A mobile-first approach was followed.

CSS Grid was implemented for both mobile and desktop versions.

Flexbox was used for the desktop version of the statistics list.

The desktop and mobile version of the image are loaded using the `picture` element. A blending of a `background-color` on the `.image-box` along with `mix-blend-mode` and `opacity` properties on the `<image>` element give the overall result.

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Further investigated the importance of a solid HTML structure and the proper use of elements (semantic or not).

How to use the `<picture>` element.

How to achieve a blending of a `background-color` on a parent element with an `<image>` child element.

### Continued development

Better understanding of the manipulation of images related to their parent box and their aspect ratio.

### Useful resources

- [CSS Naming Conventions](https://www.freecodecamp.org/news/css-naming-conventions-that-will-save-you-hours-of-debugging-35cea737d849/) - An article that explains in a simple way the different Naming Conventions.

## Author

- Frontend Mentor - [@dkaffes](https://www.frontendmentor.io/profile/dkaffes)
