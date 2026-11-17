台灣賓果・超級獎號研究室

部署方式：
1. 將本資料夾內的 index.html、netlify.toml、data 資料夾及 data/history.csv 上傳到 GitHub repository 根目錄。
2. Netlify 選 Add new project / Import an existing project，連接 GitHub repository。
3. Build command 留白，Publish directory 填 .
4. 部署成功後開啟網站。

資料：data/history.csv 由既有 64,967 期賓果紀錄整理；超級獎號已補齊最近30天的資料。尚未配對的歷史期數會顯示「待補」。

更新：網站頁面可匯入含以下欄位的 CSV：日期,期別,超級獎號,號碼1,...,號碼20。自行匯入的資料會保存在該裝置瀏覽器的 IndexedDB；請用「匯出 CSV 備份」保存或移轉。

本網站是統計工具，不是台灣彩券官方網站。候選號碼僅依歷史統計排序，不代表未來中獎機率或保證。
