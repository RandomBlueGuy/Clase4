# Make It Real - NAME OF THE PROJECT

This is a solution to the HTML 4 My Team Page project of the Make It Real course.

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Su desafío es construir una pagina responsive para mostrar a tu team y lograr que se parezca lo más posible al diseño.

Puedes usar cualquier herramienta que te guste para ayudarte a completar el desafío. Entonces, si tienes algo que te gustaría practicar, no dudes en intentarlo.

Sus usuarios deberían poder:

Ver el diseño óptimo según el tamaño de pantalla de su dispositivo

### Screenshot

![](./screenshot.jpg)

Se agregan los screenshots 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Se aplica la propiedad grid para el manejo de las columnas tanto en la version desktop como en mobile.

```html
<div class="crew">
```
```css
.crew {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 5px;
}

.crew-con{
        display: grid;
        margin: auto;
        grid-template-columns: repeat(2,1fr);       
        width: 80%;     
    }
```



### Continued development

Reforzar en el manejo de :nth-child y que se evidencia que es una muy buena herramienta.

### Useful resources

- [Example resource 1](https://css-tricks.com/snippets/css/complete-guide-grid/) - Para la definicion de las cuadriculas


## Author

[Andres Velez and Oscar Nuñez]


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
