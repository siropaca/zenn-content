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

## Zenn 記事の執筆スタイル

記事を書く・編集する際は、以下のスタイルに従うこと。

### 構成

- frontmatter は Zenn の形式（title, emoji, type, topics, published）を使用する
- 記事の冒頭に「はじめに」セクションを設け、背景・動機・課題を個人的なストーリーとして導入する
- 本文はテーマごとにセクションを分け、具体的な内容を掘り下げる
- 記事末尾に「おわりに」または「まとめ」セクションを設け、振り返りや今後の展望を記載する
- 「参考」セクションを設け、参考 URL をリストでまとめる

### 文体

- 本文は「ですます調」で統一する
- 硬くなりすぎず、読者に語りかけるような親しみやすいトーンにする

### フォーマット

- 英語（アルファベット）と日本語の間には半角スペースを入れる
- 技術用語・コード・コマンドはバッククォート（`` ` ``）で囲む
- 箇条書きリストを活用して情報を整理する
- テーブル（表）を使って構造的な情報を見やすくまとめる
- Zenn 独自記法（`:::details` など）を活用する
- 外部リンクは URL を裸で貼り、Zenn のリンクカード展開を活用する
- 見出しは `##` を大見出し、`###` を小見出し、`####` をさらに細かい見出しとして使う（`#` は使用しない）

### その他

- 最後の締めは軽いトーンで終える（感想や一言コメントなど）
