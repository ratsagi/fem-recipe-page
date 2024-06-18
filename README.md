# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [ Live site URL ](https://ratsagi.github.io/fem-recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM

### What I learned
I learned about difference between div and section. I find out that section is landmark if it has  role of region. We should have aria-label or labeledby attribute in order to make it. Otherwise there is no difference between them.
```html
  <section  aria-labelledby="preperation-time">
    <p id="preperation-time"> Preparation time</p>
    </section>
``` 
I also learned how to remove gaps between borders of th and td with border-collapse property:
```css
table,th,td{
  border-bottom:1px solid var(--lightGrey);
  border-collapse: collapse;
 }
```
### Useful resources

- [True section](https://www.youtube.com/watch?v=ULdkpU51hTQ) - This video from Kevin Powel helped me to recognize the difference between div and section.

## Author

- Website - [Sagi](https://github.com/ratsagi)
- Frontend Mentor - [@ratsagi](https://github.com/ratsagi)
- Twitter - [@Sagi31758105](https://x.com/Sagi31758105)
