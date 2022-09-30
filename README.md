Eslint config I use in my projects

## Usage

First install the package

```bash
yarn add --D @haaxor1689/eslint-config
```

Install peer dependencies

```bash
npx install-peerdeps --dev @haaxor1689/eslint-config
```

Next add it under `eslintConfig` key to your `package.json` or add it to your existing eslint config.

```jsonc
// package.json
{
  // ...
  "eslintConfig": {
    "extends": "@haaxor1689/eslint-config"
  }
}
```
