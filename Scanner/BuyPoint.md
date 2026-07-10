# Buy Point

Version: v1.0.7-basic

## 目的

BuyPoint 用來判斷候選股是否接近可行的買點。

它不是買進指令。

## BuyPoint 條件

候選股需至少符合三項：

- RS 轉強
- OBV 上升
- MACD 綠柱縮短或翻紅
- KD 黃金交叉且未過熱
- 回測主力成本區守住
- 法人回補
- 估值合理
- 基本面未惡化

## 不合格買點

以下不視為買點：

- 只因股價跌很多
- 只因接近季線
- 只因 KD 低檔
- 只因新聞很熱
- 只因群組說外資洗盤

## BuyPoint 輸出格式

| Ticker | Name | Setup | Trigger | Risk | Decision |
|---|---|---|---|---|---|

## 下一步

若 BuyPoint 成立：

> 跑 Decision Engine：<股票> 買入
