# 蔣介石傳 · 一生，不止一種答案

以 Persona 5 Royal 視覺語彙為靈感的獨立書籍宣傳網站：繁體中文、原創剪貼字標、紅黑斜切、歷史影像及互動導讀。

線上網站：https://chiang-history-dossier.sugaryhaven4.chatgpt.site
線上網站沿用原有存取設定。

## 本機預覽

無需安裝依賴或建置。使用 Python 3：

```sh
python -m http.server 4173 --directory dist
```

開啟 http://localhost:4173 。也可將 `dist/` 交給任意靜態網站服務。

## 內容與互動

- 六個主題欄目，五個生平節點及八張歷史照片
- 開羅會議人物標註、家庭關係、二十四章目錄及原創導讀
- 逐字撞入、斜線切入、分層選單、照片切換及懸停效果
- 鍵盤操作、原生對話框、焦點返回及減少動態效果模式
- 音效預設關閉，可由使用者開啟

## 來源與使用

書籍資訊及照片出處在網站的「內容與圖片來源」中列明。歷史照片不是本書內頁；本站導讀非書中摘錄。首頁人物為原創插畫。書封保留出版品原樣，因此封面文字與網站的繁體界面不同。

展示字體 Dela Gothic One、Noto Sans CJK TC、Anton 的许可見 `dist/assets/FONT-LICENSES.txt`。其他圖片依各來源的授權條件使用；本倉庫不對第三方素材另行授權。

研究與檢查紀錄：`research/P5R-ART-DIRECTION.md`、`research/HISTORICAL-IMAGES.json`、`research/QA.md`。
