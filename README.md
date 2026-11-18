# 家庭旅行手帳（GitHub Pages 版）

## 檔案
- index.html：整個 APP（行程、清單、記帳、計算機、翻譯入口、資訊）
- manifest.webmanifest、icon-*.png、apple-touch-icon.png：加到手機桌面用
- sw.js：離線快取（第一次連網開啟後，之後沒網路也能開）
- .nojekyll：讓 GitHub Pages 原樣提供檔案

## 放上 GitHub Pages
1. 登入 GitHub，新增一個 repository（例如 family-trip）
2. 把這個資料夾裡的所有檔案（包含 .nojekyll）上傳到 repository 根目錄
3. Settings → Pages → Source 選「Deploy from a branch」，Branch 選 main、資料夾選 / (root)，按 Save
4. 約 1 到 2 分鐘後，網址是 https://你的帳號.github.io/repository名稱/

## 加到手機桌面
- iPhone：用 Safari 開啟網址 → 分享 → 加入主畫面
- Android：用 Chrome 開啟網址 → 選單 → 加到主畫面／安裝應用程式

## 更新內容
修改 index.html 後重新上傳，並把 sw.js 第 2 行的 trip-v1 改成 trip-v2（每次加 1），手機才會更新。

## 隱私提醒
- 免費 GitHub 帳號的 Pages 需要公開 repository，任何人知道網址都能看到內容。
- 這個版本已經拿掉訂單編號、Airbnb 地址與確認碼、房東電話，並把孩子的名字改成「小朋友」。
- 這些資料請在手機上的「資訊」分頁自行填入，只會存在你的手機瀏覽器，不會上傳。
- 資料（記帳、清單勾選）存在各自手機的瀏覽器裡，不同手機不會同步。
