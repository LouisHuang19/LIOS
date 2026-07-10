# Scanner System

Version: v1.0.7-basic

## 目的

Scanner 的目的不是「每天找新股票」，而是：

1. 找出符合 LIOS 條件的標的
2. 找出可取代弱勢持股的股票
3. 找出 B 級升 A 級的股票
4. 找出快要進入 Decision Engine 的候選標的
5. 避免因 FOMO 追高

## 評分來源

| 項目 | 說明 |
|---|---|
| 基本面 | 公司未來是否可能更好 |
| 估值 | 是否合理，不以股價高低判斷便宜 |
| 趨勢 | RS、均線、價格結構 |
| 籌碼 | 法人、主力、成交密集區 |
| 動能 | OBV、MACD、KD |
| LIOS 適配度 | 是否符合 Louis 的投資風格 |

## 評級

- S級：95分以上
- A級：90~94
- B級：80~89
- C級：60~79
- D級：60以下

## 重要原則

S級不代表可以追價。

S級代表：
- 值得長期追蹤
- 適合進入買點室
- 若回到合理位置，可跑 Decision Engine

## Scanner 與 Decision Engine 的關係

Scanner 只回答：

> 值不值得研究？

Decision Engine 才回答：

> 現在能不能買？

## Scanner 與 Portfolio 的關係

若持股中有健康度低於 60 的股票，Scanner 可用來尋找替代候選。

但換股前仍需跑 Decision Engine。
