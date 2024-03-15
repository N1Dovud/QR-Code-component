# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Links

- Solution URL: [Add solution URL here](https://github.com/N1Dovud/QR-Code-component)
- Live URL: (https://n1dovud.github.io/QR-Code-component)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Today, I realized that I had to apply the flexbox to the body instead of the main so that the main becomes centered. I learned more about inheritance and its impace on children from parents.

```css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: var(--light-gray);
}
```
### Continued development

Unfortunately, I did not quite understand why setting the height of the body to 100vh centered the main content vertically. Logically, I thought as default, the height is always set to 100vh but now I guess there is smth to learn.

## Author

- Frontend Mentor - [N1Dovud](https://www.frontendmentor.io/profile/N1Dovud)