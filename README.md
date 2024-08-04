# Frontend Mentor - Product preview card component (Test)

## 1. Overview

The challenge is to build out this Product preview card component and get it looking as close to the design as possible.

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

### a) My screenshot

![My screenshot for the Product preview card component coding challenge](./screenshot.jpeg)

### b) Links

- Solution URL: [my source code here](https://github.com/hieutrantrong21520859MMCL21/FrontEndPractice_Intern_ProductPreviewCardComponent)
- Live Site URL: [my website's URL here](https://hieutrantrong21520859mmcl21.github.io/FrontEndPractice_Intern_ProductPreviewCardComponent/)

## 2. My process

### a) Built with

- Semantic HTML
- CSS
- Mobile - first workflow

### b) What I learned

- How to design following mobile - first workflow.
- How to use semantic HTML markup (*picture*, *section*, ...).
- How to use *float layout* in CSS.
- How to use variables in CSS.
- How to apply a new component *button*.
- Some codes I am most proud of (which consist of knowledge I have learned):

```css
:root {
  --font_montserrat: 'montserrat', serif;
  --font_fraunces: 'fraunces', sans-serif;
}
```
```html
<picture class="product_image col-left">
      
      <source media="screen and (min-width: 599px)" srcset="./images/image-product-desktop.jpg" alt="desktop image">

      <img src="./images/image-product-mobile.jpg" alt="mobile image">

</picture>
```

### c) Useful resources

- [MDN - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML): this helped me a lot about HTML via articles.
- [Learn HTML](https://web.dev/learn/html): this is an amazing website that provides lessons about HTML with examples.
- [MDN - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS): this helped me well with CSS via articles.
- [Learn CSS](https://web.dev/learn/css): this is an amazing website that provides lessons about CSS with examples.
- [CSS Responsive](https://www.w3schools.com/css/css_rwd_intro.asp): a brief explanation about website's responsiveness.