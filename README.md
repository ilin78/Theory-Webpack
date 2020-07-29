### Минимальная конфигурация к данному проекту

file: webpack.config.js
```js
const path = require('path')

module.exports = {
    mode: 'production', // development
    entry: './src/index.js',
    output: {
        filename: 'bundle.js',
        path: path.resolve(__dirname, 'dist')
    }
}
```