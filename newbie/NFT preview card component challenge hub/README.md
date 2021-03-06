# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshots

<img src="screenshots/nft-preview-card.png">
<p float="left">
  <img src="screenshots/nft-preview-card-mobile.png" width="400" height="500">
  <img src="screenshots/nft-preview-hover.png" width="400" height="500">
</p>

### Links
- Solution URL: [Github link](https://github.com/codeFliers/Frontend-mentor/tree/main/newbie/NFT%20preview%20card%20component%20challenge%20hub/solution)
- Solution LIVE: [Github live link](https://codefliers.github.io/Frontend-mentor/newbie/NFT%20preview%20card%20component%20challenge%20hub/solution/)
## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS

### What I learned

I learned how to center both horizontally and verticaly a div :  

```css
.centerVandH {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
```

And to make the page height relative the the viewport : 
```css
html, body {
    margin: 0;
    /* have the max height corresponding to the screen height (viewport height) */
    height: 100vh;
}
```

### Useful resources

- [resource 1](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/) - This helped me to center both horizontally and vertically.

