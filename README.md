# react-scrollmagic

> React declarative component for ScrollMagic

[![NPM](https://img.shields.io/npm/v/react-scrollmagic.svg)](https://www.npmjs.com/package/react-scrollmagic) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-scrollmagic
```

## Usage

```jsx
import React from 'react';
import { SMController, SMScene } from 'react-scrollmagic';

const Sticky = () => (
  <div>
    <SMController>
      <SMScene duration={600} pin={true}>
        <div>Sticky Example</div>
      </SMScene>
    </SMController>
  </div>
);
```

Examples live demo:

https://bitworking.github.io/react-scrollmagic/

Examples source:

https://github.com/bitworking/react-scrollmagic/tree/master/example/src/components/ScrollMagicExamples

This project was bootstrapped with:

https://github.com/transitive-bullshit/create-react-library

## License

MIT © [bitworking](https://github.com/bitworking)
