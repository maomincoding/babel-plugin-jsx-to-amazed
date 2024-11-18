# Babel-plugin-jsx-to-mettle

This plugin converts JSX into Tagged Templates that work with mettle.js.

## Usage

In your Babel configuration (`.babelrc`, `babel.config.js`, `"babel"` field in package.json, etc), add the plugin:

```js
{
  "plugins": [
    ["babel-plugin-jsx-to-mettle"]
  ]
}
```

### options

#### `tag=html`

By default, `babel-plugin-jsx-to-mettle` will process all Tagged Templates with a tag function named `html`. To use a different name, use the `tag` option in your Babel configuration:

```js
{"plugins":[
  ["babel-plugin-jsx-to-mettle", {
    "tag": "html"
  }]
]}
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2023-present, maomincoding
