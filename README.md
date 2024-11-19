# Forge CSS

The official CSS implementation of the Forge design system created by [@zigurous](https://github.com/zigurous).

## Installation

### NPM

Set the scoped package registry in your `.npmrc` file:
```bash
registry=https://registry.npmjs.org/
@zigurous:registry=https://npm.pkg.github.com
```

Run one of the following commands in a terminal:
- Install with npm `npm install @zigurous/forge-css`
- Install with yarn `yarn add @zigurous/forge-css`
- Install with pnpm `pnpm add @zigurous/forge-css`

Import the css file in your code:
```js
import '@zigurous/forge-css/dist/index.min.css'
```

### CDN

Add one of the following links to your HTML:

#### Cloudfront

```html
<link href="https://cdn.zigurous.com/forge-css@1.0.0/dist/index.min.css" rel="stylesheet">
```

#### jsDelivr

```html
<link href="https://cdn.jsdelivr.net/gh/zigurous/forge-css@1.0.0/dist/index.min.css" rel="stylesheet">
```

#### statically

```html
<link href="https://cdn.statically.io/gh/zigurous/forge-css/1.0.0/dist/index.min.css" rel="stylesheet">
```
