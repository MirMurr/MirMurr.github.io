# MirMurr.github.io
# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [Overview](#overview)
  - [The challenge](#the-challenge)
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
Users should be able to:

- View the optimal layout for the component depending on their device's screen size

### Links
live site [https://mirmurr.github.io/index.html]


## My process
- I worked with felxbox and used relative and absolute positioning to position the elements on the page appropriately. I applied the mobile-first principle.


### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned
- Adding padding-bottom: 100% to the second conatiner, made it the same size as the first container. Without this property the 2. conatiner would be smaller.

- Combining Flexbox and Positioning relative and absolute.

- Predefining font-sizes and using them as variables makes it easy to edit the font-size in responsive mode. Example: 

```css
:root {
    --fs-600: 2.1875rem; /*div booking text h2*/
    --fs-500: 1.125rem; /*div booking text p*/
    --fs-400: 0.65625rem; /*type */
    --fs-300: 0.8125rem; /*num*/
    --fs-200: 0.625rem; /*chat header h4 and chat messages */
    --fs-100: 0.6875rem; /*chat header h3 */
}


@media only screen and (min-width: 768px) {
    :root {
    --fs-600: 2.5rem;
    --fs-500: 1.2rem; 
    }
}


### Continued development
- Combination of Flexbox and Positioning (relative, absolute)
- Backgound image sizing and positioning
- Color theory
- Responsive typography


### Useful resources
- Kevin Powell´s youtube tutorial: (https://www.youtube.com/watch?v=wARbgs5Fmuw) - Helped me with responsive typography and how to change the font sizes easily in the media queries.
- (https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This guide helped me with flexbox properties.
- (https://www.w3schools.com)


## Author
- Frontend Mentor - [@MirMurr](https://www.frontendmentor.io/profile/MirMurr)


## Acknowledgments
Kevin Powell´s YouTube tutorials always help me to find better CSS solutions. 



DIFFICULTIES: 
Working with the 2 purple shapes in the background if they are not set as a background image. I coded both shapes and tried to work with positioning. However in responsive mode it wasn´t successful. That´s why I set the images as backgound image. 

QUESTIONS: 
Positioning the 2 purple shapes so that they render properly in responsive mode. 

Please if you have some suggestions how to solve it better, do not hesitate to share. :)
