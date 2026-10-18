<div align="center">

[English](README.md) · [简体中文](README.zh-CN.md) · [**日本語**](README.ja.md)

# Hi, I'm XY 👋

### AI Application Builder · Agent Workflow Explorer · Cybersecurity Researcher

AIを「答えるだけ」から、**行動し、検証し、復旧できる**アプリケーションへ。

[![GitHub](https://img.shields.io/badge/GitHub-XY--code1-181717?style=flat-square&logo=github)](https://github.com/XY-code1)
[![Email](https://img.shields.io/badge/Email-xyuzzz123456%40gmail.com-4A90E2?style=flat-square&logo=gmail&logoColor=white)](mailto:xyuzzz123456@gmail.com)
[![Xiaohongshu](https://img.shields.io/badge/Xiaohongshu-@XY-FF2442?style=flat-square&logo=xiaohongshu&logoColor=white)](https://www.xiaohongshu.com/user/profile/6a63c2420000000013031400)

</div>

---

## About Me

私は **独立系AI開発者** として、**AIアプリケーション開発、LLM、AI Agents、RAG**、そして **AIセキュリティ研究** に取り組んでいます。

曖昧なアイデアを、入力の理解、行動計画、人間による制御、変更の実行、実状態に基づく結果検証という、動作するプロダクトフローへ落とし込むことが好きです。Hackathonやオープンソース活動を通じて、学びを目に見える再利用可能な成果へ変えています。

- 🔭 信頼性・説明可能性・検証可能性を備えたAI Agentアプリを開発
- 🧠 LLM / RAG / Agent workflow / AIセキュリティを深く探究
- 🌱 Rustを学びながら、フロントエンドとソフトウェア工学の基礎を強化
- 🤝 AIアプリ、開発者ツール、UX関連のOSSへの貢献に関心

## Tech & Tools

> キーワードの数ではなく、実際の経験レベルに基づいて分類しています。

| 分野 | 技術・ツール |
| --- | --- |
| **主要言語** | Python |
| **アプリ開発** | React · Vite · TypeScript / JavaScript |
| **プログラミング基礎** | Java · C |
| **学習中** | Rust |
| **AI** | LLM Applications · AI Agents · RAG · Human-in-the-loop · AI Security |
| **開発ワークフロー** | Git · GitHub · Pull Requests · CI |

## Featured Work

### 🛡️ [Schedule Guardian / Plan Guardian](https://github.com/XY-code1/plan-guardian)

スケジュール競合を扱う **Human-in-the-loop Agent**。自然言語の予定変更依頼を理解し、時間の競合を検出して実行可能な候補を提示します。明示的な承認後にのみ変更を実行し、書き込み後に状態を再読込して結果を検証します。

`conflict detection` → `plan` → `approve / reject` → `execute` → `reread & verify`

**重視する点：** 承認境界、planとversionの紐付け、fail-closed、拒否時に書き込まないこと、実行後の検証。

---

### 🎵 AI Co-Screen Assistant / In-Sync Live

Tencent Music Hackathonで開発した、音楽の興味マッチング、AIによる会話のきっかけ作り、没入型ソーシャルUIを組み合わせたプロジェクトです。共通の音楽嗜好を自然な交流の出発点にします。

**Keywords:** `music-interest matching` · `AI icebreaking` · `immersive social UI`

> リポジトリは非公開のため、リンクは掲載していません。

## Open Source

Agent基盤、ランタイムの信頼性、オープンソース・サプライチェーンの安全性を中心に貢献しています。以下はGitHubで公開確認できる代表的な実績で、マージ済みとレビュー中を明確に区別しています。

### 🦌 [ByteDance DeerFlow · PR #6894](https://github.com/bytedance/deer-flow/pull/6894) · **Merged**

run eventのタイムスタンプをSQLiteへ保存した際にタイムゾーンoffsetが失われる不具合を修正。3つのDB書き込み経路すべてでUTCへ正規化し、往復後も同一時刻を保持することを実SQLiteの回帰テストで確認しました。

`Python` · `SQLite` · `runtime persistence` · `timezone correctness`

### 🛡️ [OpenSSF Scorecard · PR #5339](https://github.com/ossf/scorecard/pull/5339) · **Open**

GitLab Code-Review分析が、順序保証のないcommit一覧の先頭を検索時間境界に使う問題を修正。commit順序と既存互換性を保ったまま、最新の有効なcommit日時を計算します。

`Go` · `GitLab API` · `open-source security` · `regression tests`

### 🧠 [TencentDB Agent Memory · PR #1717](https://github.com/TencentCloud/TencentDB-Agent-Memory/pull/1717) · **Open**

L2 memory extractionの失敗が「データなしの成功」として扱われる問題を修正。正当なゼロ件処理を維持しながら、構造化された失敗をworkerの既存retry経路へ伝播させます。

`TypeScript` · `AI memory pipeline` · `failure propagation` · `retry semantics`

### 🔎 [Tencent BrowserSkill · PR #457](https://github.com/Tencent/BrowserSkill/pull/457) · **Open**

[Issue #386](https://github.com/Tencent/BrowserSkill/issues/386) に対応し、session idleの可観測性を改善。推定残りidle時間と構造化されたtimeout reasonを公開し、原因不明の状態消失に見えていたsession回収を診断可能にします。

`Rust` · `browser automation` · `session lifecycle` · `observability`

## What I Care About

```text
Useful AI      > impressive demos only
Verified state > optimistic success messages
Human control  > silent automation
Clear evidence > vague claims
```

## Let's Connect

- GitHub: [@XY-code1](https://github.com/XY-code1)
- Email: [xyuzzz123456@gmail.com](mailto:xyuzzz123456@gmail.com)
- Xiaohongshu: [プロフィール](https://www.xiaohongshu.com/user/profile/6a63c2420000000013031400)

<div align="center">

_Keep building. Keep verifying. Stay curious._

</div>
