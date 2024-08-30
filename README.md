# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./Screenshot%20.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/samritbasnet/Four-card-feature-section)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned about grid layout in this project and the ways to organize and use different properties of grid layout of css and the pseudo class selector to color the elements.

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.card-container {
  display: grid;
  grid-template-columns: repeat(3, 10fr);
  gap: 20px;
  margin-top: 60px;
}

.card:nth-child(1) {
  grid-column: 1;
  grid-row: 1 / span 2;
  align-self: center;
}

.card:nth-child(1)::before {
  background-color: hsl(180, 62%, 55%);
}

.card:nth-child(2) {
  grid-column: 2;
  grid-row: 1;
}
```

### Useful resources

- [CSS TRICKS]https://css-tricks.com/snippets/css/complete-guide-grid/#aa-basics-browser-support) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
  t.

## Author

- Frontend Mentor - [@SamritBasnet](https://www.frontendmentor.io/profile/Samritbasnet)
- Twitter - [@SamritBasnet70](https://www.twitter.com/SamritBasnet70)
  .
