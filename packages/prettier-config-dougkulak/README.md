# eslint-config-dougkulak
[![Build Status](https://travis-ci.com/dougkulak/dougkulak-lint-config.svg?branch=master)](https://travis-ci.com/dougkulak/dougkulak-lint-config)
[![npm (tag)](https://img.shields.io/npm/v/prettier-config-dougkulak/latest.svg)](https://www.npmjs.com/package/prettier-config-dougkulak)
[![dependencyStatus](https://img.shields.io/david/dougkulak/dougkulak-lint-config.svg?maxAge=300)](https://david-dm.org/dougkulak/dougkulak-lint-config)
[![Test Coverage](https://api.codeclimate.com/v1/badges/8738098b0f0f4825da8b/test_coverage)](https://codeclimate.com/github/dougkulak/dougkulak-lint-config/test_coverage)
[![Maintainability](https://api.codeclimate.com/v1/badges/8738098b0f0f4825da8b/maintainability)](https://codeclimate.com/github/dougkulak/dougkulak-lint-config/maintainability)

[Prettier](https://prettier.io/) rules dougkulak prefers.

## Install
```bash
npm add prettier-config-dougkulak -D
yarn add prettier-config-dougkulak -D
```

## Usage
Add in your `package.json`:
```json
{
   ...
   "prettier": "prettier-config-dougkulak"
}
``` 
If you want overwrite some properties, you need import the file in a .prettierrc.js file and export the modifications: 
```javascript
module.exports = {
  ...require("prettier-config-dougkulak"),
  semi: false,
};
```

If you want to use prettier with eslint, add in your .eslintrc.js: 
```javascript
  extends: [
    // ...
    'prettier',
    'prettier/@typescript-eslint',
  ],
```

[Run](https://prettier.io/docs/en/cli.html) format your code:
```bash
prettier --write \"src/**/*.ts\""
```

## Contribution
If you find this config not strong enough you may add additional rules, write some tests, and trigger assets generation.
```bash
yarn test
```
