# escape-util
A small library providing utility methods to escape and unescape HTML entities

## Installation

```
npm install escape-util --save
```

## Usage

```js
var escapeUtil = require('escape-util'),
  escape = escapeUtil.escape,
  unescape = escapeUtil.unescape;

var html = '<h1>Hello World</h1>',
  escaped = escape(html),
  unescaped = unescape(escaped);

console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);
```

## Tests
```
npm test
```

## Release History

*   0.0.1 initial release
