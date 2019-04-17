# tslint-config-cognite-3d

This is the tslint configuration for Cognite 3D team projects. It uses [tslint-plugin-prettier](https://github.com/prettier/tslint-plugin-prettier) with [tslint-config-prettier](https://github.com/prettier/tslint-config-prettier) to apply code formatting style.

### Setup

Install lint config:

```sh
yarn add --dev @cognite/tslint-config-cognite-3d
```

Install peer dependencies:

```sh
yarn add --dev tslint prettier tslint-plugin-prettier tslint-config-prettier
```

Create a `tslint.json` file in the root of your project:

```json
{
  "extends": ["@cognite/tslint-config-cognite-3d"]
}
```
