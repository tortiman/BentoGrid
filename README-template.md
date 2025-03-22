# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Design the bento grid en penpot ![](./screenshot/Captura%20de%20pantalla%202025-03-22%20111817.png)
- Structure the html and css.
-

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<main class="main">
  <article class="container-grid">
    <div class="subcontainer-grid-left">
      <div class="subcontainer-grid-left-up"></div>
      <div class="subcontainer-grid-left-down"></div>
    </div>
    <div class="subcontainer-grid-right">
      <div class="subcontainer-grid-right-up">
        <div class="subcontainer-grid-right-up-left">
          <div class="subcontainer-grid-right-up-left-up"></div>
          <div class="subcontainer-grid-right-up-left-down">
            <div class="social-media"></div>
            <div class="calendar"></div>
          </div>
        </div>
        <div class="subcontainer-grid-right-up-right"></div>
      </div>
      <div class="subcontainer-grid-right-down">
        <div class="subcontainer-grid-right-down-left"></div>
        <div class="subcontainer-grid-right-down-right"></div>
      </div>
    </div>
  </article>
</main>
```

```css
:root {
  --Purple100: hsl(254, 88%, 90%);
  --Purple500: hsl(256, 67%, 59%);
  --Yellow100: hsl(31, 66%, 93%);
  --Yellow500: hsl(39, 100%, 71%);
  --White: hsl(0, 0%, 100%);
  --Black: hsl(0, 0%, 7%);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  display: flex;
  height: 100vh;
  justify-content: center;
  align-items: center;
}

.main {
  width: 1440px;
  height: 1056px;
  background-color: aliceblue;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container-grid {
  width: 1300px;
  height: 930px;
  background-color: beige;
  display: grid;
  grid-template-columns: 1fr 3fr;
  column-gap: 40px;
}

.subcontainer-grid-left {
  background-color: aqua;
  display: grid;
  grid-template-rows: 1fr 1fr;
  row-gap: 40px;
}

.subcontainer-grid-left-up {
  background-color: brown;
}

.subcontainer-grid-left-down {
  background-color: burlywood;
}

.subcontainer-grid-right {
  background-color: blue;
  display: grid;
  grid-template-rows: 2fr 1fr;
  row-gap: 40px;
}

.subcontainer-grid-right-up {
  background-color: blueviolet;
  display: grid;
  grid-template-columns: 2fr 1fr;
  column-gap: 40px;
}

.subcontainer-grid-right-up-left {
  background-color: wheat;
  display: grid;
  grid-template-rows: 1fr 1fr;
  row-gap: 40px;
}

.subcontainer-grid-right-up-left-up {
  background-color: violet;
}

.subcontainer-grid-right-up-left-down {
  background-color: antiquewhite;
  display: grid;
  grid-template-columns: 1fr 1fr;
  column-gap: 40px;
}

.social-media {
  background-color: cadetblue;
}

.calendar {
  background-color: azure;
}

.subcontainer-grid-right-up-right {
  background-color: tomato;
}

.subcontainer-grid-right-down {
  background-color: yellowgreen;
  display: grid;
  grid-template-columns: 1fr 2.21fr;
  column-gap: 40px;
}

.subcontainer-grid-right-down-left {
  background-color: chartreuse;
}

.subcontainer-grid-right-down-right {
  background-color: chocolate;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
