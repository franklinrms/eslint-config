# ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Simple import sort plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @franklinrms/eslint-config prettier-plugin-tailwindcss
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@franklinrms/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

Inside `package.json`
```
  "prettier": {
    "plugins": [
      "prettier-plugin-tailwindcss"
    ]
  }
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @franklinrms/eslint-config prettier-plugin-tailwindcss
```
Inside `.eslintrc.json`
```
{
  "extends": "@franklinrms/eslint-config/react"
}
```

Inside `package.json`
```
  "prettier": {
    "plugins": [
      "prettier-plugin-tailwindcss"
    ]
  }
```

### Node.js

Install dependencies:
```
npm i -D eslint @franklinrms/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@franklinrms/eslint-config/node"
}
```
