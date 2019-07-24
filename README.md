# 1.Introduction

## はじめに

このドキュメントは、初心者がNuxt.jsを用いて簡易なSingle Page Applicationを作れるようになるための資料です。

この資料で作成するアプリケーションの実際のソースコードは[GitHub](github.com/Umisyo/getting-started-with-nuxt)上で公開されています。

この資料は、フレームワークの全てを解説するものではありません。
Nuxt.jsについてのより詳細な情報は、[公式ドキュメント](ja.nuxtjs.org)を参照してください。

## Nuxt.jsとは？

> Nuxt.js は Vue アプリケーションを作成するフレームワークです。ユニバーサルアプリケーション、静的に生成されるアプリケーション、シングルページアプリケーションの中から作成するアプリケーションを選ぶことができます。

[公式ドキュメント](ja.nuxtjs.org/guide/) より

## 環境構築

***この資料では、主にMac OS もしくはそれに準ずるUnix互換環境での開発を前提としています。
Windowsやその他の環境での開発について解説するものではありませんのでご理解ください***

```bash
$brew install node
```

もしくは `nodenv` などの仮想環境で管理しても構いません。

```bash
$brew install yarn

or

$brew install npm
```

此処から先は原則として `yarn` を用いるものとして解説を進めていきますが、`npm` を使う場合は適宜置き換えて頂いて結構です。

```bash
$yarn global add nuxt
```

```bash
$create-nuxt-app getting-started-with-nuxt
```

そうすると幾つかの選択肢が表示されるので選択していきましょう。

今回はイカのように選択していきます。

```bash
? Project name getting-started-with-nuxt
? Project description 説明
? Use a custom server framework none
? Choose features to install PWA support Linter/Formatter Prettier
? Chose UI frame Vuetify
? Use a custom test framework none
? Choose rendering mode Single Page App
? Author name 開発者名
? Chose the package manager yarn
```

すると、以下のようなディレクトリが生成されます。

```bash
.
├── assets
├── components
├── layouts
├── middleware
├── node_modules
├── pages
├── plugins
├── static
└── store
```

次のページからは実際に開発を始めていきます。
