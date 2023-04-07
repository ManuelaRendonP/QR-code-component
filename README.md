# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![Screenshot Desktop](./images/Screenshot%20Desktop.png)
![Screenshot Mobile](./images/Screenshot%20Mobile.png)

### Links

- Solution URL: [Solution Github](https://github.com/ManuelaRendonP/QR-code-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Media queries

### What I learned

I learned how to use the CSS transform property, mainly to center a div:

```html
<div class="card">
  <img src="images/image-qr-code.png" alt="QR code" class="QR-img">
</div>
```
```css
.card {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

### Continued development

I will focus a little more on the use of the display, both grid and flex, since it is a little difficult to remember what each one can do.

### Useful resources

- [Resource 1](https://www.freecodecamp.org/espanol/news/centrar-en-html-div-con-css/) - This resource helped me as I was having difficulty centering the div. It pointed me in the right direction.

## Author

- Website - [Manuela Rendon de la Pava](https://portfolio-manuela-rendon.netlify.app/)
- Frontend Mentor - [@ManuelaRendonP](https://www.frontendmentor.io/profile/ManuelaRendonP)
- Twitter - [@xPLDRMx](https://www.twitter.com/xPLDRMx)
