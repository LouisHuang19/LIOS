# Repository Setup

Version: v1.0.2-basic

## GitHub

建議建立 private repository：

`LIOS`

放入：
- README.md
- VERSION.md
- CHANGELOG.md
- Core/
- Rules/
- Commands/
- Projects/
- Docs/
- Templates/

## Google Drive

建議建立資料夾：

`LIOS_DATA`

放入：
- Portfolio.xlsx
- Replay.xlsx
- Journal.xlsx
- Watchlist.xlsx
- Screenshots/
- Research/
- Archive/

## 為什麼分開

GitHub 適合：
- 系統規則
- 文件
- 版本紀錄
- patch

Google Drive 適合：
- 圖片
- Excel
- 每日資料
- 大型檔案

## 新聊天室使用

輸入：

`🚀 啟動 LIOS`

然後上傳：
- `Core/LIOS_Core.md`
- `Portfolio.xlsx`（需要持股分析時）
- `Replay.xlsx`（需要回測時）

## Git Patch 使用方式

收到 patch 後：

```bash
cd <your-repo-root>
git apply <patch-file>
git status
git add .
git commit -m "Apply LIOS patch"
```

## 建議 Commit 訊息

- `Apply LIOS Part 2 core rules clarification`
- `Apply LIOS Part 3 daily workflow and data templates`
