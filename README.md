# PowerPoint Automation Bot

Microsoft Teams上で動作するチャットボットを通じて、PowerPointスライドの編集やThink-Cellチャートの作成・更新を自動化するシステムです。

## 機能概要

- Microsoft Teams上でのチャットによるPowerPoint操作
- 自然言語によるスライド編集指示
- PowerPointの基本操作（スライド追加、レイアウト変更、テキスト挿入等）
- Think-Cellチャートの作成・更新
- 企業固有のブランドガイドラインに沿ったカスタマイズ

## 技術スタック

- Node.js
- Microsoft Bot Framework SDK
- Azure Bot Service
- Azure AI Services
- Microsoft Graph API

## 必要条件

- Node.js LTS バージョン
- Microsoft Azure アカウント
- Microsoft 365 開発者アカウント

## セットアップ

1. 必要なパッケージのインストール
```bash
npm install
```

2. 環境変数の設定
```bash
cp .env.example .env
# .envファイルに必要な認証情報を設定
```

## 開発環境

- Bot Framework Emulator
- Visual Studio Code または Cursor
- Git

## ライセンス

このプロジェクトは [ライセンス名] の下で公開されています。

## 作成者

株式会社リアルバリュー
