# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover and focus states for interactive elements

### Screenshots

#### Desktop 

![Desktop Screenshot](images/screenshot-desktop.png)

#### Mobile

![Mobile Screenshot](images/screenshot-mobile.png)

### Links

- Solution URL: [Github](https://github.com/lindajensen/fem-product-preview-card-component-main.git)
- Live Site URL: [Netlify](https://ruby-product-preview-card-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

First time ever I tried a mobile-first flow and didn't get frustrated out of my mind. So I guess I'm getting better and I've learnt a bit more about that approach. It seems to be less komplex to do a mobile first approach. Like there isn't as much code to be written. But that could just be this challenge. I also learned a bit about the picture element and using two different images one for mobile and one for desktop.  

```html
        <picture>
          <!-- Desktop image -->
          <source media="(min-width: 768px)" srcset="/images/image-product-desktop.jpg">
          <!-- Mobile image -->
          <img src="/images/image-product-mobile.jpg" alt="Chanel Perfume">
        </picture>
```
```css
@media screen and (min-width: 48em) {
    .container {
        display: flex;
        flex-direction: row;
        max-width: 600px;
    }

    .image img {
        border-top-right-radius: 0;
        border-bottom-left-radius: 8px;
        height: 100%;
    }

    .content {
        width: 90%;
    }

    .content h1 {
        font-size: 2.3rem;
        margin-top: 0.938rem;
        margin-bottom: 1.875rem;
    }

    body {
        font-size: 0.92rem;
    }

    .main {
        margin: 8rem 0;
    }
}
```

### Continued development

I need to keep practicing a mobile-first workflow and also keep working on responsive typography and layout. Try and learn a bit more about how I can use CSS to my advantage, because it's like if I just code it right then a lot of things are responsive by nature. 

### Useful resources

- [Sitepoint](https://www.sitepoint.com/improving-responsive-images-picture-element/) - This helped me with how the picture element works. 

## Author

- Github - [Linda Jensen](https://github.com/lindajensen)
- Frontend Mentor - [@lindajensen](https://www.frontendmentor.io/profile/lindajensen)
- LinkedIn - [Linda Jensen](www.linkedin.com/in/linda-jensen-swe)
