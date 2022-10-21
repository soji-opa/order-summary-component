# Frontend Mentor - Order summary card

This is a solution to the [Order summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/screenshot.png)

### Links

- [Order summary component](https://order-summary-component-jet-nu.vercel.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I gained basic understading of implementing hover elements.

```css
button {
	display: block;
	width: 100%;
	border: none;
	border-radius: 10px;
	padding: 1em 0;
	background-color: var(--clr-brblue);
	color: var(--clr-white);
	margin-top: 10px;
	font-weight: 700;
	font-size: 16px;
	cursor: pointer;
}

button:hover {
	background-color: var(--clr-dsblue);
}

.alt-btn {
	background: none;
	color: var(--clr-dsblue);
	box-shadow: none;
}

.alt-btn:hover {
	background: none;
	color: var(--clr-dkblue);
}
vertical-align: bottom;
```

### Useful resources

- [Scrimba](https://scrimba.com/learn/learnreact) - This platform provided me with an opportunity to learn react for free

## Author

- Github - [@soji](https://github.com/soji-opa)

## Acknowledgments

I am very grateful to [Smug](https://github.com/theadusamuel) & [Openwell](https://github.com/openwell) for always making time out of their busy schedules to see to my coding challenges and providing me with extra motivation.
