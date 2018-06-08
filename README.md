# cjt
[![Build Status](https://travis-ci.org/announce/cjt.svg?branch=master)](https://travis-ci.org/announce/cjt)

A library to convert CSV text to Jira's table notation


## Usage

```js
const cjt = require('cjt')
csv = `
  heading 1,heading 2,heading 3
  col A1,col A2,col A3
  col B1,col B2,col B3
`
console.log(cjt.convert(csv))
```

Output:

```txt
||heading 1||heading 2||heading 3||
|col A1|col A2|col A3|
|col B1|col B2|col B3|
```

## Installation

[cjt \- Chrome Web Store](https://chrome.google.com/webstore/detail/pagmnllnggjajagmlelanjlbompjelmd/publish-accepted)

```
npm install --save-dev cjt
```

## Reference

- [Jira's table notation](https://jira.atlassian.com/secure/WikiRendererHelpAction.jspa?section=tables)


## Development

https://chrome.google.com/webstore/developer/dashboard
