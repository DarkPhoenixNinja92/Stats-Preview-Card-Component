# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot/Stat-Preview-Component.png)

### Links

- Solution URL: [https://github.com/DarkPhoenixNinja92/Stats-Preview-Card-Component](https://github.com)
- Live Site URL: [https://darkphoenixninja92.github.io/Stats-Preview-Card-Component/](darkphoenixninja92.github.io)

## My process

### Built with

- Semantic HTML5 markup
- SCSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This gave me a great chance to learn about how filter works in CSS since this is something I had never used before. I also got more practice with flexbox layouts and combining positioning with flex to be more precise with my text positioning when flex alone won't cut it.

```css
.card img {
    filter: invert(40%) sepia(95%) saturate(434%) hue-rotate(233deg) brightness(96%) contrast(91%);
}

### Continued development

In the future, I want to work on getting better at using the filter in css. In this project, I had to use a user made app on codepen to convert a hex code version of my hsl to a filter code in future and I would like to not have to resort to that in future.

### Useful resources

- [CSS Tricks - Filter](https://css-tricks.com/almanac/properties/f/filter/) - This helped me figure out how to do the image color change as, prior to this, the only thing I really knew about CSS filter was that it existed.
- [Codepen](https://codepen.io/sosuke/pen/Pjoqqp) - This is the codepen I mentioned above. It's an app that takes a hex color code and converts it to a working filter function with all the relevant values applied.

## Author

- Website - [Add your name here](https://www.shaunpourdev.com)
- Frontend Mentor - [@DarkPhoenixNinja92](https://www.frontendmentor.io/profile/DarkPhoenixNinja92)
- GitHub - [@darkphoenixninja92](https://github.com/DarkPhoenixNinja92)