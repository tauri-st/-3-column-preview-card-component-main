# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop Styles](/final-build/3card-newbie-desktop.png)
![Mobile Styles](/final-build/3card-newbie-mobile.png)

### Links

- Solution URL: [Github Website](https://tauri-st.github.io/-3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This is my first truly independent project utilizing Flexbox, and I was definitely confused while trying to implement "mobile-first" at first. I started with a columns layout, but desktop > mobile was a more useful way to see what Flexbox needed to do: 'row wrap'!

I used Codepen and CSS Tricks to help me understand more about buttons because I have never used active states before.

At some point I was baffled to realize that the cards themselves had rounded corners. I always assumed shapes like this were set on a graphic but of course not! Messing with border-radius is fun but I don't understand the ratios well yet.

I'm proud that I recognized the desktop cards are overlapping and adjusted the margins to make them negative to achieve that effect.

**I got feedback and looked at the JPEG design which (vs the Figma comp) clearly shows that the center card has no rounded corners and only the outer corners do. Feedback also pointed out to me that my body element was not aligned in the center for the desired clear effect. :) The margins are NOT overlapped.

### Useful resources

- [CSS -Tricks](https://css-tricks.com/a-complete-guide-to-links-and-buttons/-) This helped me to understand how to use active states and the difference between semantic buttons and a hrefs styled to look like buttons.
- [Codepen](https://codepen.io/pouretrebelle/pen/npomqM) - I am still not clicking with how the radius work so had to find a codepen to get me within the ball park of the rounded corner look I am going for.

## Author

- Github - [@tauri-st](https://github.com/tauri-st)
- Frontend Mentor - [@tauri-st](https://www.frontendmentor.io/profile/tauri-st)
- LinkedIn - [@tauri-stclaire](https://www.linkedin.com/in/tauri-stclaire/)