# Prettier config

[![npm version](https://badge.fury.io/js/prettier-config-twg.svg)](https://badge.fury.io/js/prettier-config-twg) ![NPM downloads](https://img.shields.io/npm/dm/prettier-config-twg) ![Code Style Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg) [![MIT License](https://img.shields.io/badge/license-MIT-red.svg?style=flat)](https://github.com/TheWidlarzGroup/prettier-config-twg/blob/master/LICENSE) [![Twitter Follow](https://img.shields.io/twitter/follow/WidlarzGroup?label=Follow%20on%20Twitter)](https://twitter.com/WidlarzGroup)

These are settings for Prettier.

## What it does

A shared Prettier config

## Installation

To install this package run the following command in the terminal in the root directory of your application.

```
npm install --save-dev @twgdev/prettier-config
```

**OR**

```
yarn add --dev @twgdev/prettier-config
```

## Usage

Add a key in your **package.json** file.

```
"prettier": "@twgdev/prettier-config"
```

**OR**

Create a **.prettierrc** , **.prettierrc.yaml** , **.prettierrc.yml** or **.prettierrc.json** file and export a string.

```
"@twgdev/prettier-config"
```

**OR**

Create a **prettier.config.js** or **.prettierrc.js** file and export an object.

```
module.exports = {
  ...require("@twgdev/prettier-config"),
  // endOfLine: 'lf', // to overwrite the property
};
```
