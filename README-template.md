# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

This is my first practice project to exercise my html/css skills. It's a simple order summary component. My focus is on replicating its look and layout, responsiveness, and the button interactions.

### The challenge

- Replicating the layout and style
- See hover states for interactive elements
- Responsiveness

### Screenshot

-N/A

## My process

I first started with the HTML markup and planned out my parent/child orientations. Then in mobile first, I focused on the textual heirarchy with sizing, weight, and color. Afterwards I began spacing the elements out similarly to the references. I began tweaking in select spots to get it as close as I could.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

-One of the snags that I encountered was trying to create a helper class for spacing things out. It worked for all except it was overriding the summary text and was not centering like I hoped. So I did away with the spacing helper class and did it specifically for each element. This may be something that I can come back to and refactor some of my styling, but for now I left it so it is functional.

-Something that struggled to find a good solution for is the spacing of the music note svg, Annual plan info, and the change link. My first attempt is to use flex spacing to space them evenly, but it still wasnt quite right. I tried adding a negative left margin to the Annual Plan but it isnt very responsive when going from mobile to desktop.

-A puzzling thing that I've encountered is trying to center the parent container inside the body tag will not center vertically. I've come to find that setting the top and bottom margin to auto does not work the same way as left and right, so that wont work. I've tried flexbox and align-content on the body, doesnt work. I tried absolute positioning and transform top and left on the child, doesnt work.

### Continued development

### Useful resources

-https://stackoverflow.com/questions/6775273/why-dont-margin-top-auto-and-margin-bottomauto-work-the-same-as-their-left-an
