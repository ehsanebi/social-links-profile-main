# Frontend Mentor - Social links profile solution

This is my solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

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



## Overview

This project is a responsive social links profile page built as part of a Frontend Mentor challenge.



### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page.

### Screenshot

![](/design/screenshot.jpg)

### Links

- Solution URL: https://github.com/ehsanebi/social-links-profile-main.git
- Live Site URL: https://ehsanebi.github.io/social-links-profile-main/

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS logical properties
- Flexbox
- `clamp()`
- Mobile-first workflow

### What I learned

I learned how to use the `clamp()` function more effectively to make layouts responsive without relying on media queries.  
This helped me better understand fluid sizing and how elements can scale smoothly across different screen sizes.

I also learned that using CSS logical properties (such as `inline` and `block`) is a better practice, especially for multilingual and internationalized websites. Without them, layout issues can occur when text direction changes.

Some CSS code I’m proud of:

```css
body {
  min-block-size: 100vb;
}

.main {
  max-inline-size: 24rem;
}

.container {
  padding: clamp(1.5rem, 8.4vw, 2.5rem);
}

```



### Continued development

I plan to continue using logical properties and the clamp() function in future projects.
I believe these are modern CSS features that will become more common and are essential for building flexible and accessible layouts.

Useful resources

### Useful resources

- (https://youtu.be/cV9JhEV4Ll0?si=jL-aWjiKQWoGyv8S) - This video helped me for learning and understanding Logical Properties. I really liked it and it have lot's of good example.


