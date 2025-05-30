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

## ファイル構造 / File Structure

```
sample_claude/
├── README.md                          # プロジェクトの概要とドキュメント / Project overview and documentation
└── .github/
    └── workflows/
        └── claude.yml                 # Claude統合用のGitHub Actionsワークフロー / GitHub Actions workflow for Claude integration
```

### ファイルの詳細 / File Details

#### `README.md`
- **説明**: プロジェクトの概要、使用方法、セットアップ手順などを記載したメインドキュメント
- **Description**: Main documentation containing project overview, usage instructions, and setup procedures
- **内容 / Contents**:
  - プロジェクトの概要と機能
  - 使い方とセットアップ手順
  - セキュリティ情報
  - Project overview and features
  - Usage and setup instructions
  - Security information

#### `.github/workflows/claude.yml`
- **説明**: GitHub Actions上でClaude AIを動作させるためのワークフロー定義ファイル
- **Description**: Workflow definition file for running Claude AI on GitHub Actions
- **主な機能 / Main Features**:
  - イシューやプルリクエストでの `@claude` メンションを検知
  - Claude Code Actionを実行して自動応答
  - 60分のタイムアウト設定
  - Detects `@claude` mentions in issues and pull requests
  - Executes Claude Code Action for automatic responses
  - 60-minute timeout configuration
- **トリガー / Triggers**:
  - `issue_comment`: イシューへのコメント時
  - `pull_request_review_comment`: PRレビューコメント時
  - `issues`: イシューの作成・アサイン時
  - `pull_request_review`: PRレビューの提出時

## セキュリティ / Security

### セキュリティステータス / Security Status

✅ **セキュリティチェック完了** - このリポジトリ内のすべてのファイルをチェックし、セキュリティ上の問題は検出されませんでした。

✅ **Security Check Complete** - All files in this repository have been checked and no security issues were detected.

### 詳細 / Details

- **実行可能ファイル**: なし / None
- **機密情報**: 検出されず / Not detected
- **外部依存関係**: なし / None
- **セキュリティリスク**: 低 / Low

このリポジトリはドキュメンテーションのみを含むサンプルプロジェクトであり、実行可能なコードや機密情報は含まれていません。

This repository is a sample project containing only documentation and does not include any executable code or sensitive information.

## ライセンス / License

このプロジェクトのライセンスは未定義です。詳細はリポジトリオーナーにお問い合わせください。

The license for this project is not yet defined. Please contact the repository owner for details.