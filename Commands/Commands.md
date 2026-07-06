# LIOS Commands

Version: v1.0.2-basic

## Boot

- 🚀 啟動 LIOS

## Rooms

- 查看投資室
- 查看戰情室
- 查看風險室
- 查看選股室
- 查看持股診斷
- 查看排行榜
- 查看買點室
- 查看警報器
- 查看學習室
- 查看投資日誌

## Engines

- 跑 Decision Engine：<股票>
- Replay：<股票> <日期>
- Strategy Lab：<策略內容>
- Review Lab：<案例或規則>

## Daily Flow

1. 查看風險室
2. 查看投資室
3. 查看戰情室
4. 若要交易，跑 Decision Engine
5. 若有新想法，送 Strategy Lab
6. 若有歷史案例，送 Replay Lab

## 固定輸出格式

### 投資室

需包含：
- 資產總覽
- 核心持股
- 風險提醒
- 今日一句

### 風險室

需包含：
- 風險燈號
- 現金狀態
- AI / 半導體集中度
- 弱勢持股
- 禁止事項

### Decision Engine

需包含：
- 分數
- 燈號
- 支持理由
- 反方檢查
- 建議動作

### Replay

需包含：
- 當時可見資訊
- LIOS 進場
- LIOS 出場
- 實際報酬
- Review


## Room Specific Commands

- 查看投資室：輸出 Dashboard
- 查看戰情室：輸出 Battle Room
- 查看風險室：輸出 Risk Room
