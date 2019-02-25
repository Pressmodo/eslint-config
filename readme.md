Pressmodo ESLint Config
=====================

In order to improve both our efficiency and consistency, we need to standardize what we use and how we use it. This repository contains Pressmodo's standard configuration for [ESLint](http://eslint.org/).

## Installation

To use this config, install [@pressmodo/eslint-config](https://github.com/pressmodo/eslint-config) as a development dependecy of your project:

```sh
npm install @pressmodo/eslint-config --save-dev
```

Next, add this configuration to your `package.json`:

```json
{
    "eslintConfig": {
        "extends": "@pressmodo/eslint-config"
    }
}
```

Or add a .eslintrc file to your project root containing: 

```json
{
    "extends": "@pressmodo/eslint-config"
}
```