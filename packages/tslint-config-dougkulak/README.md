# tslint-config-dougkulak
[![Build Status](https://travis-ci.com/dougkulak/dougkulak-lint-config.svg?branch=master)](https://travis-ci.com/dougkulak/dougkulak-lint-config)
[![npm (tag)](https://img.shields.io/npm/v/tslint-config-dougkulak/latest.svg)](https://www.npmjs.com/package/tslint-config-dougkulak)
[![dependencyStatus](https://img.shields.io/david/dougkulak/dougkulak-lint-config.svg?maxAge=300)](https://david-dm.org/dougkulak/dougkulak-lint-config)
[![Test Coverage](https://api.codeclimate.com/v1/badges/8738098b0f0f4825da8b/test_coverage)](https://codeclimate.com/github/dougkulak/dougkulak-lint-config/test_coverage)
[![Maintainability](https://api.codeclimate.com/v1/badges/8738098b0f0f4825da8b/maintainability)](https://codeclimate.com/github/dougkulak/dougkulak-lint-config/maintainability)

[TSLint](https://github.com/palantir/tslint/) rules dougkulak prefers. Based on [tslint-config-standard](https://github.com/blakeembrey/tslint-config-standard) and [tslint-react](https://github.com/palantir/tslint-react).

:warning: __TSLint will be deprecated some time in 2019__. See this issue for more details: [Roadmap: TSLint &rarr; ESLint](https://github.com/palantir/tslint/issues/4534).  
Use [eslint-config-dougkulak](../eslint-config-dougkulak/README.md) instead.

## Install
```bash
npm add tslint-config-dougkulak -D
yarn add tslint-config-dougkulak -D
```

## Usage
Refer to `tslint-config-dougkulak` in your [tslint.json](https://palantir.github.io/tslint/usage/configuration/):
```json
{
  "extends": "tslint-config-dougkulak"
}
```
[Run](https://palantir.github.io/tslint/usage/cli/) linting your TS code:
```bash
tslint -p tsconfig.json -c tslint.json --fix
```

## Contribution
If you find this config not strong enough you may add additional rules, write some tests, and trigger assets generation.
```bash
yarn test:gen
```
