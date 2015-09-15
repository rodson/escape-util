# escape-util
A small library providing utility methods to escape and unescape HTML entities

## Installation

```
npm install escape-util --save
```

## Usage

```
var escapeUtil = require('escape-util'),
  escaped = escapeUtil.escape,
  unescape = escapeUtil.unescape;

var html = '<h1>Hello World</h1>',
  escaped = escape(html),
  unescaped = unescape(escaped);

console.log('html', html, 'escaped', escaped, 'unescaped', unescape);
```

## Tests
```
npm test
```

## Release History

*   0.0.1 initial release