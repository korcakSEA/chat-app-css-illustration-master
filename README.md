# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Screenshot

![](./![alt text](image.png))


### Links

- Solution URL: (https://github.com/korcakSEA/chat-app-css-illustration-master.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I would say that the toughest part is creating a background and making it responsive. This is the only solution I've managed so far. If you have any other solutions, please let me know.

You can see the code snippet below

```css
.left-top{
    width: 500px;
    height: 800px;
    background: var(--gradient-primary);
    border-radius: 0 0 250px 250px;

    position: absolute;
    left: min(-5rem, calc(30vw - 420px));   
    top: min(-7rem, calc(30vw - 420px));  
    z-index: -1;
   
}

.right-bottom{
    width: 500px;
    height: 800px;
    background: var(--color-text-grayish-blue);
    opacity: 0.1;
    border-radius: 250px 250px 0px 0px;

    position: absolute;
    right: min(-8rem, calc(30vw - 420px));  
    bottom: min(-7rem, calc(30vw - 420px)); 
    z-index: -1;
}
```

## Author

- Frontend Mentor - [@korcakSEA](https://www.frontendmentor.io/profile/korcakSEA)
