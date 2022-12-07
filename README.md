# CSS/SASS , Grid , Flexbox Tasks
![](https://img.shields.io/static/v1?label=HTML&message=v.5&color=red)
![](https://img.shields.io/static/v1?label=CSS&message=v.3&color=blue)
![](https://img.shields.io/static/v1?label=SCSS&message=v.1.56&color=blue)

This is a SASS, SCSS  practice @integrify.

## Table of content
- [Technologies](#technologies)
- [Requirements](#requirements)
- [Project structure](#project-structure)
- [Getting started](#getting-started)

---
## Technologies
- HTML
- SCSS/SASS for styling
    - Variable
    Mixin
    Extend
- CSS
    - Flex and Grid system

---
## Requirements

1. Floating of the HTML elements
    - Flexbox and Grid system were used
2. Animations was Implemented on
    - The webpage
    - Hover effect,
    - Active link styles,
    - Typing effect
    - Outlook of the effects were modified

---
## Project structure
```shell
.
├── README.md
├── img
│   ├── Header.png
│   ├── Transition.png
│   ├── hover.png
│   └── transform.png
├── package-lock.json
├── package.json
└── src
    ├── css
    │   ├── styles.css
    │   └── styles.css.map
    ├── index.html
    └── scss
        ├── features
        │   └── _button.scss
        ├── sections
        │   ├── _footer.scss
        │   ├── _header.scss
        │   └── _main.scss
        ├── shared
        │   ├── inheritance
        │   │   └── _mixins.scss
        │   └── variables
        │       ├── _colors.scss
        │       ├── _fonts.scss
        │       └── _spacing.scss
        └── styles.scss
```
---
## Getting started

### Header

- By hovering on the link, it displays gray color on each link, when clicking on each link the gray color turn to yellow.

![header](/img/Header.png)

---
### Flexbox, transition and text transformation

- CSS flexbox used for text writing, and the width of the text container is determined by the actual length of the text being used in this website. 

![Transition](/img/Transition.png)

---
### Grid 
- The CSS Grid Layout Module was in layout for each section with rows and columns. On hovering each card, the background image transform, and an arrow floats out before each bolder text.

![transform](/img/transform.png)

---
### Steps taken 
<ol>
    <li>The parent (upstream) forked from the repo @integrify GitHub account </li>
    <li>The repository cloned from @integrify GitHub </li>
</ol>

### Acknowledgement
This design was formulated from this [website](https://maido-dark.fueko.net/)