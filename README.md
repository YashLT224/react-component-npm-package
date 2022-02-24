# dummy-counter 🚀

A simple React component that counts from 0 - 100 and then resets back to 0. This runs for infinity and yes, this is not meant to be functional in any way.

[![Build Status](https://semaphoreci.com/api/v1/nimjetushar/utils/branches/master/shields_badge.svg)](https://semaphoreci.com/nimjetushar/utils)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/86a61b646ab041c0b64e502b3d8be7a7)](https://www.codacy.com/app/tushar/Utils?utm_source=github.com&utm_medium=referral&utm_content=nimjetushar/Utils&utm_campaign=Badge_Grade)
[![npm version](https://img.shields.io/npm/v/react-image-magnifiers.svg?style=flat)](https://www.npmjs.com/package/@vyash5075/react-demo-module "View this project on npm")
[![npm downloads](https://img.shields.io/npm/dm/react-image-magnifiers.svg?style=flat-square)](https://www.npmjs.com/package/@vyash5075/react-demo-module)
<a href="https://packagephobia.now.sh/result?p=rollup">
<img src="https://packagephobia.now.sh/badge?p=rollup" alt="install size" >
</a>

## How to use

Clone this repo to your local computer, then run:

```
npm install && npm run build
```

- To make this component available to other projects on your local computer, run

```
npm link
```

## Quickstart

```
npx create-react-app my-app
cd my-app
npm install '@vyash5075/react-demo-module'
npm start
```

## Installation

```
npm install '@vyash5075/react-demo-module'
```

## Usage

```
import Dummy, { ICounterProps } from '@vyash5075/react-demo-module'
...
```

## Available props

```

className: string (optional)

```

To customise this component, pass in a class name to the `className` prop and style that class name in your custom CSS.

```

// your-component.js
import Dummy from '@vyash5075/react-demo-module'

...
<Dummy className="dummy" />
...

// your-component.css
.dummy {
  color: white;
  background-color: purple;
}

```

## Contributors ⚡

<table>
  <tr>
    <td align="center"><a href="https://github.com/vyash5075"><img src="https://avatars.githubusercontent.com/u/44260505?v=4" width="114px;" alt=""/><br /><sub><b>Yash Verma</b></sub></a><br /><a href="https://github.com/vyash5075" title="Github"> 👨‍💻 </a></td>
  </tr>
</table>

## License

[![GitHub license](https://img.shields.io/github/license/nimjetushar/Utils.svg?style=popout)](https://github.com/nimjetushar/Utils/blob/master/LICENSE)
Copyright © 2022 vyash5075

**This component was built for an article on how to publish a React component as a package to npm.**
