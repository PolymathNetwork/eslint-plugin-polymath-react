# eslint-plugin-polymath-react

ESLint plugin for the Polymath related React projects.

## Usage

1. `npm install PolymathNetwork/eslint-plugin-polymath-react --save-dev`
2. Create a file named `.eslintrc` in your project:

```js
{
  extends: ['plugin:polymath-react/recommended']
}
```

3. Add to your `package.json`:

```js
"scripts": {
  ...
  "lint": "./node_modules/eslint/bin/eslint.js --ext .js,.jsx --fix src",
```

## Rules

### Extends

This package extends [eslint:recommended](http://eslint.org/docs/rules/), [plugin:react/recommended](https://github.com/yannickcr/eslint-plugin-react) and [plugin:polymath/recommended](https://github.com/ChronoBank/eslint-plugin-chronobank)

### Overrides

To check overrides see `config.js`.

## License

[GPL-3.0](https://opensource.org/licenses/GPL-3.0)
