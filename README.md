# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](https://media.discordapp.net/attachments/1067139053750845564/1085340297594159145/Captura_da_Web_14-3-2023_201440_.jpeg)
### Links

- Solution URL: [Repository in Github](https://github.com/Krampus-update/qr-code-component)
- Live Site URL: [Live Solution](https://krampus-update.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I was so happy when I learned how to use the onerror property for images! It saved me so much time and hassle when I wanted to share my web project with my friends. Instead of sending them two files (the index.html and the image), I could just send them one file that would load a different image if the original one was not found. This way, they could see how my project looked like with the right size and alignment. It was such a cool trick that made my life easier!

```html
      <img class="qr-code" src="./images/image-qr-code.png" onerror="this.src='https://cdn.discordapp.com/attachments/926995351871848500/1085327367037263882/image-qr-code.png'" width="90%" />
```
I was so frustrated with the vertical alignment of the page. I tried everything: changing the margins, padding, display, position, flexbox... Nothing worked. I spent half an hour banging my head against the wall. Then I realized it was something simple: I had a typo in the CSS file. I fixed it and voilà! The page looked perfect. I felt so relieved and happy. It was such a silly mistake but it taught me a valuable lesson: always check your code for typos!
```css
    body {
      background-color: hsl(212, 45%, 89%);
      height: 100vh;
      display: flex;
      align-items: flex-start;
    }
```

### Continued development

One of my goals for the future is to improve my group work skills and learn how to become more practical with programming. I think these are important abilities for finding a job in this field. To achieve this, I plan to take some online courses on collaboration tools and best practices, as well as practice coding on different platforms and projects. I also want to join some communities of programmers who can give me feedback and advice on how to improve my skills and portfolio.

## Author

- Website - [Pedro Alves](https://linktr.ee/umKrampus)
- Frontend Mentor - [@Krampus-update](https://www.frontendmentor.io/profile/Krampus-update)
- Twitter - [@Kr4mpus_](https://twitter.com/Kr4mpus_)

## Acknowledgments

I want to thank Malu (or Maria) for her invaluable help in testing my project. She was very patient, supportive and insightful throughout the process. I couldn't have done it without her!
