# Spanish Learning Panel

從零開始的西語 A1 學習面板，包含句型卡、搜尋、章節篩選、學習狀態追蹤，以及瀏覽器語音播放。

## Files

- `spanish-learning-panel.html`：單檔互動面板，直接用瀏覽器開啟即可。
- `西語從零開始_A1句型資料庫.csv`：A1 起步句型資料，可匯入 Notion 或 Google Sheets。
- `西語_CH3房屋單字.csv`：從手寫筆記整理的 CH3 房屋相關單字。
- `日文從零開始_N5文法資料庫.csv`：日文 N5 文法資料庫。
- `日文從零開始_每日進度設計.md`：日文每日學習進度設計。

## Run Locally

```bash
python3 -m http.server 8766 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:8766/spanish-learning-panel.html
```

The audio buttons use the browser's built-in `speechSynthesis` API with Spanish voice settings.
