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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

One  should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![desktop screenshot](./images/Screenshot%202022-09-08%20at%2015-49-26%20Frontend%20Mentor%20Stats%20preview%20card%20component.png)
![mobile screenshot](./images/Screenshot%202022-09-08%20at%2015-50-44%20Frontend%20Mentor%20Stats%20preview%20card%20component.png)


### Links

- Solution URL: [stats card](https://github.com/Wahomethegeek/Stats-Preview-Card.git)
- Live Site URL: [stats preview card](https://statspreviewcard-wahome.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow using media query


### What I learned

I was able to learn more in grid and flexbox. I was able to change order of how the image and text and change using order property.


```css
   /* the lower the image the content appears first*/
    .image-component{
        order: -1;
    }
```
```css
.card-stats{
    display: flex;
    justify-content: space-between;
    text-transform: uppercase;
    padding-top: 55px;
}
```
```css
/* for the image and the content to appear on one column we use grid */
.wrapper{
    background: hsl(244, 38%, 16%);
    display: grid;
    grid-template-columns: 1fr 1fr;
    border-radius: 15px;
    overflow: hidden;
    margin: 2rem;

}
```


### Continued development

I have realised css has a big scope and I need to give it more time and take consistency in learning areas such as order property and css grid.


## Author

- Frontend Mentor - [@wahomethegeek](https://www.frontendmentor.io/profile/Wahomethegeek)
- Twitter - [@_Wahomekelvin](https://twitter.com/_Wahomekelvin)


