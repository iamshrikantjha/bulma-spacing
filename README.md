# Bulma Spacing


> Missing Bulma spacing library without JavaScript dependency for pixel perfect designs. You can use library with or without Bulma 

[![NPM](https://nodei.co/npm/bulma-spacing.png?stars&downloads)](https://nodei.co/npm/bulma-spacing/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![npm package](https://img.shields.io/npm/v/bulma-spacing.svg)](https://www.npmjs.org/package/bulma-spacing) [![downloads](https://img.shields.io/npm/dt/bulma-spacing.svg)](https://www.npmjs.com/package/bulma-spacing) [![size](https://img.shields.io/bundlephobia/minzip/bulma-spacing)](https://www.npmjs.com/package/bulma-spacing)

<a href="https://bulma.io"><img src="https://raw.githubusercontent.com/jgthms/bulma/master/docs/images/bulma-banner.png" alt="Bulma: a Flexbox CSS framework" style="max-width:100%;" width="600"></a>
<a href="https://github.com/kaangokdemir/bulma-spacing"><img src="https://bulma.io/images/extensions/bulma-spacing.png" alt="Bulma Spacing" style="max-width:100%;" width="600"></a>

## Installation and Usage

### With JavaScript (Recommended)

#### Install Module First

```bash
# Yarn
yarn add bulma-spacing
```
```bash
# NPM
npm i bulma-spacing
```
#### Then just import in your .js file

```javascript
import 'bulma-spacing/css/bulma-spacing.min.css'
```


### Without JavaScript

#### Add that line into your head element

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma-spacing/css/bulma-spacing.min.css">
```

## How to use

### Keywords
```css
properties: margin padding
directions: top, right, bottom, left
values(px): -100, -99, -98 ... -1 0 1 2 3 ... 98 99 100 (-100 to 100)
```

### For positive numbers

```css
.{property}-{direction}-{value}
```
```
.margin-top-24 // margin-top: 24px !important
.padding-right-6 // padding-right: 6px !important
.margin-left-0 // margin-left: 0px !important
```
### For negative numbers

```css
.{property}-{direction}-minus-{value}
```
Note: negative padding is not supported by CSS
```
.margin-top-minus-100 // margin-top: -100px !important
.margin-bottom-minus-17 // margin-bottom: -17px !important
.margin-right-minus-33 // margin-right: -33px !important
```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

### Contributors

Kaan Gökdemir - Author ([@kaangokdemir](https://twitter.com/kaangokdemir)) - [kaangokdemir.com](https://kaangokdemir.com) 

### License

MIT

