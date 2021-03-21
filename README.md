## DoIT Accessibility script

## Installation

```
git clone https://github.com/ICJIA/doit-accessibility.git
npm install
```

## Lint and build

`npm run prestart`

### Usage:

#### Script tag:

`<script src="https://cdn.jsdelivr.net/gh/icjia/doit-accessibility/dist/index.js">`

#### Programmatic:

```
document.body.appendChild(document.createElement('script')).src = 'https://cdn.jsdelivr.net/gh/icjia/doit-accessibility/dist/index.js';
```
