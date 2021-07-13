# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
This challenge started with the design that was provided where mobile version was implemented first and then was enlarged to desktop version where JS was added later for the popup button.

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![image](https://user-images.githubusercontent.com/42742924/125234542-ad2f5e80-e300-11eb-819e-6ee8b1c9af70.png)
![image](https://user-images.githubusercontent.com/42742924/125234572-b7e9f380-e300-11eb-8775-ac3fd3a8531a.png)

### Links

- Solution URL: [Solution URL](https://github.com/Skyz03/Article-preview-component)
- Live Site URL: [Live Site](https://skyz03.github.io/Article-preview-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

The most important thing I learned was to built from mobile version to desktop version plus I learned about the implementation of JS whenn the button gets clicked.

```js
function myFunction() {
  var popup = document.getElementById("myPopup");
  popup.classList.toggle("show");
}
```

### Continued development

The SVG image can be implemented as per given design where the arrow changes its color plus the animation to remove popup can be made smoother.

### Useful resources

- [W3 Schools popup creation](https://www.w3schools.com/howto/howto_js_popup.asp) - This helped me create pop up for the site.

## Author

- Website - Skyz03
