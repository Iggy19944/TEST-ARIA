# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Dark cyan: hsl(158, 36%, 37%)
- Cream: hsl(30, 38%, 92%)

### Neutral

- Very dark blue: hsl(212, 21%, 14%)
- Dark grayish blue: hsl(228, 12%, 48%)
- White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size (paragraph): 14px

### Font

- Family: [Montserrat](https://fonts.google.com/specimen/Montserrat)
- Weights: 500, 700

- Family: [Fraunces](https://fonts.google.com/specimen/Fraunces)
- Weights: 700




<!--  -->
HTML

<s><span class="visually-hidden">Old price: </span>$169.99</s>

CSS

mark,
del,
s {
  position: relative;

  &::before,
  &::after {
    @extend .visually-hidden;
  }
}



s::before {
  content: ' [strike-through start] ';
}
s::after {
  content: ' [strike-through end] ';
}



