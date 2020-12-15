# @unfoldingword/eslint-config

> Eslint Configuration for unfoldingWord apps.

## Install

Using npm:

```sh
npm install @unfoldingword/eslint-config --save-dev
```

or using yarn:

```sh
yarn add @unfoldingword/eslint-config --dev
```

## Basic Setup For React Projects

add to eslint config:

```js
...
  "extends": [
    ...
    "@unfoldingword"
  ],
  ...
```

## Non React Project Setup

add to eslint config:

```js
...
  "extends": [
    ...
    '@unfoldingword/eslint-config/common',
  ],
  ...
```
