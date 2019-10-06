# Utils

This is a simple npm package for my utilities, created to practice using the [GitHub Package Registry](https://github.com/features/package-registry).


## Installation

Before installing, make sure to authenticate with GitHub Package Registry or using a `.npmrc` file. See "[Configuring npm for use with GitHub Package Registry](https://help.github.com/en/articles/configuring-npm-for-use-with-github-package-registry#authenticating-to-github-package-registry)."

```sh
npm install @austintraver/utils
```

Or add this package to your `package.json` file:

```json
"dependencies": {
    "@austintraver/utils": "^1.0.0"
  }
```

## Usage

```js
const utils = require('@austintraver/utils');
utils.hello();
```

