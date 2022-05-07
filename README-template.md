# Project Name - Portfolio

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
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

A portfolio of work can showcase your skills and talents to employers looking to fill a part-time or full-time position. An effective portfolio highlights your strongest work as well as the thought processes behind it. Students who have portfolios with deployed web applications (meaning they are live on the web) are typically very successful in their career search after the boot camp. This last point can’t be stressed enough: having several deployed projects is a minimum requirement to receive an initial interview at many companies.

### User Story

AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position


### Acceptance Criteria

GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport




### Links

- Solution URL: [GitHub](https://github.com/Snufalufakis/Homework-2)
- Live Site URL: [GitHub Live Site](https://github.snufalufakis.github.io/Homework-2/)

## My process
I broke this project into smaller parts to tackle parts of the whole process. Starting with the nav bar all the way down to the footer. Tackling it this way helped me out dermatically.

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

I struggled with buttons, list an unlisted order.
hours later I figured it out. 


```css
.nav {
    display: flex;
    justify-content: end;
    overflow: auto;
    background-color: var(--dark);
    font-family: 'Libre Baskerville', serif;
}

.nav a {
  font-size: 18px;
  color: white;
  text-align: center;
  padding: 14px 10px;
  text-decoration: none;
}

.nav a:hover {
  background-color: var(--secondary);
}
```

### Continued development

I really want to get the flexbox method down..
### Useful resources

- [Buttons](https://readlearncode.com/code-and-stuff/creating-buttons-from-ul-element/) - Was useful figuring our the buttons.
- [W3schools Click images](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_link_image) - Showed me a great method to make images clickable.


## Author

)
- Twitter - [@Snufalufakis](https://twitter.com/Snufalufakis2)


## Acknowledgments

A big thanks to Scott Nelson for the template.
