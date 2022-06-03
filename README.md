# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![project screenshot](./design/desktop-design.jpg)

### Links

- Solution URL: [Solution Page](https://www.frontendmentor.io/solutions/interactive-nft-preview-card-using-flexbox-OLukGygML1)
- Live Site URL: [Live Site](https://attia-mahmoud.github.io/NFT-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Color blend an image on hover

```css
.image-container:hover::before {
  content: "";
  position: absolute;
  left: 0rem;
  top: 0rem;
  right: 0rem;
  bottom: 0;
  background: red;
  opacity: 0.7;
  mix-blend-mode: multiply;
}
```

## Author

- Website - [Mahmoud Attia](https://www.mahmoudattia.com)
- Frontend Mentor - [@mahmoud-attia](https://www.frontendmentor.io/profile/attia-mahmoud)
