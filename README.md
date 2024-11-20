# Forge CSS

<a href="https://github.com/zigurous/forge-css/actions"><img alt="GitHub Actions Workflow Status" src="https://img.shields.io/github/actions/workflow/status/zigurous/forge-css/publish-release.yml" /></a>
<a href="https://github.com/zigurous/forge-css/pkgs/npm/forge-css"><img alt="GitHub package.json version" src="https://img.shields.io/github/package-json/v/zigurous/forge-css" /></a>
<a href="https://github.com/zigurous/forge-css/blob/main/LICENSE"><img alt="GitHub License" src="https://img.shields.io/github/license/zigurous/forge-css" /></a>

The official CSS implementation of the Forge design system created by [@zigurous](https://github.com/zigurous).

## Installation

### CDN

Available from any of the following:
- Install with CloudFront `https://cdn.zigurous.com/forge-css@1.0.0/dist/index.min.css`
- Install with jsDelivr `https://cdn.jsdelivr.net/gh/zigurous/forge-css@1.0.0/dist/index.min.css`
- Install with Statically `https://cdn.statically.io/gh/zigurous/forge-css/1.0.0/dist/index.min.css`

Link to the stylesheet in your HTML file:
```html
<link href="https://cdn.zigurous.com/forge-css@1.0.0/dist/index.min.css" rel="stylesheet">
```

### GitHub Packages

Generate a [personal access token](https://github.com/settings/tokens) in your GitHub account with the `read:packages` scope. GitHub requires an auth token to download packages even if they are public.

Add an `.npmrc` file in the same directory as your `package.json` with the lines below. Replace `${NPM_TOKEN}` with the token you generated in the previous step.
```
registry=https://registry.npmjs.org/
@zigurous:registry=https://npm.pkg.github.com
//npm.pkg.github.com/:_authToken=${NPM_TOKEN}
```

Install the package using your preferred package manager:
- Install with npm `npm install @zigurous/forge-css`
- Install with yarn `yarn add @zigurous/forge-css`
- Install with pnpm `pnpm add @zigurous/forge-css`


Import the css file in your code:
```js
import '@zigurous/forge-css/dist/index.min.css'
```
