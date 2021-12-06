# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [dev-rome](https://www.frontendmentor.io/profile/dev-rome/solutions)
- Live Site URL: [NFT-Card-Component](https://wizardly-ritchie-7bf14e.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Two things I learned during the making of this project. One will be the use of the after pseudo-element. The second will be the use of the content element. I was able to create a line instead of using the hr tag. Also was able to use the view SVG in the content and center it along with the hover state of changing the background color on hover.

```css
.data-wrapper::after {
	content: " ";
	border-bottom: 1px solid var(--line-color);
	margin: 2.5rem 0 1.5rem;
}
```

```css
.card-img:hover::after {
	content: url("/images/icon-view.svg");
	position: absolute;
	display: flex;
	justify-content: center;
	align-items: center;
	width: 302px;
	height: 302px;
	background: hsla(178, 100%, 50%, 0.4);
	cursor: pointer;
	border-radius: 8px;
}
```

### Continued development

Going foward will continue to work on writing better semantic HTML5 markup, and better CSS with flexbox.

## Author

- Github - [@dev-rome](https://github.com/dev-rome)
- Frontend Mentor - [@dev-rome](https://www.frontendmentor.io/profile/dev-rome)
- Twitter - [@rome_dev](https://twitter.com/rome_dev)
- Linkedln - [@dev-rome](https://www.linkedin.com/in/jerome-haynes/)
