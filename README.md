# Testlio ESLint Configuration

This repository contains a shareable ESLint configuration that should be used with Node.js services written at Testlio. The package can be installed simply by running:

```
npm install --save-dev @testlio/eslint-config-services
```

The configuration can then be used by using the `extends` key in your `.eslintrc`:

```
{
    "extends": "@testlio/eslint-config-services"
}
```

All rules are listed in [index.js](./index.js) and are fairly self-evident, especially when compared to the [full list of available rules](http://eslint.org/docs/rules/).
