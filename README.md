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

`<script src="https://cdn.jsdelivr.net/gh/icjia/doit-accessibility/dist/index.js" async>`

#### Programmatic:

```
document.body.appendChild(document.createElement('script')).src = 'https://cdn.jsdelivr.net/gh/icjia/doit-accessibility/dist/index.js';
```

#### Nuxt:

`nuxt.config.js`

```
 script: [
      {
        src:
          'https://cdn.jsdelivr.net/gh/icjia/doit-accessibility/dist/index.js',
        async: true,
        body: true,
      },
    ],
```
