# open-browser-plugin
A webpack plugin to solve the problem that webpack-dev-server can not automatically open the browser via node api

## How to use

```js
npm i --save-dev open-browser-plugin
```

```js
// webpack.config.js
const OpenBrowserPlugin = reuire('open-browser-plugin')

const config = {
  plugins: [
    new OpenBrowserPlugin({
      port: 8080
    })
  ]
}
```


## options
### port

default `8080`

### host

default `localhost`

### protocol

default `http:`

