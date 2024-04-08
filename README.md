# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./assets/images/screenshot.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/singe-page-card-component-DU0OR3UB6U)
- Live Site URL: [Live Site URL](https://craigwolfe.github.io/single-price-component-challenge/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<section id="bottom-left-section">
  <h3>Monthly Subscription</h3>
  <div id="price-container">
    <div id="price">$29</div>
    <div id="price-frequency">per month</div>
  </div>
</section>
```

```css
@media (min-width: 576px) {
  #card {
    height: 400px;
    width: 600px;
  }
  #bottom-right-section,
  #bottom-left-section {
    width: 50%;
  }
}
```

## Author

- Frontend Mentor - [@craigwolfe](https://www.frontendmentor.io/profile/craigwolfe)
