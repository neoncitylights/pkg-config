# eslint-config-neoncitylights

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/v/eslint-config-neoncitylights?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/eslint-config-neoncitylights)

My personal ESLint configuration settings.

## Install

```shell
npm install eslint eslint-config-neoncitylights --save-dev
```

Or, if ESLint is already installed:

```shell
npm install eslint-config-neoncitylights --save-dev
```

## Usage

### TypeScript

Useful for developing pure TypeScript libraries, or using TypeScript within your application.

```js
{
    "extends": [
        "neoncitylights/typescript"
    ]
}
```

### Testing (unit, integration)

This includes settings for Vitest, React Testing Library, and Playwright.

```js
{
    "extends": [
        "neoncitylights/tests"
    ]
}
```

## License

This repository, including all packages within, is licensed under the MIT license ([`LICENSE-MIT`](../../LICENSE) or <http://opensource.org/licenses/MIT>).

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the MIT license, shall be licensed as above, without any additional terms or conditions.
