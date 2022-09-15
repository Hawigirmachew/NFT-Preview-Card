# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

NFT PREVIEW CARD COMPONENT

### Screenshot

Mobile view

![mobile-view](https://user-images.githubusercontent.com/88828065/190515700-479697f3-b1bc-4954-9cf2-c81d6c67f6e4.PNG)


Desktop view

![desktop-view](https://user-images.githubusercontent.com/88828065/190515751-cd119606-99cd-48b4-97e1-5a9310edd2c6.PNG)


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U/hub/responsive-page-using-css-flexbox-VHZ1h80gKU)
- Live Site URL: [Live site](https://dancing-genie-b8ac0a.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox



### What I learned
css code

.image{
    position:relative;
}
.image-view{
    height:100%;
    max-width:320px;
    width:100%;
    object-fit: cover;
    border-radius: 0.625rem;
    cursor: pointer;
    opacity: 1;
    transition: .5s ease;
    backface-visibility: hidden;
}
.backhover{
    transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  
}
.image:hover .image-view {
    opacity: 0.5;
}
.image:hover .backhover{
    opacity: 1;
}



## Author
- Website - [Hawi Girmachew](https://dancing-genie-b8ac0a.netlify.app/)
- Frontend Mentor - [@Hawigirmachew](https://www.frontendmentor.io/profile/Hawigirmachew)
- Twitter - [@girmachee_h](https://twitter.com/girmachee_h)
