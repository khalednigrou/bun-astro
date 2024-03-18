# Astro & Bun

Bunとサーバーサイドレンダリングを組み合わせたAstroプロジェクトの簡易テンプレート。

[Read in English](./README.md) | [Lire en Français](./README_fr.md)

## インストール

依存関係をインストールします。

```sh
bun install
```

## 開発

開発サーバーを起動します。

```sh
bun run dev
```

http://localhost:4321 にアクセスしてください。

## ビルド

プロジェクトをビルドします。

```sh
bun run build
```

ビルドしたプロジェクトを実行します。

```sh
bun ./dist/server/entry.mjs
```

http://localhost:4321 にアクセスしてください。 (または http://127.0.0.1:4321)