# web-ext-webpack-plugin
A webpack plugin for web-ext

## Install
```
npm install --save-dev @abdullah2993/web-ext-webpack-plugin
```

**webpack.config.js**
```js
const path = require('path');
const WebExtWebpackPlugin = require('@abdullah2993/web-ext-webpack-plugin');

module.exports = {
  plugins: [
    new WebExtWebpackPlugin({ sourceDir: path.resolve(__dirname, 'extension') })
  ]
}
```
