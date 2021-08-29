# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](screenshots/screenshot.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

# CSS practice highlights:

/** using pseudo elements for invisible padding top/bottom  */
body::before,
body::after {
  content: "";
  height: 70px;
}

/** * Provide a intrinsic height for any parent and a min height to its children 
  * * (in our case, this will allow body tag to have a full broswer sized responsive background )  
  */

html {
  height: 100%;
}

body {
  min-height: 100%;
}

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Improvement on HTML masrkup is still neeeded as well as CSS writing, repititive code writing must be avoided. Responsiveness of website must always be taken into account. 

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Min-height? Body and html tag?](https://stackoverflow.com/questions/17555682/height-100-or-min-height-100-for-html-and-body-elements) - This helped me for responsive background   design. I really liked this pattern and will use it going forward.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@hanz02](https://www.frontendmentor.io/profile/hanz02)
- Instagram - [@moyashiii_02](https://www.instagram.com/moyashiii_02)
- Github = [hanz02](https://github.com/hanz02)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**
