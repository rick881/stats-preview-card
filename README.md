# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge
Your challenge is to build out this stats preview card component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
\screenshots
stats card desktop.PNG
stats card mobile.PNG
stats card tablet.PNG


### Links

- Solution URL: [https://github.com/rick881/stats-preview-card.git](https://your-solution-url.com)
- Live Site URL: [https://rick881.github.io/stats-preview-card/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
For styles


### What I learned

- positioning elements with css
- using the [:after] pseudoclass

```css
.card .image:after {
    content: "";
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: rgba(136, 31, 201, 0.5);
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
}
```
If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

- css

### Useful resources

- [Example resource 1](https://www.w3schools.com) - This helped me with css. I really liked how straight foward it is and has practical live examples and will use it going forward.

- [Example resource 2] - just google thngs that i dont get and try them out.

## Author

- Frontend Mentor - [@rick881](https://www.frontendmentor.io/profile/rick881)


## Acknowledgments

- google
