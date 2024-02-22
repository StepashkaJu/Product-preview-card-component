# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).
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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

1440px
![image](https://github.com/StepashkaJu/Product-preview-card-component/assets/121011573/f811c7ad-d5e9-4b34-91da-de6b8c41ffae)

375px
![image](https://github.com/StepashkaJu/Product-preview-card-component/assets/121011573/9b0d88d3-aecf-4de1-9e20-892200b5fae9)

### Links

- Solution URL: (https://stepashkaju.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Google Fonts
- Font Awesome icons

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

I found out how I can center card in the viewport

```css
.proud-of-this-css {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%)
}
```
I found out how I can use different images in depence on screen width
```html
<picture class="image">
        <source
          srcset="images/image-product-mobile.jpg"
          media="(max-width: 375px)"
        />
        <source
          srcset="images/image-product-desktop.jpg"
          media="(max-width: 1440px)"
        />
        <img
          src="images/image-product-desktop.jpg"
          alt="product image"
          class="card__picture"
        />
 </picture>
```
### Useful resources

- [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This helped me for learning the concept of adaptive images. I really liked this pattern and will use it going forward.

## Author
- GitHub - [StepashkaJu](https://github.com/StepashkaJu)
- Frontend Mentor - [@StepashkaJu](https://www.frontendmentor.io/profile/StepashkaJu)
