# Stratumn eslint-config

This is Stratumn's shareable eslint config. It works with the `extends` feature of `.eslintrc` files. You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

## Install

First install the package as a dev dependency:

```bash
yarn add -D @stratumn/eslint-config
```

Then add this to your .eslintrc file:

```json
{
  "extends": "@stratumn/eslint-config"
}
```

You can override settings from the shareable config by adding them directly into your `.eslintrc` file.
