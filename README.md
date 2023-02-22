# This package contains the global NordLB ESLint Base Config

## How to use it

### Installation

```bash
# npm
npm install --dev @nordlb-ui/eslint-config-base

# yarn
yarn add -D @nordlb-ui/eslint-config-base
```

### Implementation

`.eslintrc.js`

```js
module.exports = {
  extends: ['@nordlb-ui/eslint-config-base']
}
```

## What you get

### Extended Configs and Plugins

- [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base)
- [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)
- [typescript-eslint/recommended](https://github.com/typescript-eslint/typescript-eslint#readme)

### Custom Parsers

- [typescript-eslint/parser](https://github.com/typescript-eslint/typescript-eslint#readme)

### Plugins

- [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)
- [eslint-plugin-simple-import-sort](github.com/lydell/eslint-plugin-simple-import-sort#readme)
- [@typescript-eslint/eslint-plugin](https://github.com/typescript-eslint/typescript-eslint#readme)

### Custom Rules

| Rule Name                               | Description                                                                          | Configuration | Documentation                                                                                                                                                          |
| :-------------------------------------- | :----------------------------------------------------------------------------------- | :------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| @typescript-eslint/no-use-before-define | Warns when it encounters a reference to an identifier that has not yet been declared | Errors.       | [typescript-eslint/no-use-before-define](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/no-use-before-define.md) |

## Overrides

### Files matching `**/*.test.*`

### Additional Extends

- [jest-dom/recommended](https://github.com/testing-library/jest-dom)
- [testing-library/dom](https://github.com/testing-library/eslint-plugin-testing-library)

### Additional Plugins

- [jest-dom](https://github.com/testing-library/jest-dom)
- [testing-library](https://github.com/testing-library/eslint-plugin-testing-library)

### Rules

| Rule Name | Description | Configuration | Documentation |
| :-------- | :---------- | :------------ | :------------ |
