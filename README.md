# Redux Toolkit example

This example shows how to integrate Next.js with [Redux Toolkit](https://redux-toolkit.js.org).

The **Redux Toolkit** is intended to be the standard way to write Redux logic (create actions and reducers, setup the store with some default middlewares like redux devtools extension). This example demonstrates each of these features with Next.js

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-redux-toolkit&project-name=with-redux-toolkit&repository-name=with-redux-toolkit)

## How to use

### インストール

#### テンプレートからインストール

`yarn create next-app --example with-redux-toolkit . `

next.config.js 作成

#### typescript

```
yarn add --dev typescript @types/react @types/node
touch tsconfig.json
yarn dev
```

#### ESLint

```
yarn add -D eslint eslint-config-next eslint-config-prettier prettier
yarn add -D @typescript-eslint/parser @typescript-eslint/eslint-plugin
```

.eslintrc.js、.eslintignore 作成
package.json に lint コマンド追加

#### tailwind.css

```
yarn add -D tailwindcss@latest postcss@latest autoprefixer@latest
npx tailwindcss init -p
```

tailwind.config.js 編集
