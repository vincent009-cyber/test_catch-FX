**Excel Yahoo Finance 市場及匯率資料自動化**

使用 Excel VBA + Yahoo Finance 自動取得匯率資料並保存歷史紀錄。

📊 市場資料

匯率
USD/TWD
JPY/TWD
EUR/TWD
CNY/TWD
市場指數
TWII — 台股加權指數
GSPC — S&P 500

🔄 系統流程

Excel → VBA → Yahoo Finance → 更新資料 → 保存歷史資料 → Log → Save

📁 Excel 架構

Dashboard

最新市場資料

立即更新

08:30 排程

資料

歷史資料 — 保存每次更新結果

Log — 記錄執行狀態

VBA

Module1 — Yahoo Finance 資料取得與更新

Module2 — 手動更新與排程控制

Module3 — 資料解析與測試

🧪 開發進度

✅ Yahoo Finance — 資料取得

✅ 6 項市場資料

✅ 最新有效交易日

✅ 歷史資料保存

✅ Log

✅ Excel 自動儲存

✅ 每分鐘測試

✅ Dashboard 按鈕

✅ VBA 08:30 排程

⏳ Windows 08:30 自動排程

🎯 最終目標

每天 08:30
↓
Windows 工作排程器
↓
開啟 Excel
↓
執行 VBA
↓
Yahoo Finance
↓
更新資料
↓
保存歷史資料
↓
自動儲存
↓
關閉 Excel
Windows 工作排程器：下一階段

**最終目標**
每天 08:30 → Windows 工作排程器 → 開啟 Excel → 執行 VBA → Yahoo Finance → 更新 → 保存 → 關閉 Excel
