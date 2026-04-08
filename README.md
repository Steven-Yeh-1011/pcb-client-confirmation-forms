# PCB／控制板 — 客戶端需求確認表單

靜態 HTML 表單，部署於 Vercel 供客戶填寫。

## 頁面

| 路徑 | 說明 |
|------|------|
| `/` | 首頁，可選簡易版或完整版 |
| `/form-simple.html` | 客戶端確認表單（簡易版） |
| `/form-full.html` | 客戶端確認表單（完整版） |

## 本機預覽

以瀏覽器直接開啟 `index.html`，或使用任意靜態伺服器。

## 部署到 Vercel

1. 將此儲存庫連結到 [Vercel](https://vercel.com)（Import Git Repository）。
2. **Framework Preset** 選 **Other**（或偵測為靜態網站即可）。
3. **Root Directory** 維持專案根目錄，不需建置指令；**Output** 留空即可。
4. 部署完成後，將產生的網址（如 `https://xxx.vercel.app`）傳給客戶即可。

## 來源檔案

表單內容源自 `D:\00_Inbox\PCB_borad\` 內之 `客戶端確認表單.html` 與 `客戶端確認表單_簡易版.html`（於此 repo 中分別對應 `form-full.html`、`form-simple.html`，檔名改為英文以利網址與工具相容）。

## 授權

專案內容依您公司／專案政策自行訂定。
