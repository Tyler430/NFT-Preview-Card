# Frontend Mentor - NFT Preview Card Component Solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What issues I encountered](#issues-encountered)
  - [How did I resolve my encounters](#resolved-problem) 
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](https://user-images.githubusercontent.com/40303747/206097248-9ae92b5e-2eed-463f-83cb-02711b27d17e.png)
![](https://user-images.githubusercontent.com/40303747/206098386-bee4cffa-ae4a-48f5-8ad4-cc9531f3c3e8.png)

### Links

- Live Site URL: [Click Here!](https://nft-preview-card-tyler.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### Issues encountered

- The hover effect, to show the eye image and change the background to the cyan. Also with the exact same size of the Equilibrium image. 
![](https://user-images.githubusercontent.com/40303747/206099917-8480e264-7d69-44a3-8b93-a9516ccb93cf.png)

### Resolved problem

How did I resolve my issue from above?

- I wrapped the Equilibrium logo in `<picture></picture>` element tag.
- I put the eye image in a seperate tag, which was a `<div></div>`.

Then I used the following CSS3 styles.

```css
.eyeLook {
    position: absolute;
    top: 1rem;
    bottom: 14.6rem;
    left: 1rem;
    right: 1rem;
    display: grid;
    place-content: center;
    opacity: 0;
}

.eyeLook:hover {
    background-color: var(--cyan);
    opacity: .5;
}
```

## Author

- Frontend Mentor - [@Tyler430](https://www.frontendmentor.io/profile/Tyler430)
- Twitter - [@TylerF430](https://www.twitter.com/TylerF430)
