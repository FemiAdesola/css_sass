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
├── node_modules
│   ├── anymatch
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.d.ts
│   │   ├── index.js
│   │   └── package.json
│   ├── binary-extensions
│   │   ├── binary-extensions.json
│   │   ├── binary-extensions.json.d.ts
│   │   ├── index.d.ts
│   │   ├── index.js
│   │   ├── license
│   │   ├── package.json
│   │   └── readme.md
│   ├── braces
│   │   ├── CHANGELOG.md
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   ├── lib
│   │   │   ├── compile.js
│   │   │   ├── constants.js
│   │   │   ├── expand.js
│   │   │   ├── parse.js
│   │   │   ├── stringify.js
│   │   │   └── utils.js
│   │   └── package.json
│   ├── chokidar
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   ├── lib
│   │   │   ├── constants.js
│   │   │   ├── fsevents-handler.js
│   │   │   └── nodefs-handler.js
│   │   ├── package.json
│   │   └── types
│   │       └── index.d.ts
│   ├── fill-range
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   └── package.json
│   ├── fsevents
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── fsevents.d.ts
│   │   ├── fsevents.js
│   │   ├── fsevents.node
│   │   └── package.json
│   ├── glob-parent
│   │   ├── CHANGELOG.md
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   └── package.json
│   ├── immutable
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── dist
│   │   │   ├── immutable.d.ts
│   │   │   ├── immutable.es.js
│   │   │   ├── immutable.js
│   │   │   ├── immutable.js.flow
│   │   │   └── immutable.min.js
│   │   └── package.json
│   ├── is-binary-path
│   │   ├── index.d.ts
│   │   ├── index.js
│   │   ├── license
│   │   ├── package.json
│   │   └── readme.md
│   ├── is-extglob
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   └── package.json
│   ├── is-glob
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   └── package.json
│   ├── is-number
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   └── package.json
│   ├── normalize-path
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   └── package.json
│   ├── picomatch
│   │   ├── CHANGELOG.md
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.js
│   │   ├── lib
│   │   │   ├── constants.js
│   │   │   ├── parse.js
│   │   │   ├── picomatch.js
│   │   │   ├── scan.js
│   │   │   └── utils.js
│   │   └── package.json
│   ├── readdirp
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── index.d.ts
│   │   ├── index.js
│   │   └── package.json
│   ├── sass
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── package.json
│   │   ├── sass.dart.js
│   │   ├── sass.default.dart.js
│   │   ├── sass.js
│   │   └── types
│   │       ├── compile.d.ts
│   │       ├── exception.d.ts
│   │       ├── importer.d.ts
│   │       ├── index.d.ts
│   │       ├── legacy
│   │       │   ├── exception.d.ts
│   │       │   ├── function.d.ts
│   │       │   ├── importer.d.ts
│   │       │   ├── options.d.ts
│   │       │   ├── plugin_this.d.ts
│   │       │   └── render.d.ts
│   │       ├── logger
│   │       │   ├── index.d.ts
│   │       │   ├── source_location.d.ts
│   │       │   └── source_span.d.ts
│   │       ├── options.d.ts
│   │       ├── util
│   │       │   └── promise_or.d.ts
│   │       └── value
│   │           ├── argument_list.d.ts
│   │           ├── boolean.d.ts
│   │           ├── color.d.ts
│   │           ├── function.d.ts
│   │           ├── index.d.ts
│   │           ├── list.d.ts
│   │           ├── map.d.ts
│   │           ├── number.d.ts
│   │           └── string.d.ts
│   ├── source-map-js
│   │   ├── CHANGELOG.md
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── lib
│   │   │   ├── array-set.js
│   │   │   ├── base64-vlq.js
│   │   │   ├── base64.js
│   │   │   ├── binary-search.js
│   │   │   ├── mapping-list.js
│   │   │   ├── quick-sort.js
│   │   │   ├── source-map-consumer.js
│   │   │   ├── source-map-generator.js
│   │   │   ├── source-node.js
│   │   │   └── util.js
│   │   ├── package.json
│   │   ├── source-map.d.ts
│   │   └── source-map.js
│   └── to-regex-range
│       ├── LICENSE
│       ├── README.md
│       ├── index.js
│       └── package.json
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
### Steps taken 
<ol>
    <li>The parent (upstream) forked from the repo @integrify GitHub account </li>
    <li>The repository cloned from @integrify GitHub </li>
</ol>