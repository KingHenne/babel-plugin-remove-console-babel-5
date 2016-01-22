# babel-plugin-remove-console-babel-5

Babel 5 plugin to remove console.* calls

> This preservses the npm package [babel-plugin-remove-console](https://www.npmjs.com/package/babel-plugin-remove-console) for Babel 5 users.
> Former source location: [https://github.com/babel-plugins/babel-plugin-remove-console]()

## Installation

```sh
$ npm install babel-plugin-remove-console-babel-5
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["remove-console-babel-5"]
}
```

### Via CLI

```sh
$ babel --plugins remove-console-babel-5 script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["remove-console-babel-5"]
});
```
