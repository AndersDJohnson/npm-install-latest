# npm-install-latest

```js
Object.entries(require('./package.json').devDependencies)
  .filter(([v,k]) => v.match(/eslint/))
  .map(([v]) => `${v}@latest`)
  .join(' ')
```
