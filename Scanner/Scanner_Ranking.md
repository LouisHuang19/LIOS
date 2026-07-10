# Scanner Ranking

Version: v1.0.7-basic

## 目的

Ranking 用來把候選股依 LIOS 分數排序。

## 排名規則

### S級

95分以上。

特徵：
- 基本面強
- 估值未明顯失控
- 趨勢強
- OBV / RS 佳
- 適合長期追蹤

### A級

90~94分。

特徵：
- 可列入買點室
- 等待回檔或突破確認

### B級

80~89分。

特徵：
- 條件不差
- 尚未完全成熟
- 等待 RS / OBV / MACD 改善

### C級

60~79分。

特徵：
- 觀察
- 不急著買
- 需要更多確認

### D級

60以下。

特徵：
- 不加碼
- 避免新買
- 若已持有，送 Review Lab

## 輸出格式

| Rank | Ticker | Name | Score | Grade | Reason | Next Step |
|---|---|---|---:|---|---|---|
