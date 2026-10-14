# LOCAL AI // PROJECT CONTROL

這是可部署至 GitHub Pages 的唯讀控制台。開啟網頁時，瀏覽器直接從[專案試算表](https://docs.google.com/spreadsheets/d/1Gvz11LvzKoalal_ZGiUOrMZrsvnMND4P0EQhw-BJEmY/edit)的 `Dashboard`、`功能清單`、`更新紀錄` 工作表讀取資料。不使用 Google Apps Script，也不需要 Google Cloud API 金鑰。

試算表的共用權限必須為「知道連結的任何人可檢視」。網頁只顯示功能進度與更新摘要，但知道試算表網址的人也能讀取整份試算表；不要在其中放敏感資料。修改試算表內容後，網站按「更新」即可重新讀取，不必重新部署。

將 `index.html` 放在 GitHub 儲存庫根目錄，於 Settings → Pages 選擇 Deploy from a branch、主分支、`/(root)`，即可取得 `https://<使用者名稱>.github.io/<儲存庫名稱>/` 網址。
