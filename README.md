# stylelint configuration

![Build](https://github.com/electerious/stylelint-config/workflows/Build/badge.svg)

Shareable stylelint configuration for my personal projects.

## Install

Install this package, stylelint and the necessary plugins.

```
npm install --save-dev @electerious/stylelint-config stylelint
```

## Usage

Create a file named `.stylelintrc.json` with following contents in the root folder of your project:

```json
{
  "extends": "@electerious/stylelint-config"
}
```

That's it! You can override the settings by editing the `.stylelintrc.json` file.