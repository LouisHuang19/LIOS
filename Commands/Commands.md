# LIOS Commands

Version: v1.0.0

## Boot
- 🚀 啟動 LIOS

## Daily
- 查看風險室
- 查看投資室
- 查看戰情室

## Decision
- 跑 Decision Engine：<股票>
- 跑 Decision Engine：<股票> 買入
- 跑 Decision Engine：<股票> 加碼
- 跑 Decision Engine：<股票> 續抱
- 跑 Decision Engine：<股票> 減碼

## Replay
- Replay：<股票> <日期>
- Replay Review：<Replay ID>
- 查看 Replay30

## Scanner
- 查看選股室
- 查看 S 級股票
- 查看 Watchlist
- 查看買點室

## Strategy
- Strategy Lab：<策略內容>
- Review Lab：<案例或規則>

## v1.0 Daily Minimal Flow
1. 查看風險室
2. 查看投資室
3. 有交易才跑 Decision Engine
4. 每週做一個 Replay
5. 每月 Review


## Remote Boot

- 🚀 啟動 LIOS + `bootstrap.json` Raw URL
- 直接貼上 `bootstrap.json` Raw URL
- 若遠端讀取失敗，上傳 `bootstrap.json` 與 `Core/LIOS_Core.md`
