# AI Agent Tools Detailed Comparison

## 2. 詳細功能比較

| 比較項目 | Claude Cowork | OpenAI Codex | Google Antigravity | OpenClaw | Hermes Agent |
|---|---|---|---|---|---|
| **主要使用者** | 非工程師、analyst、QS、finance、legal、researcher | Developer、software engineer、AI builder | Developer、startup builder、frontend / full-stack 人 | Power user、想有 AI personal assistant 嘅人 | 技術型 power user / developer |
| **是否需要 coding 背景** | 基本唔需要。Anthropic 明確話 Cowork 係設計俾 non-technical knowledge work，用 desktop、local files、apps 完成多步任務。 | 需要少量至中等 coding 概念。Codex 係 coding agent，可以 read / edit / run code，亦可接 GitHub repo。 | 需要 coding 背景。Google 形容 Antigravity 係 agentic development platform，可跨 editor、terminal、browser 自動 plan / execute / verify。 | 需要安裝及設定。OpenClaw 係自己喺 device 上跑嘅 personal AI assistant，可用 WhatsApp、Telegram 或 chat app 控制。 | 技術門檻最高。Hermes 可跑喺 VPS、cloud VM、Docker、SSH、serverless 等環境，主打長期運行。 |
| **文件處理能力** | 強。支援 Word、PDF、TXT、Markdown、HTML、JSON、CSV、Excel、PowerPoint、圖片等格式。 | 中。可以處理 repo 內文件、README、config、code docs，但唔係為 office 文件而設計。 | 中。主要處理 codebase、UI、browser testing artifacts。 | 視乎你接駁咩工具。官方定位係清 inbox、send email、manage calendar、flight check-in。 | 視乎你安裝嘅 tools / skills，可做文件、automation、report，但要自己配置。 |
| **Coding 能力** | 有，但唔係主菜；Cowork 係把 Claude Code 架構帶去 desktop knowledge work。 | 最強主菜。可寫、review、ship code；可用 IDE extension 或 cloud delegate 大任務。 | 好強，特別係 UI / browser / terminal 一齊做，例如寫 feature、launch app、用 browser 驗證 component。 | 可連 coding agents，但本身定位係 personal assistant 多過 IDE。 | 可寫 code、跑 script、spawn subagents，但較似長期 agent framework。 |
| **自動化能力** | 強於 desktop task，例如整理 folder、讀文件、抽資料、製作 draft。 | 強於工程自動化，例如 parallel cloud coding tasks、PR、bug fix、test。 | 強於開發流程自動化，例如多 agent、background bug fix、生成 test case、UI screenshots / walkthroughs。 | 強於個人生活 / 工作 assistant，例如 inbox、calendar、email、chat app 指令。 | 強於長期 unattended automation，例如 daily reports、nightly backups、weekly audits。 |
| **Memory / 長期記憶** | 有上下文，但主要係完成指定任務。 | 主要跟 repo / task context。 | 有 knowledge base，可保存有用 context / code snippets。 | 有 personal assistant / workspace 概念，context 可留喺自己機。 | 最強。Hermes 主打 built-in learning loop、memory、skill creation、跨 session recall。 |
| **多平台控制** | Desktop 為主；Pro / Max 有 mobile pairing research preview，但電腦要開住。 | VS Code、IDE、Codex Web、ChatGPT plan 內使用。 | Desktop IDE，支援 macOS、Windows、Linux public preview。 | WhatsApp、Telegram 或其他 chat app。 | Telegram、Discord、Slack、WhatsApp、Signal、CLI 等。 |
| **私隱 / 控制權** | 由 Claude desktop 控制指定 folder / app 權限；會要求權限，適合一般商業用，但 sensitive / regulated workload 要小心。 | 可本地 / cloud；cloud 會接 GitHub repo，適合工程但要小心 repo secret、API key、production 權限。 | Agent 可跨 editor、terminal、browser，權限要小心設定。 | 控制權較高，因為係 own devices / own data，但安全責任亦落喺你身上。 | 控制權最高，可自選 model、endpoint、VPS / cloud，但安全、維護、權限管理都要自己做。 |
| **成熟度 / 穩定性** | 較接近商業產品，適合日常工作。 | 商業級，OpenAI 官方 coding agent。 | Public preview，功能新但可能變動較大。 | 開源社群型，發展快但要接受折騰。 | 開源 agent framework，功能強但較 technical。 |
| **技術門檻** | 低 | 中 | 中至高 | 高 | 高至很高 |

## 簡單結論

| 用途 | 最推薦 |
|---|---|
| QS、Excel、PDF、VO、報告、Email | Claude Cowork |
| Python、AI trading bot、automation、debug | OpenAI Codex |
| Build app、UI、browser testing、AI IDE | Google Antigravity |
| WhatsApp / Telegram AI 管家 | OpenClaw |
| 自架長期 AI assistant / agent | Hermes Agent |

## 一句總結

Cowork 適合 office / knowledge work；Codex 同 Antigravity 適合 coding / app development；OpenClaw 同 Hermes 適合自架 personal AI agent。
