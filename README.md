# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned + Continued development](#what-i-learned+continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned + Continued development

While using absolute positioning with tranform: translate() to center the QR code card, the top percentage wasn't working. I realized that I needed to specify the height of the parent div to make it work (if I'm correct).

```css
body {
  font-family: "Outfit", sans-serif;
  font-size: 1.5rem;
  background-color: hsl(212, 45%, 89%);
  max-width: 144rem;

  margin: 0 auto;

  height: 100vh;
  position: relative;
}

.qrcode-card {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```

## Author

- Frontend Mentor - [@kongguksu](https://www.frontendmentor.io/profile/kongguksu)
