# eslint-config-dougkulak
[![Build Status](https://travis-ci.com/dougkulak/dougkulak-lint-config.svg?branch=master)](https://travis-ci.com/dougkulak/dougkulak-lint-config)
[![npm (tag)](https://img.shields.io/npm/v/eslint-config-dougkulak/latest.svg)](https://www.npmjs.com/package/eslint-config-dougkulak)
[![dependencyStatus](https://img.shields.io/david/dougkulak/dougkulak-lint-config.svg?maxAge=300)](https://david-dm.org/dougkulak/dougkulak-lint-config)
[![Test Coverage](https://api.codeclimate.com/v1/badges/8738098b0f0f4825da8b/test_coverage)](https://codeclimate.com/github/dougkulak/dougkulak-lint-config/test_coverage)
[![Maintainability](https://api.codeclimate.com/v1/badges/8738098b0f0f4825da8b/maintainability)](https://codeclimate.com/github/dougkulak/dougkulak-lint-config/maintainability)

[ESLint](https://eslint.org) rules dougkulak prefers.

## Install
```bash
npm add eslint-config-dougkulak -D
yarn add eslint-config-dougkulak -D
```

## Usage
Refer to `eslint-config-dougkulak` in your [.eslintrc.json](https://eslint.org/docs/user-guide/configuring):
```json
{
  "extends": "eslint-config-dougkulak"
}
```
[Run](https://eslint.org/docs/user-guide/command-line-interface) linting your TS code:
```bash
eslint -c /any/path/to/.eslintrc.json --fix
```

## Contribution
If you find this config not strong enough you may add additional rules, write some tests, and trigger assets generation.
```bash
yarn test:gen
```
