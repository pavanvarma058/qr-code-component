# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

I have completed the an "QR Code Component Project" challenge on Frontend Mentor. To complete this challenge i used web technologies like a Markup language **HTML**, and a style sheet language **CSS**.

### Screenshot

![Screenshot](./images/Screenshot%202025-02-19%20170516.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

To define my process, i can simply say that, at the start i have understood what i have to build by seeing the actual finished project. Then, i followed the README, where they guided through the styling part and it really helped me..!

### Built with

- HTML5
- CSS
- CSS - Flexbox
- Mobile-first workflow

### What I learned

While Building this project I got better at CSS flexbox really and also this is my first time writing media queries on my own and it went pretty well while adjusting the screen sizes for different devices.

To see how you can add code snippets, see below:

```css
.container {
  background-color: hsl(212, 45%, 89%);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}
```

```css
@media (min-width: 325px) and (max-width: 575px) {
  .content {
    width: 250px;
  }

  .img-qr {
    width: 220px;
    height: 220px;
  }
}
@media (min-width: 576px) and (max-width: 768px) {
  .content {
    width: 280px;
  }

  .img-qr {
    width: 250px;
    height: 250px;
  }
}

@media (min-width: 769px) and (max-width: 1280px) {
  .content {
    width: 300px;
  }

  .img-qr {
    width: 270px;
    height: 270px;
  }
}
```

### Continued development

I really want to continue building projects that both supports mobile and desktop or any other device, for that i have to be more good at understanding media quries, right now i'm better but i'll try to improve more..!

And also i'll try to add more stylish to the project next time which it looks more beautiful for UI

### Useful resources

- [MDN Web DOcs](https://developer.mozilla.org/en-US/) - This helped me for understanding media queries and flexbox while building the project.

## Author

- Name - **Pavan Varma**
- Frontend Mentor - [@pavanvarma058](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@pavan_varma_728](https://www.twitter.com/pavan_varma_728)

## Acknowledgments

I really thank the Frontendmentor.io team for giving this type of challenges for beginners. By builidng this type of projects they can really understand the fundamentals and complex topics.

Thank You 🙏🏼
