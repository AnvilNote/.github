# AnvilNote

**Languages:** **繁體中文** | [English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [Русский](README.ru.md)

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Electron](https://img.shields.io/badge/Electron-Desktop-black?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)

AnvilNote 是一款離線優先的寫作與筆記應用程式，專為長篇筆記、課堂講義、報告與學術文件而設計。

它提供類似 Notion 的寫作體驗，但更著重於結構化文件匯出、範本、字型、公式、程式碼區塊與 PDF 產生。

## 為什麼選擇 AnvilNote

- **預設離線優先。** 筆記存在你自己的裝置上，不需要仰賴網路連線。
- **本機桌面版無需登入。** 開啟應用程式即可開始寫作。
- **為長篇寫作與結構化文件而設計** —— 課堂筆記、報告、學術論文，不只是短筆記。
- **公式、程式碼區塊、範本與 PDF 匯出**是核心功能，而非事後加上的附加項目。
- **以 Typst 為核心的文件排版引擎**，提供快速且高品質的 PDF 輸出。
- **桌面版已內建所需工具**，使用者不需要另外安裝 Node.js 或 Typst。

## 儲存庫

AnvilNote 由多個儲存庫組成，並非單一 monorepo。

| 儲存庫 | 用途 | 狀態 |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | 專案總覽、文件、架構、路線圖與原始碼建置指南 | 規劃中 |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | 編輯器、文件介面、範本選擇與網頁介面 | 規劃中 / 內部 |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | 本機 API、SQLite 資料庫、文件儲存與匯出端點 | 規劃中 / 內部 |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | 以 Typst 為基礎的 PDF 排版、範本、字型與文件編譯 | 規劃中 / 內部 |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | DOCX 匯出流程 | 規劃中 / 內部 |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Electron 桌面殼層、內建 sidecar、封裝、安裝程式與發佈建置 | 公開預覽版 |

## 下載

桌面版可由此取得：

**https://github.com/AnvilNote/anvilnote-desktop/releases**

## 目前狀態

AnvilNote 目前處於早期開發階段。上方部分儲存庫仍為內部或尚未公開，核心功能仍在建置中。桌面版已進入公開預覽，其他儲存庫將於狀態穩定、足以支援外部貢獻者時陸續開放。

## 參與貢獻

一旦 [AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote) 公開，請從該處開始了解專案總覽、架構與貢獻指南。

桌面版封裝、安裝程式與發佈相關問題請回報至 [AnvilNote/anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop)。

完整的組織層級貢獻指南請參閱 `.github` 儲存庫的 [CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md)。
