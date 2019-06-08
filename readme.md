## @pavanjadhaw/prettier-config

> My personal [Prettier](https://prettier.io) config.

## Usage

**Install**:

```bash
$ yarn add --dev @pavanjadhaw/prettier-config
```

Reference it in your package.json

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@pavanjadhaw/prettier-config"
}
```

If you don't want to use package.json, you can use any of the supported extensions to export config, e.g. `.prettierrc.js`:

This method also allows extending the configuration.

```js
module.exports = {
  ...require("@pavanjadhaw/prettier-config"),
  semi: false
};
```
