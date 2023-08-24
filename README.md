# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

./Screenshot.png

### Links

- Solution URL: https://github.com/sandu-motelica/social-proof-section-master.git
- Live Site URL: https://sandu-motelica.github.io/social-proof-section-master/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

With Flexbox, arranging elements within containers became a breeze. It made alignment and distribution a snap, adapting seamlessly to different screens. CSS Grid introduced me to two-dimensional layout control, making complex grid creation and responsiveness a cinch. And then there was background positioning — a simple yet impactful technique. By combining background images with precise positioning, I learned to create parallax effects, add visual interest, and enhance overall aesthetics.

html {
...
background-image: url("../images/bg-pattern-top-desktop.svg"),
url("../images/bg-pattern-bottom-desktop.svg");
background-repeat: no-repeat, no-repeat;
background-size: 40%, 70%;
background-position: left top, right bottom -20px;
}

.grid {
display: grid;
grid-template-columns: repeat(6, 1fr);
row-gap: 4.8rem;
column-gap: 3.2rem;
align-items: center;
}

## Author

- Frontend Mentor - [@sandu-motelica](https://www.frontendmentor.io/profile/sandu-motelica)
- GitHub - [@sandu-motelica](https://github.com/sandu-motelica)
