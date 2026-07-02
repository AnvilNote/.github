# AnvilNote

**Languages:** [繁體中文](README.zh-TW.md) | **English** | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | [Русский](README.ru.md)

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Electron](https://img.shields.io/badge/Electron-Desktop-black?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)

AnvilNote is an offline-first writing and note-taking app for long-form notes, lecture handouts, reports, and academic documents.

It provides a Notion-like writing experience, but focuses more on structured document export, templates, fonts, formulas, code blocks, and PDF generation.

## Why AnvilNote

- **Offline-first by default.** Your notes live on your machine, not behind a required network connection.
- **No login required for local desktop use.** Open the app and start writing.
- **Designed for long-form writing and structured documents** — lecture notes, reports, academic papers — not just short notes.
- **Formulas, code blocks, templates, and PDF export** are first-class, not bolted on.
- **Built around Typst-based document rendering** for fast, high-quality PDF output.
- **The desktop app bundles required tooling**, so users do not need to install Node.js or Typst separately.

## Repositories

AnvilNote is organized as multiple repositories, not a monorepo.

| Repository | Purpose | Status |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | Main project overview, documentation, architecture, roadmap, and source build guide | Planned |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | Editor, document UI, template selection, and web interface | Planned / internal |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | Local API, SQLite database, document storage, and export endpoints | Planned / internal |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | Typst-based PDF rendering, templates, fonts, and document compilation | Planned / internal |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | DOCX export pipeline | Planned / internal |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Electron desktop shell, bundled sidecars, packaging, installers, and release builds | Public preview |

## Download

The desktop app is available from:

**https://github.com/AnvilNote/anvilnote-desktop/releases**

## Current status

AnvilNote is in early development. Some repositories listed above are internal or not yet public while core functionality is being built out. The desktop app is in public preview; other repositories will open up as they reach a stable enough state to support external contributors.

## Contributing

Once [AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote) is public, start there for project overview, architecture, and contribution guidelines.

Desktop packaging, installer, and release issues belong in [AnvilNote/anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop).

See the `.github` repository's [CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md) for the full organization-wide contribution guide.
