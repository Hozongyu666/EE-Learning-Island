# ⚓ 國立臺灣海洋大學電機工程學系 - 3D 互動式學程島 (NTOU EE 3D Island)

這是一個基於 HTML5 Canvas 與 Tailwind CSS 開發的單頁面互動式 Web 應用程式 (SPA)。將海大電機系的「113 學年度必修科目表」、「六大領域師資與實驗室」及「修業規定」轉化為生動、高質感的 3D 等距立體 (Isometric 3D) 互動島嶼。

## ✨ 核心特色與功能 (Features)

* **🏝️ 全 3D 等距立體渲染引擎 (Isometric 3D)**
  告別扁平的 2D 網頁，採用自製 Canvas 3D 繪圖引擎，渲染出具有真實厚度切面的多層次地形、立體玻璃帷幕系館大樓，以及生動的 3D 立體角色。
* **🎓 系主任與學長姐 NPC 互動**
  內建現任系主任（譚仕煒教授）的真實影像互動獎座，搭配分佈於島上的大一至大四學生 NPC。小人具備平滑路徑緩動 (Smooth Waypoints) 不抽動，靠近時會自動浮現修課攻略與實驗室心得。
* **👨‍🔬 師資陣容與專屬實驗室名錄**
  完整收錄海大電機系「固態電子、控制、電力與電子電路、電波、通訊與訊號處理、資訊科技」六大領域的教授名單、最高學歷、研究專長及實驗室位置，支援即時關鍵字與領域篩選。
* **🧮 137 畢業學分互動試算器**
  將繁雜的 Excel 必修科目表數位化，提供視覺化的學分檢核表。包含共同教育、系訂專業必修、六選三核心必選修與專業選修的自動加總試算。
* **🕸️ 核心課程先修關聯與領域分流**
  點擊島上立體系館，即可從右側滑出精品級課程抽屜，查看該館對應的必修課號，並瀏覽從大一基礎銜接至大四研究所的先修關聯圖。
* **✨ 極致細節與互動手感**
  內建實體跟隨的「正版海大深藍三道白浪校徽」游標、點擊水波漣漪特效、晝夜海景氛圍切換，以及無依賴的單檔 Base64 圖片直出技術。

## 🚀 快速開始 (Quick Start)

本專案採「無依賴、單一檔案」的極簡架構設計，無需安裝 Node.js、npm 或任何前端框架環境。

### 方法一：本機直接執行
1. 將 Repository 中的 `index.html` 下載至您的電腦。
2. 對著 `index.html` 點擊兩下，使用任何現代瀏覽器（Google Chrome, Edge, Safari, Firefox）開啟即可體驗完整 3D 互動內容。

### 方法二：部署至 GitHub Pages (推薦)
1. 將此專案 Fork 或 Push 至您個人的 GitHub Repository。
2. 進入該 Repository 的 **Settings** > **Pages**。
3. 在 **Build and deployment** 下的 Source 選擇 `Deploy from a branch`。
4. Branch 選擇 `main`（或 `master`），資料夾選擇 `/ (root)`，然後點擊 **Save**。
5. 等待約 1-2 分鐘，即可透過 `https://<您的帳號>.github.io/<專案名稱>/` 公開分享給所有人。

## 🛠️ 技術棧 (Tech Stack)

* **UI 框架**: [Tailwind CSS](https://tailwindcss.com/) (透過 CDN 即時編譯)
* **字體排版**: Google Fonts (`Noto Sans TC`, `Plus Jakarta Sans`)
* **核心渲染**: HTML5 `<canvas>` API + 原生 Vanilla JavaScript
* **資源打包**: 圖片與 Icon 全數採用 Base64 編碼內嵌，達成零外部圖檔請求的單檔綠色應用程式。

## 📂 資料來源與聲明 (Data Sources)

本網站之課表、師資、實驗室等學務資訊均整合自以下官方來源：
* [國立臺灣海洋大學 電機工程學系 官方網站](https://ee.ntou.edu.tw/)
* 113 學年度入學生適用之必修科目表與核心課程關聯圖。
* 實際開課狀況、修課規定及畢業門檻，請以海大電機系辦公室每學期最新公告為準。


---
*Developed for NTOU EE Curriculum Interactive Project v4.0*
