# My Note App 📝

一個基於 **Vue 3.5** 構建的高性能單頁應用程式 (SPA)。本專案結合了全域狀態管理與動態路由導航，提供使用者直覺、快速且具備資料持久性的筆記管理體驗。

## 🌟 核心特色
* **Vue 3 (Composition API)**：採用最新標準，建構模組化且易於擴充的組件架構。
* **多頁面導航系統 (Vue Router)**：
    * **主頁 (Home)**：應用程式進入點與概覽。
    * **所有筆記 (All Notes)**：完整的筆記清單瀏覽與管理。
    * **新增筆記 (Add Note)**：專屬的筆記創作介面。
* **精準狀態管理 (Pinia Store)**：
    * 透過 `note_store.js` 處理筆記的 CRUD (增、刪、改、查) 邏輯。
    * **自動持久化**：使用 `watch` 深度監聽資料，自動同步至 `localStorage`。
* **現代化工具鏈**：由 **Vite** 驅動，確保極速的開發環境與最佳化的生產環境打包。

## 🛠 技術棧 (Tech Stack)
| 技術 | 工具 | 描述 |
| :--- | :--- | :--- |
| **Framework** | Vue 3.5 | 核心前端框架 |
| **State** | Pinia 3.0 | 全域資料流管理 |
| **Routing** | Vue Router 4.5 | 單頁應用路由導覽 |
| **Network** | Axios 1.11 | 非同步資料請求處理 |
| **Persistence** | LocalStorage | 瀏覽器端資料持久化 |



## 📁 專案導航結構
本專案定義了明確的路由邏輯，確保使用者體驗流暢：
* `/` : `HomeView` - 歡迎頁面與主要導覽。
* `/allNotes` : `AllNotesView` - 檢視所有已儲存的筆記，支援刪除操作。
* `/addNote` : `AddNoteView` - 提供表單輸入，快速建立新筆記。

GitHub Page: https://mallow96.github.io/my-note-app/#/

取得專案
```bash
git clone [https://github.com/Mallow96/my-note-app.git](https://github.com/Mallow96/my-note-app.git)
cd "my-note-app/my note"
