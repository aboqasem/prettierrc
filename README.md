# My Personal Prettier Configurations

```json
{
  "tabWidth": 2,
  "useTabs": false,
  "singleQuote": true,
  "semi": true,
  "trailingComma": "all",
  "arrowParens": "always",
  "bracketSpacing": true,
  "jsxSingleQuote": false,
  "printWidth": 100,
  "quoteProps": "as-needed",
  "endOfLine": "lf"
}
```

## Install

```shell
npm i -D @aboqasem/prettierrc
yarn add -D @aboqasem/prettierrc
pnpm add -D @aboqasem/prettierrc
```

## Use

```jsonc
// .prettierrc
"@aboqasem/prettierrc"
```

## Override

```javascript
/** @type {import('prettier').ParserOptions} */
module.exports = {
  ...require('@aboqasem/prettierrc'),
  printWidth: 100,
};
```
