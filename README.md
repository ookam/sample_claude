# sample_claude

## 概要 / Overview

このリポジトリは、GitHub上でClaudeを活用してイシューやプルリクエストの自動処理を行うサンプルプロジェクトです。

This repository is a sample project that demonstrates how to leverage Claude for automatic processing of issues and pull requests on GitHub.

## 機能 / Features

- 🤖 GitHub Actionsを使用したClaude統合
- 📝 イシューとプルリクエストへの自動応答
- 🔧 コードレビューと実装支援
- 🌐 多言語対応（日本語・英語）

- 🤖 Claude integration using GitHub Actions
- 📝 Automatic responses to issues and pull requests
- 🔧 Code review and implementation assistance
- 🌐 Multi-language support (Japanese/English)

## 使い方 / Usage

### 基本的な使用方法 / Basic Usage

1. イシューまたはプルリクエストで `@claude` をメンションする
2. Claudeが自動的に応答し、要求されたタスクを実行する

1. Mention `@claude` in an issue or pull request
2. Claude will automatically respond and execute the requested task

### 使用例 / Examples

```
@claude このコードをレビューしてください
@claude READMEを更新してください
@claude このバグを修正してください
```

```
@claude please review this code
@claude update the README
@claude fix this bug
```

## セットアップ / Setup

### 必要なもの / Requirements

- GitHub Actions の有効化
- Claude アプリケーションのインストール
- リポジトリへの書き込み権限

- GitHub Actions enabled
- Claude application installed
- Write permissions to the repository

### インストール手順 / Installation Steps

1. [Claude GitHub App](https://github.com/apps/claude) をリポジトリにインストール
2. `.github/workflows/claude.yml` ファイルが自動的に作成される
3. イシューやプルリクエストで `@claude` をメンションして使用開始

1. Install the [Claude GitHub App](https://github.com/apps/claude) to your repository
2. The `.github/workflows/claude.yml` file will be created automatically
3. Start using by mentioning `@claude` in issues or pull requests

## 技術スタック / Tech Stack

- GitHub Actions
- Claude AI
- YAML configuration

## ライセンス / License

このプロジェクトのライセンスは未定義です。詳細はリポジトリオーナーにお問い合わせください。

The license for this project is not yet defined. Please contact the repository owner for details.