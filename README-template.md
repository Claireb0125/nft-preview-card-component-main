# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

This is my first solution from the Frontend Mentor challenges, As a new and still learning developer I have found this xtremely rewarding and has taught me more than I imagined when I first decided to attempt this project. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](https://file%2B.vscode-resource.vscode-cdn.net/c%3A/VSCode/NFT/nft-preview-card-component-main/images/Capture.PNG?version%3D1667834642835)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/nft-preview-card-component-3MBDmikeEc)
- Live Site URL: (https://claireb0125.github.io/nft-preview-card-component-main/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

Adding the hover view symbol and color was a real challenge for me. Not knowing where to really begin I did have a resort to watching a bit of a guide but did most myself once I grasped the concept. I will be linking the video at the end for anyone curious or having similar issues. 

```css
.container .main-img {
    position: relative;
}

.container .main-img div {
    position: absolute;
    top: 0;
    background-color: hsl(178, 100%, 50%, 60%);
    width: 100%;
    height: 100%;
    z-index: 999;
    opacity: 0;
    transition: opacity 0.5s ease-in-out;
}

.container .main-img div:hover {
    opacity: 1;
    cursor: pointer;
}

.container .main-img div img {
    position: absolute;
    left: 50%; 
    top: 50%;
    translate: -50% -50%;
```
If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Youtube Tutorial](https://www.youtube.com/watch?v=9bGbykdR4T8) - Tutorial mentioned in the "What I learned" section. 

## Author

- Github - [Claireb0125](https://github.com/Claireb0125)
- Frontend Mentor - [@claireb0125](https://www.frontendmentor.io/profile/Claireb0125)
- Codepen - [Claireb0125](https://codepen.io/claireb0125)
