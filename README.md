# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](finished-work.jpg)

### Links

- Solution URL: [Add solution URL here](https://benjamin-onu.github.io/result-summary-component-main/)
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project was a very good challenge in that I learnt most especially more from its position and layout. I realized that to see the magic of flexbox properties, the elements have to be children of a parent element that has its display property as flex. This was a challenge indeed.
Making your website mobile friendly is very important but this had lot of differences in terms of layout which is what I get to practice doing and getting used to. This was where I used CSS grid to get the layout.

To see how you can add code snippets, see below:

```html
<div id="reaction" class="subjects">
        <div>
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20"><path stroke="#F55" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.25" d="M10.833 8.333V2.5l-6.666 9.167h5V17.5l6.666-9.167h-5Z"/></svg>
          <h4>Reaction</h4>
        </div>
        <p><strong>80</strong>&nbsp;/&nbsp;100</p>
      </div>
```
```css
.subjects{
    display: flex;
    justify-content: space-between;
    margin: 1em;
}
```

### Continued development
I mainly just focused on perfecting HTML and CSS, I'll keep practicing absolute and relative positioning

### Useful resources
- [Example resource 1]([https://flexboxfroggy.com/]) - This helped me to clarify flexbox properties

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@Benjamin-Onu]([https://www.frontendmentor.io/profile/Benjamin-Onu])
