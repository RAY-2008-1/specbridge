[日本語](#日本語) | [English](#english)

---

<a name="日本語"></a>
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

## 広告枠

Google AdSense の承認後に差し替え予定。

---

## 活動ログ

### 2026-05-18
- SpecBridge α版を公開
- RequiFlow（要件定義ツール）からリブランド
- 訴求を「AIアプリビルダーの前工程」に変更
- 広告枠（左右縦長・下部横長）を配置
- Google AdSense 申請予定
- Cloudflare Pages への移行作業中
- バックエンドをOpenAI → Claude APIに切り替え

---

<a name="english"></a>
# SpecBridge

> Build your spec before you build your app.

A bridge between non-engineers and AI app builders.  
Answer 5 questions to generate a spec you can paste directly into BASE44 / Bolt / Lovable / Cursor.

## Overview

"I want AI to build my app, but I don't know what to tell it."

SpecBridge is a pre-step tool for non-engineers.  
It organizes your goals, users, features, admin needs, and constraints into a clear spec and a ready-to-paste prompt.

## Features

- 5-question flow to structure your requirements
- Auto-generates app summary, target users, key screens, and risk checklist
- Outputs a prompt you can paste directly into any AI app builder
- Ctrl+Enter to submit answers quickly
- Works without an API key via fallback mode

## Tech Stack

- Frontend: HTML / CSS / JavaScript (no build step)
- Backend: Cloudflare Pages Functions
- AI: Claude API (Anthropic claude-sonnet-4-6)

## Ads

Will be replaced with Google AdSense after approval.

---

## Activity Log

### 2026-05-18
- Launched SpecBridge alpha
- Rebranded from RequiFlow (requirements definition tool)
- Repositioned as "the step before AI app builders"
- Added ad slots (left/right sidebar + bottom banner)
- Google AdSense application pending
- Migrating to Cloudflare Pages
- Switched backend from OpenAI to Claude API
