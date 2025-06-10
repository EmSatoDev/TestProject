# スクラム開発ドキュメント構造

このドキュメント構造は、AIエージェントを活用したスクラム開発プロセスをサポートするために設計されています。

## 📁 フォルダ構造

### 🎯 Product Management
- `product-backlog/` - プロダクトバックログの管理
- `user-stories/` - ユーザーストーリーの詳細
- `acceptance-criteria/` - 受け入れ基準の定義

### 🏃‍♂️ Sprint Management
- `sprints/` - 各スプリントの管理
  - `sprint-planning/` - スプリント計画
  - `sprint-backlog/` - スプリントバックログ
  - `daily-standups/` - デイリースタンドアップ記録
  - `sprint-review/` - スプリントレビュー
  - `sprint-retrospective/` - スプリント振り返り

### 📊 Progress Tracking
- `burndown-charts/` - バーンダウンチャート
- `velocity-tracking/` - ベロシティ追跡
- `metrics/` - 各種メトリクス

### 🤖 AI Agent Management
- `ai-agents/` - AIエージェントの設定と管理
- `automation/` - 自動化スクリプトとワークフロー

### 📋 Templates
- `templates/` - 各種テンプレート

## 🚀 使用方法

1. 新しいスプリントを開始する際は、`sprints/sprint-XX/` フォルダを作成
2. プロダクトバックログアイテムは `product-backlog/` で管理
3. AIエージェントの設定は `ai-agents/` で管理
4. 進捗は各スプリントフォルダ内で追跡

## 🔄 ワークフロー

1. **プロダクトバックログ作成** → `product-backlog/`
2. **スプリント計画** → `sprints/sprint-XX/sprint-planning/`
3. **デイリースタンドアップ** → `sprints/sprint-XX/daily-standups/`
4. **進捗追跡** → `burndown-charts/`, `velocity-tracking/`
5. **スプリントレビュー・振り返り** → `sprints/sprint-XX/sprint-review/`, `sprint-retrospective/` 