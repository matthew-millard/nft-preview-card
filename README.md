# Frontend Mentor - nft-preview-card

Frontend Mentor challenge - nft preview card component

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the nft preview card depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![NFT preview card](/Screenshots/Desktop-Screenshot-Frontend-Mentor-NFT-Preview-Card-Component.png)

![NFT preview card](/Screenshots/Mobile-Screenshot-Frontend-Mentor-NFT-Preview-Card-Component.png)

### Links

- Solution URL: https://matthew-millard.github.io/nft-preview-card/

## My process

### Built with

- HTML
- CSS
- Flexbox
- Mobile-first workflow
- Andy Bell's modern css reset
- Firefox web developers tools
- VS code

### What I learned

- Using the visibility property to hide a page header landmark.
  `.visibility-hidden {
    visibility: hidden;
}`
- Adding images using the ::before pseudo element.
  `.price::before {
    content: url(/images/icon-ethereum.svg);
    position: relative;
    bottom: -2px;
    right: 3px;
}`

- Applying flex-wrap and gap properties for the first time.
  `.preview-card__artist {
    width: 80%;
    display: flex;
    gap: 8px;
    flex-wrap: wrap; 
    align-items: center;
    padding-top: .5rem;
}`

- Reinforcing what I learnt recently taking Kevin Powells 21 course on flexbox.
  `.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0 auto;
    width: 90%;
    max-width: 400px;
    background-color: hsl(216, 50%, 16%);
    border-radius: 1.5rem;
}`

### Continued development

- Become more familiar with the BEM naming convention.
- Keep progressing with CSS, and become more confident using flexbox and grid layouts
- Explore new trending styles
- Develop a better workflow

## Author

- Frontend Mentor - [@matthew-millard](https://www.frontendmentor.io/profile/matthew-millard)

- Github - [matthew-millard](https://github.com/matthew-millard)

## Acknowledgments

- Kevin Powell [@KevinPowell](https://www.youtube.com/kevinpowell)

- Andy Bell [@andybell](https://andy-bell.co.uk/a-modern-css-reset/)
