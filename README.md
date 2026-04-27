# 星際公民 (Star Citizen) 繁體中文翻譯數據包(用於SCMDB 網頁)

本儲存庫提供為 [SCMDB](https://scmdb.net/) (Star Citizen Mission & Data Browser) 工具製作的 SCMDB 網站，繁體中文翻譯檔案。讓社群玩家能在瀏覽器中以熟悉的語言查看遊戲任務與數據。

## 🚀 快速開始 (如何使用)

若要在 SCMDB 網頁套用此翻譯，請根據您的需求選擇以下方式：

### 1. 訪客快速連結
直接在 SCMDB 網址後方加上參數即可套用（設定會儲存在瀏覽器中）：
```
https://scmdb.net?lang=https://raw.githubusercontent.com/White-PhoN/SCMDB-TEST/refs/heads/main/lang-global-4.7.1-live.11638371.json
```

### 2. SCMDB 帳戶使用者
1. 前往 SCMDB 的 **Settings**。
2. 在 Language URL 欄位貼上本專案的 JSON 檔案直連網址
```
https://raw.githubusercontent.com/White-PhoN/SCMDB-TEST/refs/heads/main/lang-global-4.7.1-live.11638371.json)。
```

## 📊 專案狀態 (最新版本)

* **對應遊戲版本**：4.7.1-live.11638371
* **最後更新日期**：2026-04-24
* **翻譯覆蓋率**：約 94% (2391/2542 鍵值已翻譯)

如何移除
無需帳戶：清除瀏覽器數據，或訪問scmdb.dev?lang=clear
使用帳戶：從設定中移除 URL

## ⚖️ 法律聲明與版權說明 (Declarations)

### 1. 版權歸屬 (Ownership)
* **遊戲數據**：本專案所包含之所有《星際公民》(Star Citizen) 遊戲文本中文皆由***澄清石灰水/everland_3769 提供以及繁體本地化***，目前使用版由本人(PhoN)維護。
* **遊戲數據**：本專案所包含之所有《星際公民》(Star Citizen) 遊戲文本、數據及相關素材之版權均歸 **Cloud Imperium Games (CIG)** 所有。
* **工具來源**：本翻譯檔案係透過 [SCMDB Community Translations](https://github.com/KrovaxCode/SCMDB_LANG) 開放原始碼工具 `build_lang_template.py` 生成。

### 2. 免責聲明 (Disclaimer)
* 本專案為非官方、由社群愛好者自發維護的翻譯作品，與 Cloud Imperium Games 官方無任何關聯。
* **無擔保聲明**：翻譯內容可能包含錯誤或未與最新版本完全同步。開發者對使用本檔案後可能產生的任何顯示異常或不便不負任何責任。

### 3. 翻譯範圍 (Scope)
* **包含範圍**：本翻譯僅針對遊戲內原始數據 (In-game data)，如：任務標題、描述、地點名稱、船艦與物品名稱等。
* **不包含範圍**：SCMDB 網站本身的使用介面（按鈕、選單、篩選器等）將保持英文顯示，這是有意為之的設計，以確保排版與功能的穩定性。

### 4. 開源授權 (License)
本翻譯包之 JSON 結構與生成工具遵循原始專案之授權條款。翻譯文本內容歡迎社群在標註來源的前提下，於其他《星際公民》相關非營利專案中使用。

## 🛠️ 技術細節
本檔案由 `global.ini` 翻譯原始檔轉換而成，自動處理了 `[RANK]`、`[LOCATION]` 等動態權杖 (Token) 的替換作業，大幅提升了中文語境下的閱讀體驗。

## 📬 問題回饋
若您在翻譯內容中發現嚴重錯漏或翻譯建議，歡迎透過 [GitHub Issues] 提交，或在社群群組中與我們聯繫。
