# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](Screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 - For the semantic structure of the profile. 
- CSS3 - Custom Properties and Flexbox.
- Google Fonts API.
- Spck Editor - The mobile Integrated Development Environment (IDE), used to write and test code on the go.
- Git/GitHub.
- GitHub pages.

### What I learned

For the html code, if my social link isn't inside a class link container, it'll just show a blue link without a clickable button, and that's what happened initially before I tackled that issue. 

The CSS code with the .social-link is what helped me have that we'll centered and nice bottons.

```html
<h1>Some HTML codes I learnt something from</h1>
<div class="links-container">
    <a href="https://github.com/Ghod-Zilla12" class="social-link">GitHub</a>
    <a href="https://www.frontendmentor.io/profile/Ghod-Zilla12" class="social-link">Frontend Mentor</a>
    <a href="www.linkedin.com/in/samuel-udo-dev" class="social-link">LinkedIn</a>
    <a href="#" class="social-link">Twitter</a>
    <a href="#" class="social-link">Instagram</a>
  </div>
  </main>
```
```css
.social-link {
  display: block;
  width: 100%;
  box-sizing: border-box;
  padding: 12px;
  background-color: var(--grey-700);
  color: var(--white);
  text-decoration: none;
  font-weight: 600;
  border-radius: 8px;
  margin-bottom: 12px;
  transition: background-color;
}
```

### Continued development

Refining a card image and make it clickable is what I'm working toward in my future projects. 

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)?
- How did you use them (e.g., debugging, generating boilerplate, brainstorming solutions)?
- What worked well? What didn't?

**Note: Delete this note and the content above if you didn't use AI, or replace with your own experience.**

## Author

- Frontend Mentor - [Ghod-Zilla12]()
- Facebook - [Zilla]()
- LinkedIn - [Samuel udo](www.linkedin.com/in/samuel-udo-dev)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**

