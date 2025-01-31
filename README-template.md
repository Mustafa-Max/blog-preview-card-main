![image](https://github.com/user-attachments/assets/708a7766-84e7-44f8-8fb2-4ab58f9d4d31)# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![image](https://github.com/user-attachments/assets/b9bd4180-95ad-48a1-aee2-a7851e4ceaf7)

### Links

- Solution URL: https://github.com/Mustafa-Max/blog-preview-card-main
- Live Site URL: https://mustafa-max.github.io/blog-preview-card-main

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<main class="card">
      <img
        src="./assets/images/illustration-article.svg"
        alt="Article illustration"
      />
      <span class="tag">Learning</span>
      <p class="date">Published 21 Dec 2023</p>
      <h1 class="title">HTML & CSS foundations</h1>
      <p class="description">
        These languages are the backbone of every website, defining structure,
        content, and presentation.
      </p>
      <div class="author">
        <img src="./assets/images/image-avatar.webp" alt="Greg Hooper avatar" />
        <span class="author-name">Greg Hooper</span>
      </div>
```
```css
.card {
  background-color: var(--white);
  border-radius: 20px;
  padding: 1.5rem;
  max-width: 375px;
  border: 1px solid var(--gray-950);
  box-shadow: 8px 8px 0 var(--gray-950);
  transition: all 0.2s ease-in-out;
}
}
```

### Useful resources

- [VS Code](https://code.visualstudio.com/) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Website - [Mustafa-Max](https://github.com/Mustafa-Max)
- Frontend Mentor - [@Mustafa-Max](https://www.frontendmentor.io/profile/Mustafa-Max)
