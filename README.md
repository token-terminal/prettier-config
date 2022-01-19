# prettier-config

Our prettier config. Use it with our eslint config.

## Usage

Add the following to your `package.json`:

```
"prettier": "@token-terminal/prettier-config",
"eslintConfig": {
  "extends": "@token-terminal/eslint-config"
},
"devDependencies": {
  "@token-terminal/eslint-config": "https://github.com/token-terminal/eslint-config",
  "@token-terminal/prettier-config": "https://github.com/token-terminal/prettier-config"
}
```

Install the dependencies:

```
yarn install
```
