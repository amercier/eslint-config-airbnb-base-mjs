eslint-config-airbnb-base-mjs
=============================

> [eslint-config-airbnb-base](https://www.npmjs.com/package/eslint-config-airbnb-base)
> with `.mjs` extension replacing `.js`

[![Latest Stable Version](https://img.shields.io/npm/v/eslint-config-airbnb-base-mjs.svg)](https://www.npmjs.com/package/eslint-config-airbnb-base-mjs)
[![License](https://img.shields.io/npm/l/eslint-config-airbnb-base-mjs.svg)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/amercier/eslint-config-airbnb-base-mjs/master.svg)](https://travis-ci.org/amercier/eslint-config-airbnb-base-mjs)

Installation
------------

- Install `eslint-config-airbnb-base-mjs` and its peer dependencies:
```sh
# With npm 5+:
npx install-peerdeps --dev eslint-config-airbnb-base-mjs

# Or, with npm < 5:
# 1. Install peer dependencies listed by: npm info eslint-config-airbnb-base-mjs@latest peerDependencies
# 2. Install eslint-config-airbnb-base-mjs: npm install eslint-config-airbnb-base-mjs --save-dev
```
- Add to your `.eslintrc.json` (or [equivalent](https://eslint.org/docs/user-guide/configuring#configuration-file-formats)):
```json
{
  "extends": "eslint-config-airbnb-base-mjs"
}
```

Usage
-----

```sh
# With npm 5+ (otherwise run `./node_modules/.bin/eslint`)
npx eslint . --ext .mjs
```

License
-------

This project is released under [ISC License](LICENSE.md).
