# Flare RPG 繁體中文網頁版

將 [Flare: Empyrean Campaign](https://github.com/flareteam/flare-game) 編譯為純靜態網頁版，供自架使用。

## 來源

- 引擎：https://github.com/flareteam/flare-engine (GPLv3)
- 遊戲資料：https://github.com/flareteam/flare-game (CC-BY-SA 3.0)
- 繁中翻譯：內含於上游（`data.zh_TW.po` / `engine.zh_TW.po`）

## 授權聲明

本專案僅包含**建置設定檔**，不含遊戲原始碼或美術資源。

- Flare 引擎程式碼：GPLv3
- 遊戲資料與美術：CC-BY-SA 3.0
- 繁體中文翻譯：CC-BY-SA 3.0（衍生自上游翻譯）

編譯產物為上述專案之衍生作品，散布時須保留對應授權聲明。

## 使用方式

1. 到 Actions 頁面點「Run workflow」
2. 等待編譯完成（約 20-40 分鐘）
3. 下載 artifact（`flare-web`）
4. 解壓後放到網站目錄即可

## 部署需求

- 靜態檔案伺服器（Apache/Nginx）
- `.wasm` 需以 `application/wasm` 提供
- 建議啟用 gzip 壓縮

## 備註

本 repo 由自動化腳本建立。