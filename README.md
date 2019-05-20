# @swiftcarrot/react-markdown

[![npm](https://img.shields.io/npm/v/@swiftcarrot/react-markdown.svg)](https://www.npmjs.com/package/@swiftcarrot/react-markdown)
[![npm](https://img.shields.io/npm/dm/@swiftcarrot/react-markdown.svg)](https://www.npmjs.com/package/@swiftcarrot/react-markdown)
[![Build Status](https://travis-ci.org/swiftcarrot/react-markdown.svg?branch=master)](https://travis-ci.org/swiftcarrot/react-markdown)
[![codecov](https://codecov.io/gh/swiftcarrot/react-markdown/branch/master/graph/badge.svg)](https://codecov.io/gh/swiftcarrot/react-markdown)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

render markdown as react component

### Installation

```sh
yarn add @swiftcarrot/react-markdown
npm install @swiftcarrot/react-markdown --save
```

### Usage

```javascript
import React from 'react';
import Markdown from '@swiftcarrot/react-markdown';

const text = `
## testing
`;

const App = () => <Markdown>{text}</Markdown>;
```

### License

MIT
