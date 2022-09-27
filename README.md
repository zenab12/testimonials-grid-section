# Frontend Mentor - Testimonials grid section solution
This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot


### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/product-preview-card-component-kJXMnUMI9F)
- Live Site URL: [Live Demo](https://zenab12.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- CSS BEM classes Names 

```html
<main class="card">
<div class="card__info">
  
      <p class="card__info--title">  Perfume</p>
      <h1> Gabrielle Essence Eau De Parfum    </h1>
      <p> A floral, solar and voluptuous interpretation composed by Olivier Polge, 
        Perfumer-Creator for the House of CHANEL. 
      </p>
  
</main>
```

- Picture element to make image responsive in html

```html
  <picture class="card__picture">
      <source media="max-width:767px" srcset="./images/image-product-mobile.jpg" alt=" Gabrielle Essence Eau De Parfum   ">
      <img  src="./images/image-product-desktop.jpg" alt="parfum" title=" Gabrielle Essence Eau De Parfum  ">
   </picture>  
```

### Useful resources

- [HTML Notes for professional book](https://www.computer-pdf.com/web-programming/html/827-tutorial-html5-notes-for-professionals-book.html) - HTML Notes for professional book help me in many important Notes.
- [CSS BEM](https://www.freecodecamp.org/news/css-naming-conventions-that-will-save-you-hours-of-debugging-35cea737d849/) - helped me in name classes in best pratice

### Author

- Frontend Mentor - [@zenab12](https://www.frontendmentor.io/profile/zenab12)
- Twitter - [@zenabmo90454136](https://twitter.com/zenabmo90454136)
- Linkedin -[@zienabmuhammad](https://www.linkedin.com/in/zienabmuhammad/)


