# @supple-kit/prettier-config

Default prettier config for Supple-kit projects

## Install

```bash
npm i -D @supple-kit/prettier-config
```

## Usage

In `package.json`:

```json
{
  "prettier": "@supple-kit/prettier-config"
}
```

In dedicated `prettier.config.js`:

```js
module.exports = {
  ...require("@supple-kit/prettier-config")
};
```

## License

MIT.
