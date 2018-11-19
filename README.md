# Next.js + Jsons

Import json in [Next.js](https://github.com/zeit/next.js)
(jsons)

## Installation

```
npm install --save next-jsons
```

or

```
yarn add next-jsons
```

## Usage

Create a `next.config.js` in your project

```js
// next.config.js
const withJsons = require('next-jsons')
module.exports = withJsons()
```

Optionally you can add your custom Next.js configuration as parameter

```js
// next.config.js
const withFonts = require('next-jsons')
module.exports = withJsons({
  webpack(config, options) {
    return config
  }
})
```
