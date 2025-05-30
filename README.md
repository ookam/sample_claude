# sample_claude

## 概要 / Overview

このリポジトリは、GitHub Issues と Pull Requests で Claude AI を活用するためのサンプルリポジトリです。`@claude` とメンションすることで、Claude が自動的にコードレビュー、実装支援、質問への回答などを行います。

This is a sample repository demonstrating how to integrate Claude AI as an automated assistant for GitHub Issues and Pull Requests. By mentioning `@claude`, Claude will automatically provide code reviews, implementation assistance, and answer questions.

## 機能 / Features

- 🤖 **自動コード支援** - Issue や PR で `@claude` をメンションすると、Claude が自動的に対応します
- 💬 **インタラクティブな対話** - コメントを通じて Claude と対話できます
- 🔧 **実装支援** - コードの実装や修正を依頼できます
- 📝 **コードレビュー** - PR のレビューを依頼できます
- ❓ **質問回答** - 技術的な質問に回答します

## 使い方 / Usage

### 基本的な使い方

1. Issue または Pull Request を作成します
2. コメントで `@claude` をメンションして、依頼内容を記載します
3. Claude が自動的に応答し、要求されたタスクを実行します

### 使用例

```
@claude このコードをレビューしてください
```

```
@claude README にインストール手順を追加してください
```

```
@claude このエラーの原因を教えてください
```

## セットアップ / Setup

このリポジトリでは、GitHub Actions を使用して Claude を統合しています。独自のリポジトリで Claude を使用するには：

1. [grll/claude-code-action](https://github.com/grll/claude-code-action) を参照
2. 必要な認証トークンを GitHub Secrets に設定：
   - `CLAUDE_ACCESS_TOKEN`
   - `CLAUDE_REFRESH_TOKEN`
   - `CLAUDE_EXPIRES_AT`
3. `.github/workflows/claude.yml` ファイルを作成

## 技術スタック / Tech Stack

- **GitHub Actions** - Claude の自動実行環境
- **Claude AI** - AI アシスタント
- **grll/claude-code-action@beta** - Claude を GitHub に統合するアクション

## ライセンス / License

このプロジェクトのライセンスについては、リポジトリ所有者にお問い合わせください。