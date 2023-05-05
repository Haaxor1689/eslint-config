Eslint config for React + Next + Tailwind projects. Also comes with a Prettier config.

## Usage

Install the package with its peer dependencies

```bash
npx install-peerdeps --dev @haaxor1689/eslint-config
```

Next add it under `eslintConfig` key to your `package.json` or add it to your existing eslint config. You can also add the prettier config as well.

```jsonc
// package.json
{
  // ...
  "eslintConfig": {
    "extends": "@haaxor1689/eslint-config"
  },
  "prettier": "@haaxor1689/prettier-config"
}
```
