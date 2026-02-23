# 学習ログ管理

各プロジェクト・学習領域ごとに学習内容を記録。

## 構成

```
~/projects/learning/
├── security-specialist/     # 情報処理安全確保支援士の学習
│   └── learning_log.md
├── ai-agent-sandbox/        # AI・エージェント開発の学習
│   └── learning_log.md
├── web-development/         # Web開発の学習
│   └── learning_log.md
├── cpp-game-dev/            # C++・ゲーム開発の学習
│   └── learning_log.md（初回記録時に自動生成）
└── README.md               # このファイル
```

## 各ログの説明

### security-specialist
- **目的:** 情報処理安全確保支援士試験の学習
- **内容:** 暗号技術、セキュリティプロトコル、脆弱性対策
- **関連:** M-FACILITYプロジェクトでの実践

### ai-agent-sandbox
- **目的:** AI・LLMエージェント開発の学習
- **内容:** AI・エージェント・Claude Code・LangChain、プロンプトエンジニアリング
- **関連:** AI-Agent-Sandboxプロジェクト

### web-development
- **目的:** Web開発技術の学習
- **内容:** React・TypeScript・Next.js等のWeb技術
- **関連:** kakeibo-app、facility-management-system 等

### cpp-game-dev
- **目的:** C++・ゲーム開発の学習
- **内容:** C++・SFML・ゲームエンジン設計
- **関連:** 2d-platformerプロジェクト

## 使い方

### 1. 学習内容を記録

```
Claude Codeで学習中...
↓
新しい概念を自分の言葉で説明
↓
「記録して」と指示
↓
該当するlearning_log.mdに自動追記
```

### 2. 振り返り

```
「web-developmentで学んだことを振り返りたい」
→ 該当するログを読み込んで一覧表示
```

### 3. 検索

```
「DH法って何だったっけ」
→ 全ログから検索して表示
```

## 学習の記録ルール

- **507日ルール:** 毎日5〜10分は必ず学習
- **70%理解で次へ:** 完璧を目指さない
- **記録は明示的に:** 「記録して」と言った時だけ記録
- **重要なものだけ:** 全ての質問ではなく、重要な学びだけを厳選

## ファイルの同期

### Claude.ai（チャット）で記録した場合
1. チャットで「記録して」
2. ファイルをダウンロード
3. WSLの該当フォルダに上書き

### Claude Codeで直接編集した場合
- 自動的に保存される（同期不要）
