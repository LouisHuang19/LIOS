# LIOS Architecture

Version: v1.0.1-basic

## 分工

### GitHub：System

放固定規則、流程、版本與說明文件。

適合放：
- Core
- Rules
- Commands
- Projects
- Docs
- ChangeLog
- Version

### Google Drive：Data

放持股資料、Replay、Journal、截圖與研究資料。

適合放：
- Portfolio.xlsx
- Replay.xlsx
- Journal.xlsx
- Watchlist.xlsx
- Screenshots
- Research
- Archive

### ChatGPT：Analysis Engine

讀取 Core 與資料後，依 LIOS 流程分析與建議。

## 原則

System 與 Data 分離：
- Core 不放每日持股變動
- Portfolio / Replay / Journal 才放變動資料
- Core 只在規則修改時更新
- Portfolio 可以每天更新

## 推薦 Repo 使用方式

- GitHub：保存 `GitHub_LIOS/`
- Google Drive：保存 `Google_Drive_LIOS_DATA/`
- 新聊天室：上傳 Core + 所需資料檔
