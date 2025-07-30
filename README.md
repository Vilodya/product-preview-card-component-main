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
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [solution URL](https://github.com/Vilodya/product-preview-card-component-main)
- Live Site URL: [live site URL](https://vilodya.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Creating a full-screen section — I learned to use min-height: 100vh to make a section take up the full height of the browser window.

Fixing the footer at the bottom — I understood how to use a flex container (display: flex; flex-direction: column;) and margin-top: auto to stick the footer to the bottom, even when there isn't much content.

```css
body {
  display: flex;
  flex-direction: column;
  font-family: var(--main-font);
  font-size: var(--main-font-size);
}

main {
  display: flex;
  flex: 1;
  justify-content: center;
  align-items: center;
  background-color: var(--Cream);
}
```

## Author

- Website - [LinkedIn](https://www.linkedin.com/in/vladimir--denisov)
- Frontend Mentor - [@Vilodya](https://www.frontendmentor.io/profile/Vilodya)