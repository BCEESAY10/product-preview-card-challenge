# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/Product%20card%20Desktop.png)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I have learned how to use CSS and display the mobile image and layout by default, and when the screen size is larger than 375px, it will switch the layout to a row and use the desktop image, by 
changing the content of the img.

To see how you can add code snippets, see below:

```css
 .container .card .image img{
        content: url('./images/image-product-desktop.jpg');
    }
```


## Author

- Website - [bamfa-portfolio.vercel]
- Frontend Mentor - [https://www.frontendmentor.io/profile/BCEESAY10]
