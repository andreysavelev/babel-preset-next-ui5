# babel-preset-next-ui5
An UNSTABLE UNOFFICIAL preset for building SAP UI5 application with Babel.

## Install

```sh
$ npm install --save-dev babel-preset-next-ui5
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["next-ui5"]
}
```

### Via CLI

```sh
$ babel script.js --presets next-ui5
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["next-ui5"]
});
```
