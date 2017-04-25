EverFi Coding Standards
=======================

A collection of coding standards tools for EverFi.

## ESLint

### Installation
```
npm install --save-dev EverFi/code-standards
```

### Usage
Create `.eslintrc` and extend the EverFi standards
```
{
  "extends": "eslint-config-everfi-code-standards"
}
```
Add this to npm scripts in `package.json`
```
"js:lint": "node_modules/eslint-config-everfi-code-standards/node_modules/eslint-cli/bin/eslint.js ./**/*.js"
```

Run it like this:
```
npm run js:lint
```
