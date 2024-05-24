# Frontend Mentor - Single-page developer portfolio solution

This is a solution to the [Single-page developer portfolio challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/singlepage-developer-portfolio-bBVj2ZPi-x). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#Daniel-C-Igbokwe)
- 

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- Receive an error message when the `form` is submitted if: My 
  - Any field is empty                           (DONE)
  - The email address is not formatted correctly  (DONE)
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Hook the form up so it sends and stores the user's enquiry (you can use a spreadsheet or Airtable to save the enquiries)
- **Bonus**: Add your own details (image, skills, projects) to replace the ones in the design


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Vanilla Javascript
- Mobile-first workflow


### What I learned


```css I'm proud of

 #header {
    background-image: url(./assets/images/image-profile-desktop.webp);
    background-size: 30%;
    background-repeat: no-repeat;
    background-position: bottom 40px right 100px;
}

.projects .wrapper {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 40px;
    padding: 10px 10%;
}
```
```js
const sideMenu = document.getElementById("sidemenu");

function openmenu() {
    sideMenu.style.right = "0";
}

function closemenu() {
    sideMenu.style.right = "-200px";
}
```

I learned about background-size. I didn't understand background sizes could be changed, but to get the accuracy of how this project was designed, I discovered there were other ways of using background size to reduce the width of the background image.
I also learned about background-image. Which I used to get the correct placement for the image.

I also learned more about css grid works. I understood it more working on the experience section to get the arrangement of the project images. How grid-template-columns work and it specify sizing functions of grid column. MDN Docs was a huge help for this project.

I also built a menu bar fot the mobile using onclick() in html and using them as functions in javascript.




### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

I want to later use this project to make my own portfolio website. I want to add my vibrancy to some images and complete its responsiveness much more

### Useful resources

- [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns) - This helped me for understand grid-columns a lot better. I really liked this pattern and will use it going forward.
- [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image) - It really helped me understand background-images, background-size a lot better.


## Author

- Website - [Daniel-C-Igbokwe](https://www.your-site.com)
- Frontend Mentor - [@Daniel-C-Igbokwe](https://www.frontendmentor.io/home)
- Twitter - [@Daniel C Igbokwe](https://x.com/DanielIgbokwe20)



