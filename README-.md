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
This was my forst front end mentor project and I aimed to test my skills with simple layout using block and inlne elements.  The clalenge was to make a stats preview card that could be viewed in different ways depening on whether it was viewed by mobile or desktop.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot
![image](https://user-images.githubusercontent.com/83555918/146539407-e3bc9ceb-e159-4a24-88d9-884966481284.png)


### Links

- Solution URL: https://github.com/Clare1950/stats_preview_card
- - Live Site URL: https://clare1950.github.io/stats_preview_card/

## My process
I first downloaded and edited the html code to give it the sections needed to apply css.
I started with the mobile view and worked through each section in order applying the css until I was happy.
I then changed to the desktop view and went through the same process until I was happy with the look.
I then went through the css to try and remove or condense the code to make it as slimline as possible.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned to ise css to add a colored filter to an image:

.desktop-img {
  object-fit: cover;
  opacity: 0.6;
}

.image-container {
  background-color: hsl(277, 91%, 50%);
}

I learned to use flex-box order to re-order my elements in desktop view:

.image-container {
    display: flex;
    order: 2;
    width: 50%;
  }


  .main-content {
    order: 1;
    padding:50px;
    width: 50%;
  }
  
  I used media queroes and display none to swap images over at different screen sizes:
  
  @media screen and (max-width: 600px) {
  .desktop-img {
    display: none;
  }
}

@media screen and (min-width: 600px) {
  .mobile-img {
    display: none;
  }
 

### Continued development

In future I would like to develelop my use of flex-box and explore more of its features as I feel if I had understood this better my layout would have been easier. to create


### Useful resources

- https://dev.to/ellen_dev/two-ways-to-achieve-an-image-colour-overlay-with-css-eio.  This helped me to figure out how to make a colored overlay and also contains another method which I'd like to try in future.
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/.  This is a very good visual guide to flex-box which helped me with some layout issues.


## Author


- Frontend Mentor - https://www.frontendmentor.io/profile/Clare1950
-

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments



**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
