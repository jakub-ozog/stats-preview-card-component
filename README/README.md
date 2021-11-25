# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: [Vercel](https://stats-preview-card-component-git-spc-jacobharraldson.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- Sass custom variables (all compiled to the CSS)
- Flexbox
- Desktop-first workflow
- [Sass](https://sass-lang.com/) - Sass pre-processor

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In this challenged I have practiced using Sass pre-processor, including custom variables (``@use``method) as well as some more advanced image styling such as ``mix-blend-mode`` or ``-webkit-filter``. This was very helpful especially in terms of Sass usage which is my goal. Also, this was a great opportunity to work with ``@media-queries`` which was a bit challenging sometimes.

This is the code or code snippets that I am proud of in terms of this project:

```css
@use "components/colors";
@use "components/fonts";
```

```css
.module-description {
  color: colors.$SlightlyTransparentWhite2;
  font-family: fonts.$InterFont;
  line-height: 1.8em;
  font-size: fonts.$BodyFontSize;
  margin-bottom: 2.1em;
}
 ```

### Continued development

For any of the project like this I would like to learn more about the CSS breakpoints especially for devices with different height attribute. My project is not fully optimized in this field yet.

### Useful resources

- [Sass Documentation](https://sass-lang.com/documentation/at-rules/use) and [Stack Overflow](https://stackoverflow.com/questions/66193156/live-sass-compiler-use-causes-compilation-error) - These were my guides if in terms of overall Sass usage, especially for the ``@use`` method - At the very beggining I had a problem with compiling that correctly into the CSS file.  
- [DevMDN](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) - Mainly, I was refering to that source if it comes to the blending mode creation.

## Author

- Frontend Mentor - [@jacobharraldson](https://www.frontendmentor.io/profile/jacobharraldson)
