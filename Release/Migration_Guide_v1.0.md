# Migration Guide — v1.0

Version: v1.0.0

## 從 Part 1~9 升級到 v1.0

套用 Part 10 patch 後：

1. 確認 `VERSION.md` 顯示 `v1.0.0`
2. 確認 `Release/` 資料夾存在
3. 確認 `README.md` 已更新為 Stable Baseline
4. 建議建立 Git tag

```bash
git status
git add .
git commit -m "Release LIOS v1.0 stable baseline"
git tag v1.0.0
```
