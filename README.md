# W11K tslint-presets
This NPM package includes the [TSLint](https://palantir.github.io/tslint/) preset used at W11K

## Installation
Install the package as a npm dev dependency.
```bash
npm install -D @w11k/tslint-presets
```

## Usage
After adding the package to your project, create or update your `tslint.json` file:

### Angular
```json
{
  "extends": "@w11k/tslint-presets/angular.json",
  "rules": {}
}
```

### React
```json
{
  "extends": "@w11k/tslint-presets/react.json",
  "rules": {}
}
```

### Typescript
```json
{
  "extends": "@w11k/tslint-presets/typescript.recommended.json",
  "rules": {}
}
```
