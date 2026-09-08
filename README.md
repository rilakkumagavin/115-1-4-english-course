# 115-1-4-english-course

整冊英語課程靜態網站，從 [課程入口](./index.html) 選擇單元。

課程順序：Unit 1 → Unit 2 → Review 1 → Unit 3 → Unit 4 → Review 2 → Culture & Festivals: Halloween。

## GitHub Pages

在 repository 的 **Settings → Pages**，選擇 **Deploy from a branch → main → /(root)**，按 **Save**。

部署完成後網址：[線上課程](https://rilakkumagavin.github.io/115-1-4-english-course/)。

根目錄包含 `index.html`、`.nojekyll`，七個課程資料夾各含 `site/` 的六個 HTML。更新時保留目錄結構與大小寫。所有課程頁的 **Back to Course Home** 以 `../../index.html` 返回入口。

## 離線使用

下載完整專案後開啟根目錄 `index.html`。CSS、JavaScript 與圖形均內嵌，不需要 CDN 或建置步驟。Listen 使用裝置本機英文語音；若裝置沒有適用聲音，文字與練習仍可使用。

本機部署檢查：43 個 HTML、7 個入口、42 個返回連結、380 個相對連結通過；沒有遺失檔案或外部資源依賴。
