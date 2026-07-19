# AnvilNote

**Languages:** **繁體中文** | [English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [Русский](README.ru.md)

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)

AnvilNote 是一款離線優先的寫作與筆記應用程式，適合長篇筆記、課堂講義、
報告，以及學術或技術文件。它使用 Tiptap 視覺化編輯器，並支援專業 PDF 與
可繼續編輯的 DOCX 輸出。

## 專案重點

- 核心編輯與文件輸出可離線使用；
- 不需帳號即可在桌面版整理長篇結構化文件；
- 支援數學公式、程式碼、表格、範本、Callout、Proof/QED 與題目；
- 透過 Typst 產生套用範本的 PDF；
- DOCX 支援 Word 原生公式，目標應用程式支援 OMML 時可繼續編輯；
- 一般桌面版使用不需另外安裝執行工具；
- 可選用 Smart Mode，並使用自己的 OpenAI API Key。

Smart Mode 在 OpenAI Build Week 期間開發，Codex 參與主要實作與整合工作。
GPT-5.6 模型負責結構化文件產生、附件輔助產生與選取文字改寫。

## 主要儲存庫

| 儲存庫 | 用途 | 狀態 |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | 專案總覽、架構、路線圖與文件 | 公開文件 |
| [anvilnote-ai-writer](https://github.com/AnvilNote/anvilnote-ai-writer) | Smart Mode contracts、AST、prompts、policies、pricing 與 provider adapters | 開發中 |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | Tiptap 編輯器、文件介面、範本、輸出與 Smart Mode 介面 | 開發中 |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | 文件服務、輸出、附件文字擷取與 AI 應用服務 | 開發中 |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | Typst PDF 轉換、範本與字型 | 支援套件 |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | Tiptap 至 DOCX 轉換 | 支援套件 |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Electron 執行環境、封裝、安裝程式與 release | 公開預覽版 |
| [anvilnote-charts](https://github.com/AnvilNote/anvilnote-charts) | 函數圖形規格編譯器 | 支援套件 |

## 下載

桌面版請由 [AnvilNote Desktop Releases](https://github.com/AnvilNote/anvilnote-desktop/releases)
取得。核心編輯與文件輸出可離線使用；Smart Mode 為選用功能，使用時需要
網路連線與使用者自己的 OpenAI API Key。

## 參與貢獻

請先閱讀 [AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote) 的專案總覽
與儲存庫說明。組織層級的貢獻方式請參閱
[CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md)。
