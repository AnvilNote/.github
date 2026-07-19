# AnvilNote

**Languages:** [繁體中文](README.zh-TW.md) | **English** | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [Русский](README.ru.md)

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)

AnvilNote is an offline-first writing and note-taking application for long-form
notes, lecture handouts, reports, and academic or technical documents. It uses
a Tiptap visual editor and supports professional PDF and editable DOCX export.

## What it focuses on

- offline core editing and document export;
- long-form, structured documents without a required account;
- math, code, tables, templates, Callouts, Proof/QED, and Questions;
- template-driven PDF output through Typst;
- DOCX output with Word-editable equations where OMML is supported;
- bundled Desktop tooling for normal use;
- optional Smart Mode with the user's own OpenAI API key.

Smart Mode was developed during OpenAI Build Week with Codex supporting the
main implementation and integration work. GPT-5.6 models provide structured
composition, attachment-assisted composition, and selected-text rewriting.

## Main repositories

| Repository | Purpose | Status |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | Project overview, architecture, roadmap, and documentation | Public documentation |
| [anvilnote-ai-writer](https://github.com/AnvilNote/anvilnote-ai-writer) | Smart Mode contracts, AST, prompts, policies, pricing, and provider adapters | Active development |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | Tiptap editor, document UI, templates, exports, and Smart Mode UI | Active development |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | Document services, exports, attachment extraction, and AI application services | Active development |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | Typst PDF conversion, templates, and fonts | Supporting package |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | Tiptap-to-DOCX conversion | Supporting package |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Electron runtime, packaging, installers, and releases | Public preview |
| [anvilnote-charts](https://github.com/AnvilNote/anvilnote-charts) | Function-plot specification compiler | Supporting package |

## Download

Get the current desktop release from
[AnvilNote Desktop Releases](https://github.com/AnvilNote/anvilnote-desktop/releases).
Core editing and export work offline. Smart Mode is optional and requires an
internet connection and the user's own OpenAI API key.

## Contributing

Start with [AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote) for the
project overview and repository map. Organization-wide guidance is available in
[CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md).
