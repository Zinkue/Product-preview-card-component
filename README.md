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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Web Preview](images\web-preview.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

How to add an icon to the tab of the page

```html
<link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
```

The utilities of overflow 

```css
#card {
    overflow: hidden;
}
```

The properties of background images

```css
#card > #img {
    background-image: url(./images/image-product-desktop.jpg);
    background-size: cover;
    background-position: top;
}
```
