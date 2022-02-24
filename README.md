# dummy-counter 🚀

A simple React component that counts from 0 - 100 and then resets back to 0. This runs for infinity and yes, this is not meant to be functional in any way.

[![npm version](https://img.shields.io/npm/v/react-image-magnifiers.svg?style=flat)](https://npmjs.org/package/react-image-magnifiers "View this project on npm")
[![npm downloads](https://img.shields.io/npm/dm/react-image-magnifiers.svg?style=flat-square)](https://www.npmjs.com/package/react-image-magnifiers)
[![MIT license](https://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)
<a href="https://packagephobia.now.sh/result?p=rollup">
<img src="https://packagephobia.now.sh/badge?p=rollup" alt="install size" >
</a>

## How to use¯

Clone this repo to your local computer, then run:

```
npm install && npm run build
```

- To make this component available to other projects on your local computer, run

```
npm link
```

## Installation

```
npm install dummy-counter
```

## Usage

```
import Dummy, { ICounterProps } from 'dummy-counter'
...
```

## Available props

```

className: string (optional)

```

To customise this component, pass in a class name to the `className` prop and style that class name in your custom CSS.

```

// your-component.js
import Dummy from 'dummy-counter'

...
<Dummy className="dummy" />
...

// your-component.css
.dummy {
  color: white;
  background-color: purple;
}

```

**This component was built for an article on how to publish a React component as a package to npm.**
