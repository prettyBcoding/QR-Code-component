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
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![My solution preview](https://raw.githubusercontent.com/prettyBcoding/QR-Code-component/2daec1900755b1952c71c7ef82793de81c3e2322/screenshot.png)


### Links

- Solution URL: https://raw.githubusercontent.com/prettyBcoding/QR-Code-component/e087f589ab4c4a7e92e14e3f82838e401d5a3b95/screenshot.png
- Live Site URL: https://prettybcoding.github.io/QR-Code-component/

## My process

First I wrote the HTML to focus my attention on creating well-structured content. And as I was writing the HTML, starting from top to bottom, I was adding some styles. Of course I encountered some difficulties, and I think the biggest one was to position the div in the center along with the content, and the detail of the contour of the edges

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

If there is something that I have learned in this project was to use the border-radius and box-shadow property. Because before this project I didn't know about their existence 😅, and when I see the design preview of the challenges I knew that I would have to use these properties even without know the name. And I used them in the div element:

```html
<div>
      <img src="images/image-qr-code.png" alt="QR Code">
      <h2>Improve your front-end skills by building projects</h2>
      <p>Scan the QR Code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
```

```css
div{
  background-color: white;
-->  box-shadow: 0 0 0 2rem white;  <--
-->  border-radius: 12px;           <--
  margin: 100px 500px;
  padding: 0 0 10px 0;
}
```

### Continued development

I'll still focus on HTML/CSS, to improve my skills. So for now I'll keep doing the challenges of Frontend Mentor untill I get  completely comfortable with it.

### Useful resources

- [Google fonts](https://fonts.google.com/specimen/Outfit) - This helped me to get the font of the challenge reason. 
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs) - This is an amazing web docs which helped me with the challenge's CSS part, for example, to round the corners of the div and image's outer border edge, and helped me with box-shadow too. I recommend it. It is useful if you know what you want but don't how use it in the code like css properties and whatever.
- [HTML Color Codes](https://developer.mozilla.org/en-US/docs/Web/CSS/) - I used it to convert the HSL color to Hex because the atom was warning about to use HSL.

## Author

Benolísio Baptista
* Instagram - [@benolisio](https://www.instagram.com/benolisio)

## Acknowledgments

Thanks to Angela Yu who put the link to Frontend Mentor in her Web Dev course. Now I can practice more HTML/CSS.

