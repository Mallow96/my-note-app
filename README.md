# My Note App 📝

一個基於 **Vite** 與 **Vue 3.5** 構建的高性能單頁筆記應用程式 (SPA)。本專案旨在展示現代前端工具鏈的整合，包括全域狀態管理、動態路由導航以及瀏覽器端資料持久化技術。

## 🌟 核心特色
* **Vite 驅動**：利用原生 ESM 模組提供極速的冷啟動與秒級熱更新 (HMR)，最佳化開發體驗。
* **Vue 3 (Composition API)**：使用最新的 `script setup` 語法，實現高內聚、低耦合的組件開發。
* **全域狀態管理 (Pinia)**：
    * 透過 `note_store.js` 集中管理筆記資料。
    * **自動化持久化**：深度監聽資料變動，自動同步至 `localStorage`。
* **多頁面路由系統 (Vue Router)**：
    * 使用 **HTML5 History 模式** 實現流暢的無刷新頁面切換。
    * 包含 `Home`、`All Notes` 與 `Add Note` 三大核心視圖。
* **非同步通訊能力**：整合 **Axios**，為未來擴充雲端資料庫串接奠定基礎。

## 🛠 技術棧 (Tech Stack)
| 技術 | 工具 | 描述 |
| :--- | :--- | :--- |
| **Build Tool** | **Vite** | 次世代前端構建工具 |
| **Framework** | Vue 3.5 | 核心前端框架 |
| **State** | Pinia 3.0 | 狀態管理與持久化邏輯 |
| **Routing** | Vue Router 4.5 | 單頁應用路徑導覽 |
| **Network** | Axios 1.11 | Promise 基礎的 HTTP 客戶端 |



## 📁 專案路由導航
* `/` : **首頁** (HomeView)
* `/allNotes` : **所有筆記** (AllNotesView) - 瀏覽與刪除已存筆記
* `/addNote` : **新增筆記** (AddNoteView) - 筆記撰寫介面

GitHub Page: https://mallow96.github.io/my-note-app/#/

取得專案
```bash
git clone [https://github.com/Mallow96/my-note-app.git](https://github.com/Mallow96/my-note-app.git)
cd "my-note-app/my note"
