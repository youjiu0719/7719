# 教學工具箱

Wendy 自製的教學與班務小工具。首頁：index.html

## 更新「上課展示」（不用改 index.html）

首頁最上面的「上課展示」可以放圖片或 PDF，上課時點一下就全螢幕投影到白板。

1. 把檔案上傳到 `files/` 資料夾（jpg、png、pdf 都可以）。
   檔名建議用英文或數字，例如 `unit3-animals.pdf`。
2. 打開 `display.json`，按右上角鉛筆編輯，每個檔案寫一組：

```json
{
  "file": "files/unit3-animals.pdf",
  "title": "Unit 3 動物講義"
}
```

- 多組之間用逗號隔開，最後一組後面不要加逗號。
- 排在越上面，在首頁越前面。
- 不要的檔案：從 `display.json` 刪掉那一組即可（files 裡的檔案可留可刪）。
- 存檔（Commit changes）後等 1 分鐘，重新整理首頁就會更新。

### 投影時的操作

| 按鍵 | 功能 |
|---|---|
| → / PageDown / 空白鍵 / 簡報筆下一頁 | 下一頁（PDF 最後一頁會接到下一個檔案） |
| ← / PageUp / 簡報筆上一頁 | 上一頁 |
| + / − / 0 | 放大 / 縮小 / 符合畫面 |
| F | 全螢幕 |
| Esc | 離開 |

## 檔案

| 檔案 | 用途 |
|---|---|
| index.html | 工具箱首頁 |
| display.json | 上課展示清單 |
| files/ | 上課展示的圖片與 PDF |
| copy-sprint.html | 限時抄寫單字 |
| word-match.html | 單字閃卡（中英配對練習） |
| starters.html | Starters 口說抽卡 |
| post-card.html | 貼文圖卡產生器 |
| jixuan.html | 濟玄天書線上抽籤 |
| quiz.html | 題庫複習測驗（讀取 Google Sheets） |
| worksheet.html | 英文練習字 Worksheet 產生器 |
| tracing-book.html | 描紅小書工廠 |
| question-bank.html | 題庫轉換器 |
