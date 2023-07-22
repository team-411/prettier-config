# `@team-411/prettier-config`
`prettier`用の設定置き場

## インストール
```sh
# npm / yarn
$ npm install -D https://github.com/team-411/prettier-config.git

# pnpm
$ pnpm add -D github:team-411/prettier-config
```

## 設定
```js
// .prettierrc.mjs
export { default } from "@team-411/prettier-config";
```

> **Warning**
> 2023/07/22現在、`prettier@3.0.0`ではESMの読み込みができないので代わりに以下の設定を用いるか、`prettier@2.8.8`を使う。

```js
// .prettierrc.cjs
module.exports = require("@team-411/prettier-config");
```
