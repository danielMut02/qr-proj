# Frontend Mentor - QR code component solution

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./desktop-design.png)

### Links

- Solution URL: https://danielmut02.github.io/qr-proj/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In the HTML section I worked with basic semantics and learnt how to structure my code:

```html
<body>
  <div class="contenedor">
  <div class="image-block"><img class="qr" src="./images/image-qr-code.png"></div>
  <h1 class="titulo">Improve your front-end skills by building projects</h1>

  <p class="interior">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p> 
  </div>
  <footer class="attribution">
    Challenge by <a class="detalle" href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a class="detalle" href="https://github.com/danielMut02" target="_blank">Daniel Mut Torres</a>.
  </footer>
</body>
```

In the CSS I learnt how to properly implement flex property and make my website responsive with the media queries.

## .contenedor is a class for a div containing the car with the QR code

```css
.contenedor{
    display: flex;
    flex-direction: column;
    width: 100%;
    max-width: 250px;
    padding: 16px; 
    margin-bottom: 40px; 
    background-color: var(--main-color);
    border-radius: 18px;
    box-shadow: 0px 15px 30px rgba(0, 0, 0, 0.1); 
    transition: transform 0.3s ease;
}
```

### Continued development

In current projects I want to target Grid properties to continue enhancing mi responsiveness abilities. Also, is my goal to develop projects including JavaScript, in order to make my websites more interactive. Later on, I will dive into JS frameworks and libraries such as ReactJS.

### Useful resources

- [DevDocs](https://devdocs.io/) - This is an amazing technical documentation site. It helped clarify some doubts I had on flex and responsiveness
- [w3schools](https://www.w3schools.com/) - This site helped with some code examples about making images responsive. Great when you don't know how to implement certain feature.

## Author

- Frontend Mentor - [@danielMut02](https://www.frontendmentor.io/profile/danielMut02)
- GitHub - [@danielMut02](https://github.com/danielMut02)

## Acknowledgments

Eternally thankful to freeCodeCamp since there I learnt everything I know so far. Through their guided course for web developers I found a new passion!
