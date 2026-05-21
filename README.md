# SpecBridge

> AIに作らせる前に、AIに伝わる仕様書を。

非エンジニアとAIアプリビルダーをつなぐ橋渡しツール。  
5つの質問に答えるだけで、BASE44 / Bolt / Lovable / Cursor に貼れる設計書を生成します。

## 概要

「AIにアプリを作ってもらいたいけど、何を伝えればいいか分からない」

そんな非エンジニアのための前工程ツール。  
ゴール・ユーザー・機能・管理者要件・制約を整理し、抜け漏れのない仕様書とすぐ使えるプロンプトを出力します。

## 機能

- 5問の質問フローで要件を整理
- アプリ概要・想定ユーザー・主要画面・抜け漏れチェックを自動生成
- AIアプリビルダーに貼り付けられるプロンプトを出力
- Ctrl+Enter で素早く回答を送信
- APIなしでもフォールバックで動作

## 技術スタック

- フロントエンド：HTML / CSS / JavaScript（ビルド不要）
- バックエンド：Cloudflare Pages Functions
- AI：Claude API（Anthropic claude-sonnet-4-6）

## セットアップ（Cloudflare Pages）

1. このリポジトリをCloudflare Pagesに接続
2. Build command：なし（空欄）
3. Build output directory：`/`
4. 環境変数に `ANTHROPIC_API_KEY` を設定

```text
ANTHROPIC_API_KEY=sk-ant-xxxxxxxx
```

任意（デフォルト：claude-sonnet-4-6）：

```text
ANTHROPIC_MODEL=claude-sonnet-4-6
```

## 広告枠

EthicalAds（プライバシー配慮型）の承認後に差し替え予定。  
現在はプレースホルダーを表示中。

---

## 活動ログ

### 2026-05-18
- SpecBridge α版を公開
- RequiFlow（要件定義ツール）からリブランド
- 訴求を「AIアプリビルダーの前工程」に変更
- 広告枠（左右縦長・下部横長）を配置
- EthicalAds 申請予定
- Cloudflare Pages への移行作業中
- バックエンドをOpenAI → Claude APIに切り替え
