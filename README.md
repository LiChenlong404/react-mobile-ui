# React-mobile-ui

Web mobile components with react

## Doc

Please read the [documentation](https://shengkevin.github.io/react-mobile-ui/docs/index.html)

## Demo

Please look at the [demo](https://shengkevin.github.io/react-mobile-ui/example/index.html)

## Installing

npm install react-mobile-ui --save-dev

## Use example

```javascript
// app.js

import React from 'react';
import ReactDOM from 'react-dom';
import { Button } from 'react-mobile-ui';

const App = () => <Button>hello react-mobile-ui</Button>;

ReactDOM.render((
    <App/>
), document.getElementById('container'));

```

## Bug

Please commit [issues](https://github.com/shengKevin/react-mobile-ui/issues)

## Development

```js

  git clone https://github.com/shengKevin/react-mobile-ui.git
  cd react-mobile-ui && npm i
  // docs
    npm run build:lib

    npm run doc 
    
  // example 
    npm run build:lib

    npm start

  // lib
    npm run build:lib

```

### docs

```js
start: npm run doc

build: npm run build:doc
```
### example 

```js
start: npm start

build: npm run build 
```
### lib

```js
npm run build:lib
```
## Dir

```

├── build
│   ├── dist
│   ├── docs
│   ├── example
│   └── lib
├── docs
│   ├── app.js
│   ├── app.less
│   ├── docs.md
│   ├── index.html
│   └── index.js
├── example
│   ├── app.js
│   ├── app.less
│   ├── example.md
│   ├── index.html
│   └── index.js
├── src
│   ├── components
│   ├── index.js
│   ├── utils
│   └── version.js
├── webpack.config.js       // docs and exmple
└── webpack.config.lib.js   // build lib


```

