# Excel Yahoo Finance Market Data Automation

## 1. 專案目的
## 2. 系統架構
## 3. 系統流程圖
## 4. Yahoo Finance 資料
## 5. Excel 工作表架構
## 6. VBA Module 架構
## 7. 測試結果
## 8. Windows 工作排程器
## 9. 使用方式
//架構
Excel Yahoo Finance 自動化
│
├── 市場資料.xlsm
│   │
│   ├── Dashboard
│   │   ├── 最新資料
│   │   ├── 立即更新
│   │   ├── 啟動 08:30 排程
│   │   └── 停止 08:30 排程
│   │
│   ├── 歷史資料
│   │   └── 每次更新保存
│   │
│   ├── Log
│   │   └── 執行紀錄
│   │
│   ├── Module1
│   │   └── Yahoo資料取得與更新
│   │
│   ├── Module2
│   │   └── 測試及排程控制
│   │
│   └── Module3
│       └── Yahoo解析測試
│
└── 下一階段
    └── Windows 工作排程器
        └── 每天 08:30 自動執行
