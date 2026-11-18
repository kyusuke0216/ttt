# Google Cloud 問い合わせ対応AIエージェント設計資料

Gemini Enterpriseの利用を前提に、Gemini Enterprise Agent Platform（ADK / Agent Runtime）を用いた問い合わせ対応マルチエージェントの構成を検討する資料です。

## 設計方針
- **Gemini Enterprise**：企業向けAI利用・エージェント公開・ナレッジ連携
- **ADK + Agent Runtime**：問い合わせ分類、ヒアリング、社内検索、回答検証、業務API連携
- **独自UI**：チャット画面、将来の音声インターフェース
- **Gemini Live API（将来）**：リアルタイム音声会話
- **横断統制**：IAM、監査ログ、評価、アクセス権限

## 画像一覧（追加予定）
| ファイル名 | 内容 |
|---|---|
| `images/01-multi-agent-overview.png` | マルチエージェント構成図 |
| `images/02-implementation-roadmap.png` | 実装ロードマップ |
| `images/03-architecture-pros-cons.png` | 方式別メリット・デメリット |
| `images/04-evaluation-matrix.png` | 評価観点別の比較表 |
| `images/05-cx-adk-detailed-architecture.png` | CX Agent Studio + ADKの詳細構成 |
| `images/06-ge-agent-platform-architecture.png` | Gemini Enterprise + Agent Platformの詳細構成 |
| `images/07-recommended-pattern-comparison.png` | 推奨構成を含む方式比較 |

> 画像は構想段階の概念図です。Google Cloudの製品名・接続方式・機能制限・認可・契約条件は公式ドキュメントとPoCで検証してください。

## 公開時の注意
このリポジトリはPublicです。顧客名、機密データ、認証情報、非公開システムの詳細を追加しないでください。
