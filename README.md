# LIOS — Louis Investment Operating System

Version: v1.0.2-basic

LIOS 是 Louis 的個人投資作業系統，用一致的流程管理選股、持股、風險、Replay 與 Review。

## 快速啟動

在新的 ChatGPT 視窗輸入：

> 🚀 啟動 LIOS

並上傳：

1. `Core/LIOS_Core.md`
2. 需要分析持股時，上傳 `Portfolio.xlsx`
3. 需要 Replay 時，上傳 `Replay.xlsx`
4. 需要分析技術面時，上傳 K 線、OBV、MACD、KD、分價成交圖

## 核心理念

> 以基本面決定買什麼，以估值決定值不值得買，以趨勢決定什麼時候買，以紀律決定什麼時候賣。

## 目前版本狀態

- v1.0.2-basic
- 目標：先求有，再求好
- 原則：不新增大功能，只把 Part 1 / Part 2 的基本流程整理清楚
- 目前專案：Project Alpha — Replay30

## GitHub 放什麼

GitHub 放系統文件：

- `Core/`
- `Rules/`
- `Commands/`
- `Projects/`
- `Docs/`
- `Templates/`
- `CHANGELOG.md`
- `VERSION.md`

## Google Drive 放什麼

Google Drive 放每天會變的資料：

- `Portfolio.xlsx`
- `Replay.xlsx`
- `Journal.xlsx`
- `Watchlist.xlsx`
- 截圖
- 研究資料

## 日常使用流程

1. 啟動 LIOS
2. 查看風險室
3. 如果要做交易，跑 Decision Engine
4. 如果有新策略，送 Strategy Lab
5. 如果要驗證歷史案例，送 Replay Lab
6. 每月底 Review

詳見：
- `Docs/Daily_Workflow.md`
- `Docs/Repository_Setup.md`
- `Docs/Data_Schema.md`

## Replay System

Replay 文件位於 `Replay/`，用於 Project Alpha — Replay30。

## Scanner System

Scanner 文件位於 `Scanner/`，用於選股室、Watchlist、S級股票與買點室。

## Handbook

Handbook 文件位於 `Handbook/`，用於新視窗快速上手與日常操作查詢。
