# Frontend Mentor - Blog Preview Card Solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## 📋 Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- View the blog preview card with a clean, faithful layout
- See hover and focus states for all interactive elements on the page

### Screenshot

![Blog Preview Card Solution](./screenshot.jpg)


## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox for layout
- Google Fonts — [Figtree](https://fonts.google.com/specimen/Figtree)
- Mobile-first approach

### What I Learned

This challenge helped me reinforce some core CSS concepts I'm actively studying:

**CSS Custom Properties** — Using variables like `--Yellow` and `--Gray500` made the color palette much easier to manage and keep consistent throughout the file.

```css
:root {
  --Yellow: hsl(47, 88%, 63%);
  --White: hsl(0, 0%, 100%);
  --Gray500: hsl(0, 0%, 42%);
  --Gray950: hsl(0, 0%, 7%);
}
```

**Box Shadow for depth** — Getting the card's signature hard shadow right was a key detail:

```css
box-shadow: 10px 10px 0 0 rgba(0, 0, 0, 0.08);
```

**Flexbox centering** — Vertically and horizontally centering the card on the viewport using `min-height: 100vh` combined with flexbox on `body` was a clean solution.

### Continued Development

Areas I want to keep improving on future projects:

- **CSS transitions** on hover states — I want to add smooth transitions to the card title link and the entire card hover effect
- **Responsive design** — Practicing fluid layouts and proper breakpoint decisions
- **Accessibility** — Improving focus states and ensuring proper semantic HTML for screen readers
- **CSS Grid** — Incorporating grid for more complex layout challenges ahead

---

## Author

- Frontend Mentor — [@danilo-guimaraes](https://www.frontendmentor.io/profile/danilo-guimaraes)
- GitHub — [@danilo-guimaraes](https://github.com/danilo-guimaraes)
- LinkedIn — [Danilo Guimarães](https://www.linkedin.com/in/daniloguimaraes-it/)
