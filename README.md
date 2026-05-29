# 🍎 Apple Shop 小教室顧客簡報生成器

為門市小教室快速產出**顧客視角**的講座簡報，可即時編輯、下載 .pptx 或匯出 PDF。

## 🚀 立即使用

👉 **https://snowsepch.github.io/apple-shop-workshop/**

## ✨ 主要功能

- 📚 **26 個內建主題** — 涵蓋 iPhone、iPad、Mac、Watch、AirPods、軟體 App、進階教學
- 🎯 **5 種年齡層客製** — 兒童、青少年、上班族、家長、銀髮族
- 🔀 **多主題融合模式** — 多選會自動串成連貫的整合式分享
- ✏️ **即時編輯** — 點擊文字直接修改
- 📥 **下載 .pptx** — Keynote 可直接開啟編輯
- 🖨 **列印 / PDF**
- 🆕 **自訂主題** — 表單新增或 JSON 匯入
- 🧠 **智慧場次標題** — 根據選擇的主題自動命名

## 📂 專案結構

```
apple-shop-workshop/
├── index.html          ← 主程式
├── data/
│   ├── topics.json     ← 主題庫（這個檔案決定所有主題內容）
│   ├── ages.json       ← 年齡層設定
│   └── version.json    ← 版本號
└── README.md
```

## 🔄 維護更新流程

### 一般更新（如修字、補資訊）
直接編輯 `data/topics.json`，commit 後所有門市自動拿到最新版本。

### Apple 系統更新時（如 iOS 27 上市）
1. 找 Enchanté（AI 助理）：「Apple 出了 iPhone 19，幫我更新主題」
2. 取得新的 JSON 內容
3. 編輯 `data/topics.json` 加入或更新主題
4. 更新 `data/version.json` 的版本號（例如 2.0 → 2.1）
5. Commit 推送 → 全國門市自動更新

## 🏪 多門市使用建議

- **官方主題**：由總部維護 `topics.json`
- **門市自訂**：用網頁的「➕ 新增單一主題」功能（存在瀏覽器 localStorage）
- **跨店分享**：用「📤 匯出」分享 JSON 給其他門市「📥 匯入」

## 📜 版本紀錄

查看 [CHANGELOG.md](./CHANGELOG.md) 或 GitHub Commits 歷史。

---

Made with ❤️ for Apple Shop
