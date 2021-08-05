# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot - Desktop preview

<img  src= "https://github.com/rachderossi/front-end-mentor/blob/main/four-card-feature-section/Screenshot1.png">

### Links

- Solution URL: [4-card-feature-section](https://rachderossi.github.io/four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Web Design

### What I learned

```html
<section class="top-container" id="top-container">
  <div class="headings">
    <h1 class="first-line">
      <span style="color:hsl(229, 6%, 66%); font-weight: normal;">
        Reliable, efficient delivery
      </span>
    </h1>
    <h1 class="second-line"><strong> Powered by Technology </strong></h1>
    <p class="label">
      Our Artificial Intelligence powered tools use millions of project data
      points to ensure that your project is successful
    </p>
  </div>
</section>
```

```css
.cards-container {
  width: 1100px;
  height: auto;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  align-content: center;
  justify-content: center;
}
```
