# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./New Desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- JavaSript
- Mobile-first workflow


### What I learned

```html
  Can I use Frontend Mentor projects in my portfolio?
```
```css
.accordion-item-header::after {
  content: url(./assets/images/icon-plus.svg);
 
}
```
```js
 const currentlyActiveAccordionItemHeader = document.querySelector(".accordion-item-header.active");
    if(currentlyActiveAccordionItemHeader && currentlyActiveAccordionItemHeader!==accordionItemHeader) {
      currentlyActiveAccordionItemHeader.classList.toggle("active");
      currentlyActiveAccordionItemHeader.nextElementSibling.style.maxHeight = 0;
    }
```


### Continued development

i want to learn more on how to build FAQs Accordion with css and javascript only.

### Useful resources

- @import url('https://fonts.googleapis.com/css?family=Montserrat');- This helped me for setting a good font. I really liked this pattern and will use it going forward.



## Author

- Website - [Johnson Olayemi](https://jonzdee.github.io/My-Portfolio/)
- Frontend Mentor - [@Jonzdee](https://www.frontendmentor.io/profile/@Jonzdee)
- Twitter - [@Yemtech7878](https://www.twitter.com/@Yemtech7878)

