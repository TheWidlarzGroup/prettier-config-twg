# Prettier config

<!--
[![npm version](https://badge.fury.io/js/eslint-config-twg.svg)](https://badge.fury.io/js/eslint-config-twg) ![NPM downloads](https://img.shields.io/npm/dm/eslint-config-twg) [![GitHub issues](https://img.shields.io/github/issues/leonardofaria/eslint-config-twg)](https://github.com/leonardofaria/eslint-config-twg/issues) ![Code Style Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg) [![MIT License](https://img.shields.io/badge/license-MIT-red.svg?style=flat)](https://github.com/leonardofaria/twg-ui/blob/master/LICENSE) [![Twitter Follow](https://img.shields.io/twitter/follow/WidlarzGroup?label=Follow%20on%20Twitter)](https://twitter.com/WidlarzGroup) -->

These are settings for Prettier.

## What it does

A shared Prettier config

## Installation

To install this package run the following command in the terminal in the root directory of your application.

```
npm install --save-dev @twg/prettier-config
```

**OR**

```
yarn add --dev @twg/prettier-config
```

## Usage

Add a key in your **package.json** file.

```
"prettier": "@twg/prettier-config"
```

**OR**

Create a **.prettierrc** , **.prettierrc.yaml** , **.prettierrc.yml** or **.prettierrc.json** file and export a string.

```
"@twg/prettier-config"
```

**OR**

Create a **prettier.config.js** or **.prettierrc.js** file and export an object.

```
module.exports = {
  ...require("@twg/prettier-config"),
  // endOfLine: 'lf', // to overwrite the property
};
```
