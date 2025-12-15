# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

Zenn（https://zenn.dev）に公開する技術記事・本を管理するリポジトリ。Zenn CLI を使用してローカルで記事を執筆し、GitHub 連携で公開する。

## コマンド

```bash
# 新しい記事を作成
bun run new:article

# 新しい本を作成
bun run new:book

# プレビューサーバーを起動（ブラウザで確認）
bun run preview

# Zenn CLI を最新版に更新
bun add zenn-cli@latest
```

## ディレクトリ構成

- `articles/` - 記事の Markdown ファイル（slug.md 形式）
- `books/` - 本のディレクトリ（本ごとにフォルダを作成）
- `images/` - 記事・本で使用する画像（`../images/記事slug/` で参照）

## 記事のフロントマター

```yaml
---
title: "記事タイトル"
emoji: "🎉"
type: "tech"  # tech または idea
topics: ["topic1", "topic2"]  # 最大5つ
published: false  # true で公開
---
```

## 執筆ルール

- 日本語とアルファベットの間には半角スペースを入れる
- 画像は `images/記事slug/` ディレクトリに配置し、`../images/記事slug/画像名.png` で参照
- Prettier でフォーマット（tabWidth: 2, semi: false, singleQuote: true）
