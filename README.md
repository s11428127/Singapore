# 新加坡 3天2夜家族旅行 App

單一 HTML 檔案的行程小網站，內含班機資訊、Day1–3 行程時間軸、行前準備清單（可勾選、會記住狀態）、住宿與美食資訊。

- 旅行日期：2026/09/06（日）– 09/08（二）
- 同行：我、媽媽、外公、外婆
- 班機：去程 BR225 TPE 07:30 → SIN 11:55／回程 BR216 SIN 15:20 → TPE 20:00
- 住宿：Holiday Inn Singapore Atrium

## 網址

啟用 GitHub Pages 後可從這個網址打開：

https://s11428127.github.io/Singapore/

## 開啟 GitHub Pages 的步驟

1. 進入 repo 的 `Settings` 分頁
2. 左側選單找到 `Pages`
3. 在 `Build and deployment` → `Branch` 選擇 `main`，資料夾選 `/ (root)`，按 `Save`
4. 等 1–2 分鐘，網址就會出現在同一頁

在手機上打開後，用 Safari／Chrome 選單裡的「加入主畫面」就能當 App 使用。

## 之後想改內容

在 GitHub 網頁上點 `index.html` → 右上角鉛筆圖示編輯 → 找到對應的文字段落修改 → Commit，Pages 會自動重新部署，不需要額外操作。

## 檔案

- `index.html` — 整個網站（HTML／CSS／JS 都在這一個檔案裡，沒有其他相依）

行前清單的勾選狀態存在瀏覽器的 localStorage，只會留在你自己勾的那台裝置上。
