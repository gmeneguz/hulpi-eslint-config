# Hulpi ESLint config
ESLint configuration based on Rocketseat
https://github.com/Rocketseat/eslint-config-rocketseat


## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint @hulpi/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@hulpi/eslint-config/react"
  // "extends": "@hulpi/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
