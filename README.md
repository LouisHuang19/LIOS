# LIOS — Louis Investment Operating System

Version: v1.0.0 Stable Baseline

LIOS 是 Louis 的個人投資作業系統，用一致的流程管理選股、持股、風險、Replay 與 Review。

## 核心理念

> 以基本面決定買什麼，以估值決定值不值得買，以趨勢決定什麼時候買，以紀律決定什麼時候賣。

## 快速啟動

```text
🚀 啟動 LIOS
```

上傳：
1. `Core/LIOS_Core.md`
2. 分析持股時上傳 `Portfolio.xlsx`
3. Replay 時上傳 `Replay.xlsx`

## v1.0 狀態

- Status: Stable Baseline
- Mode: Feature Freeze
- Current Project: Project Alpha — Replay30

v1.0 的目標不是新增功能，而是開始實際使用、記錄、Replay 與 Review。

## 主要資料夾

| Folder | Purpose |
|---|---|
| Core/ | LIOS 核心與架構 |
| Rules/ | 決策、風險、Replay、Scanner 規則 |
| Commands/ | 指令表 |
| Rooms/ | 投資室、戰情室、風險室 |
| Portfolio/ | 持股管理流程 |
| Replay/ | Replay System 與 Replay30 |
| Scanner/ | 選股室、Watchlist、BuyPoint |
| Handbook/ | 使用手冊 |
| Docs/ | Repo、Workflow、Data Schema |
| Projects/ | Project Alpha 等專案 |
| Templates/ | CSV / Markdown 範本 |
| Release/ | Release Notes、Migration、Roadmap |


## Remote Bootstrap

新視窗建議使用：

```text
🚀 啟動 LIOS
https://raw.githubusercontent.com/LouisHuang19/LIOS/refs/heads/main/bootstrap.json
```

AI 應先讀取 `bootstrap.json`，再依序載入 required documents。

舊的 Core Raw URL 仍可使用。
