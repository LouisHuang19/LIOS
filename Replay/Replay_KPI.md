# Replay KPI

Version: v1.0.6-basic

## 核心 KPI

### Win Rate

成功案例 / 有效案例。

### Average Gain

成功案例平均獲利。

### Average Loss

失敗案例平均虧損。

### Expectancy

期望值：

```text
Expectancy = WinRate * AverageGain - LossRate * AverageLoss
```

### Profit Factor

```text
Profit Factor = Total Gains / Total Losses
```

### Max Drawdown

Replay 期間最大回撤。

### Average Holding Days

平均持有天數。

### Average Decision Score

進場時 Decision Engine 平均分數。

## 重要觀念

勝率不是唯一目標。

即使勝率只有 50%，如果平均獲利遠大於平均虧損，系統仍可能有效。

## Replay30 最低觀察門檻

Replay30 完成後，先看：

- Expectancy 是否為正
- 平均獲利是否大於平均虧損
- 大失敗案例是否可控
- 高分案例是否真的較穩定

## 不合格情況

如果出現以下情況，需 Review：

- 90 分以上案例仍大量失敗
- 低分案例反而經常成功
- KD / MACD / OBV 任一指標長期無效
- 出場規則導致多數獲利回吐為虧損
