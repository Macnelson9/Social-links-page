# Social-links-page
This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This challenge was quite easy to implement because I have been practicing other tougher challenges and I'm starting to get familiar with using HTML and CSS. Overall, I hope you find something useful here. Thank you.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/social-links-profile-personalized-nY46lzjkH0)
- Live Site URL: (https://github.com/Macnelson9/Social-links-page.git)

## My process

So at first glance, I already knew that I was going to tackle this challenge using Flexbox which I did and it was quite simple. Although, I ran into a bit of a challenge when I initally had put the a tags (hyperlinks tags) inside of button tags. It worked quite alright that way but the hover effect in this method will only change the color of text inside the button when you hover around the link itself on the button and not when you hover around the entire button. I then figured out that if I instead put the button tags inside of a tags, it works perfectly and even the button becomes clickable unlike how it was initially. And also the styling of the buttons became different for me because I was used to using padding to give it a width and a height but I figured using the width and height properties directly is far much better and neater. Think that does it. I'll be available for any clarification of sorts. Thank you and Happy Coding!

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learnt that instead of putting the a tags inside of the button tags, it's best to put the button tags inside of the a tags, thereby making the entire button a link and the a clickable one at that.

To see how you can add code snippets, see below:

```html
<div class="buttons">
  <a href="https://www.github.com/Macnelson9" target="_blank">
    <button type="button">GitHub</button></a
  >

  <a href="https://www.frontendmentor.io/profile/Macnelson9" target="_blank"
    ><button type="button">Frontend Mentor</button></a
  >

  <a href="https://www.linkedin.com/in/uche-ofatu" target="_blank"
    ><button type="button">LinkedIn</button></a
  >

  <a href="https://x.com/Macnelson92" target="_blank"
    ><button type="button">Twitter</button></a
  >

  <a href="#" target="_blank"><button type="button">Instagram</button></a>
</div>
```

```css
Here is how the buttons were styled:
.buttons {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  align-items: center;
  gap: 10px;
}

button {
  background: var(--grey);
  width: 221.13px;
  height: 33px;
  border-radius: 5px;
  border: none;
  cursor: pointer;
  color: var(--white);
  font-family: "Inter", sans-serif;
  font-size: 10px;
  font-weight: 600;
}

/* Pseudo element */
button:hover {
  background: var(--green);
  color: #141414;
}


### Continued development

I will continue to implement using button tags inside of a tags for continued development. I'm glad I got to solve this challenge and figure out how it all works.

## Author

- Frontend Mentor - [@Macnelson9](https://www.frontendmentor.io/profile/Macnelson9)
- Twitter - [@Macnelson92](https://www.x.com/Macnelson92)
-Linkedin - [Uche Ofatu](https://www.linkedin.com/in/uche-ofatu)

## Acknowledgments

I'm grateful to Copilot for helping me out by suggesting that the button tags be inside the a tags and it worked.
```

