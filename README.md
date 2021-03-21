## DoIT Accessibility script

## Installation

```
git clone https://github.com/ICJIA/doit-accessibility.git
npm install
```

## To Lint and Build

`npm run prestart`

### To include in a project:

#### Script tag:

`<script src="https://cdn.jsdelivr.net/gh/icjia/doit-accessibility/dist/index.js">`

#### Programmatic:

```
document.body.appendChild(document.createElement('script')).src = 'https://cdn.jsdelivr.net/gh/icjia/doit-accessibility/dist/index.js';
```
