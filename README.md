# Yuntech-Extract-PDF-URL
教授在 E-Class 上提供 PPT 但沒開下載選項 所以弄了個套件自己抓檔案
---
發布於 [greasyfork](https://greasyfork.org/zh-TW/scripts/528228-yuntech-extract-pdf-url/)

這是用 GPT 產生的腳本，起因是教授在 EClass 上提供 PPT 但沒開下載選項
所以弄了個套件自己抓檔案


這個油猴腳本的主要功能描述如下：
功能簡介
Yuntech PDF Downloader 是一款適用於 雲林科技大學 eClass 平台的 油猴 (Tampermonkey) 擴充腳本，
它能夠 自動檢測 PDF 預覽頁面，並在 右下角生成可下載按鈕，讓使用者輕鬆取得 PDF 檔案。
功能特色

✅ 自動監聽 PDF Viewer：當使用者點擊課程內的 PDF 預覽按鈕時，腳本會自動偵測是否開啟 PDF Viewer。
✅ 即時解析 PDF 連結：從 PDF Viewer 擷取實際的下載 URL，無需手動查找。
✅ 右下角下載按鈕：自動在畫面 右下角 顯示「📥 下載 PDF」按鈕。
✅ 美觀與互動效果：

懸停時變色 (由 #28a745 變 #218838)
懸停時放大 (scale(1.1))
陰影與滑順過渡動畫 (box-shadow, transition)
✅ 支援 eClass Yuntech 平台：針對雲科大 eClass 環境優化，無須手動修改代碼。

使用方式

安裝油猴 (Tampermonkey) 擴充功能（適用於 Chrome、Firefox、Edge）。
新增此腳本，存檔並啟用。
前往 eClass Yuntech 課程網站，點擊 PDF 預覽，右下角即會顯示「下載 PDF」按鈕。

這款腳本 不會修改原始頁面內容，僅會在 PDF 預覽時新增一個可下載的按鈕，確保使用體驗流暢無干擾！🚀
