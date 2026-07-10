# Replay SOP

Version: v1.0.6-basic

## Step 1 — 定義案例

記錄：

- 股票
- Replay 日期
- 案例背景
- 當時討論的問題

## Step 2 — 收集當時資料

只收集當天以前可見資訊：

- K 線
- KD
- MACD
- OBV
- RS
- 法人
- 融資
- 分價成交
- 月營收 / 基本面
- 大盤環境

## Step 3 — 跑 Decision Engine

記錄：

- Decision Score
- 燈號
- 支持理由
- 反方風險
- 是否進場

## Step 4 — 記錄進場

若 LIOS 允許進場：

- Entry Date
- Entry Price
- Entry Reason
- Position Type

若不進場：

- 記錄等待原因
- 後續觀察是否轉強

## Step 5 — 每日持有判斷

每個交易日檢查：

- RS 是否惡化
- OBV 是否出貨
- MACD 是否翻弱
- KD 是否死亡交叉
- 是否跌破主力成本區
- 是否出現 Kill Switch

## Step 6 — 出場

記錄：

- Exit Date
- Exit Price
- Exit Reason
- 是否符合 LIOS 出場規則

## Step 7 — 計算結果

計算：

- Return %
- Holding Days
- Max Adverse Excursion
- Max Favorable Excursion
- Result Type

## Step 8 — Review

回答：

- 哪個指標最有幫助？
- 哪個指標誤導？
- 是否應該修改規則？
- 是否只是正常交易小虧？
- 是否有情緒化行為？
