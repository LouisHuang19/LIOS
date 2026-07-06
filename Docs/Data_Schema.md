# Data Schema

Version: v1.0.2-basic

## Portfolio 欄位

| 欄位 | 說明 |
|---|---|
| Market | TW / US |
| Ticker | 股票代號 |
| Name | 名稱 |
| Category | 核心 / 波段 / 觀察 / 成長 |
| Shares | 股數 |
| Cost | 成本 |
| Current Price | 現價 |
| Market Value | 市值 |
| Cost Value | 成本總額 |
| PnL | 損益 |
| PnL % | 報酬率 |
| LIOS Grade | 健康度或等級 |
| Action | 建議動作 |
| Notes | 備註 |

## Replay 欄位

| 欄位 | 說明 |
|---|---|
| Case ID | Replay 編號 |
| Ticker | 股票代號 |
| Name | 股票名稱 |
| Replay Date | 回測日期 |
| Entry Signal | 進場理由 |
| Entry Price | 進場價 |
| Exit Signal | 出場理由 |
| Exit Price | 出場價 |
| Return % | 實際報酬 |
| Result | 完全成功 / 小成功 / 小失敗 / 大失敗 |
| Notes | Review 註記 |

## Journal 欄位

| 欄位 | 說明 |
|---|---|
| Date | 日期 |
| Ticker | 股票代號 |
| Action | 買 / 賣 / 加碼 / 減碼 / 續抱 |
| Reason | 原因 |
| LIOS Room | 使用的模組 |
| Decision Score | 決策分數 |
| Emotion Score | 情緒分數 |
| Result | 結果 |
| Review | 後續檢討 |

## Watchlist 欄位

| 欄位 | 說明 |
|---|---|
| Ticker | 股票代號 |
| Name | 股票名稱 |
| Theme | 題材 |
| Stage | Seed / Launch / Core |
| Trigger | 觸發條件 |
| Risk | 主要風險 |
| Status | 觀察 / 待確認 / 可列入 Decision Engine |
| Notes | 備註 |
