# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](./assets/images/Screenshot%202024-10-17%20at%2022-24-49%20Frontend%20Mentor%20Recipe%20page.png)


### Links

- Solution URL: [Solution URL here](https://github.com/stephany247/recipe-page)
- Live Site URL: [Live site URL here](https://stephany247.github.io/recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

- I learned how to customize list markers, changing bullet colors and aligning list content.

```css
li {
  padding: 0.3rem 0 0.3rem 0.8rem;
}

li::marker {
  font-weight: 700;
  color: var(--Brown-800);
}
```
- Styling table rows with borders and ensuring proper column spacing and alignment.

```css
table {
  border-collapse: collapse;
  width: 100%;
  margin: 1rem 0;
}
```
- Targeting specific screen widths for better control over your layout on mobile, tablet and desktop devices.

```css
@media screen and (min-width: 720px) {
  body {
    background-color: var(--Stone-100);
  }

  .container {
    width: 710px;
    border-radius: 20px;
    margin: 100px auto;
  }
}  
```


### Continued development

While I used a mobile-first workflow, I want to continue refining my skills in making layouts more responsive across a wider range of screen sizes and devices, ensuring perfect fluidity.

### Useful resources

- [Google Fonts](https://fonts.google.com/) - This helped me understand how to embed custom fonts into my project and manage different font weights and styles.
- [Stack Overflow](https://stackoverflow.com/) - I found helpful solutions for CSS issues, like handling hover effects and box shadows, which were crucial for implementing the card design in this project.


## Author

- Website - [Onyinye Stephanie Oguocha](https://www.your-site.com)
- Frontend Mentor - [stephany247](https://www.frontendmentor.io/profile/stephany247)
- Twitter - [@stephanyoguocha](https://x.com/stephanyoguocha)


## Acknowledgments

I would like to give a big thanks to the Frontend Mentor community and the resources on Stack Overflow for helping me troubleshoot and improve my project.

