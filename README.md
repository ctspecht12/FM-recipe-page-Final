# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Challenge is to build out this recipe page and get it looking as close to the design as possible.

### Screenshot

![](https://github.com/ctspecht12/FM-recipe-page-Final/blob/e013c10e6121ba960a5fa3d0ba96db62e773bade/recipe-page-main-desktop-FINAL.png)
![width:100px;](https://github.com/ctspecht12/FM-recipe-page-Final/blob/e013c10e6121ba960a5fa3d0ba96db62e773bade/recipe-page-main-mobile-FINAL.png.png)

### Links

- Solution URL: [Solution](https://github.com/ctspecht12/FM-recipe-page-Final)
- Live Site URL: [Live Site](https://ctspecht12.github.io/FM-recipe-page-Final/)

## My process

-I started by applying element tags to the HTML and separating sections into divs. Then, I applied the CSS styles for the desktop site using the colors and fonts from the style guide and the .jpg as a reference. Finally, I added @media styles to make it more responsive. 

### Built with

- Visual Studio Code

### What I learned

This was mainly a review for me as I haven't been coding in a while. The main challenges I had to figure out were styling the hr rules and figuring out how to properly style and space the li markers. These are the solutions I ended up using.

hr {
  margin-top: 2rem;
  height: 1px;
  color: hsl(30, 18%, 87%);
  background: hsl(30, 18%, 87%);
  font-size: 0;
  border: 0;
}

ul,
ol {
  margin: 0 0 0.5rem 1.2rem;
  padding: 0;
}
li {
  margin: 0 0 0.7rem 0;
  padding-left: 1rem;
}

li::marker {
  color: hsl(14, 45%, 36%);
  font-size: 14px;
}

ol li::marker {
  font-weight: bold;
}

### Continued development

I just intend to keep practicing to get more fluent and comfortable with coding.

## Author

- Frontend Mentor - [@ctspecht12](https://www.frontendmentor.io/profile/ctspecht12)

