# 新加坡 3天2夜家族旅行 App

單一 HTML 檔案的行程小網站，內含班機資訊、Day1–3 行程時間軸、新加坡出境須知、行前準備清單（可勾選、會記住狀態）、住宿與美食資訊。

## 這趟旅程

- 日期：2026/09/06（日）– 09/08（二）
- 同行：我、媽媽、外公、外婆（4 人）
- 去程：BR215　TPE 09:25 → SIN **T3** 13:50
- 回程：BR226　SIN **T3** 13:10 → TPE 17:45
- 住宿：Holiday Inn Singapore Atrium（訂單 1768307482，2 間連通房）

## 網址

https://s11428127.github.io/Singapore/

在手機上打開後，用 Safari／Chrome 選單裡的「加入主畫面」就能當 App 使用（已加好對應的 meta 標籤，開起來沒有網址列）。

## 開啟 GitHub Pages（只需設定一次）

1. 進入 repo 的 `Settings` 分頁
2. 左側選單找到 `Pages`
3. 在 `Build and deployment` → `Branch` 選擇 `main`，資料夾選 `/ (root)`，按 `Save`
4. 等 1–2 分鐘，網址就會出現在同一頁

## 之後想改內容

在 GitHub 網頁上點 `index.html` → 右上角鉛筆圖示編輯 → 找到對應的文字段落修改 → Commit，Pages 會自動重新部署，不需要額外操作。

## 檔案

- `index.html` — 整個網站（HTML／CSS／JS 都在這一個檔案裡，沒有其他相依）

行前清單的勾選狀態存在瀏覽器的 localStorage，只會留在你自己勾的那台裝置上，換手機或清除瀏覽資料就會重來。
