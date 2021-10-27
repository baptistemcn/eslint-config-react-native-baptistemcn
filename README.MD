# eslint-config-react-native-baptistemcn

This is my ESLINT and Typescript configuration for React Native.

## Usage

```sh
# You will need to install eslint with this configuration.
yarn add -D eslint eslint-config-react-native-baptistemcn --dev
```

In `.eslintrc`:

```json
{
  "extends": "react-native-baptistemcn"
}
```

In `tsconfig.json` (if you want to use my base TS configuration):

```json
{
  "extends": "eslint-config-react-native-baptistemcn/tsconfig.base"
}
```
