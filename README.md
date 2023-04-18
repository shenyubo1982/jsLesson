# 🚀 Welcome to your new awesome project!

it's a demo with metamark connect to my webSite

## directory with project

```
jsLesson/
├─ src/
│  ├─ index.js
├─ dist/
│  ├─ index.html
```

## Compile the module

```
Install the webpack
npm i --save-dev webpack

Install the Webpack CLI:
npm i --save-dev webpack-cli

Compile the module:
npx webpack

```

please add config for addawait config,sush as:

```
webpack.config.cjs
module.exports = {
    experiments: {
        topLevelAwait: true,
    },
};
```
