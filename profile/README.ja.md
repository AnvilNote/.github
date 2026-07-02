# AnvilNote

**Languages:** [繁體中文](README.zh-TW.md) | [English](README.md) | **日本語** | [한국어](README.ko.md) | [ไทย](README.th.md) | [Русский](README.ru.md)

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Electron](https://img.shields.io/badge/Electron-Desktop-black?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)

AnvilNote は、長文のノート、講義資料、レポート、学術文書向けに設計された、オフラインファーストの執筆・ノートアプリです。

Notion に似た執筆体験を提供しつつ、構造化されたドキュメントのエクスポート、テンプレート、フォント、数式、コードブロック、PDF 生成により重点を置いています。

## AnvilNote の特長

- **デフォルトでオフラインファースト。** ノートはあなたのマシン上に保存され、常時ネットワーク接続を必要としません。
- **ローカルデスクトップ利用にログイン不要。** アプリを開いてすぐに書き始められます。
- **長文執筆と構造化ドキュメントのために設計。** 短いメモだけでなく、講義ノート、レポート、学術論文にも対応します。
- **数式・コードブロック・テンプレート・PDF エクスポート**は後付けではなく、中核機能です。
- **Typst ベースのドキュメントレンダリング**により、高速で高品質な PDF 出力を実現します。
- **デスクトップアプリは必要なツールをバンドル済み**のため、Node.js や Typst を別途インストールする必要はありません。

## リポジトリ

AnvilNote はモノレポではなく、複数のリポジトリで構成されています。

| リポジトリ | 目的 | 状態 |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | プロジェクト概要、ドキュメント、アーキテクチャ、ロードマップ、ソースビルドガイド | 計画中 |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | エディタ、ドキュメント UI、テンプレート選択、Web インターフェース | 計画中 / 内部 |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | ローカル API、SQLite データベース、ドキュメントストレージ、エクスポートエンドポイント | 計画中 / 内部 |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | Typst ベースの PDF レンダリング、テンプレート、フォント、ドキュメントコンパイル | 計画中 / 内部 |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | DOCX エクスポートパイプライン | 計画中 / 内部 |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Electron デスクトップシェル、バンドルされたサイドカー、パッケージング、インストーラー、リリースビルド | 公開プレビュー |

## ダウンロード

デスクトップアプリはこちらから入手できます。

**https://github.com/AnvilNote/anvilnote-desktop/releases**

## 現在の状況

AnvilNote は開発初期段階にあります。上記の一部リポジトリは内部利用のみ、または未公開のまま、コア機能の構築が進められています。デスクトップアプリは公開プレビュー中で、他のリポジトリも外部からの貢献を受け入れられる状態が整い次第、順次公開されます。

## コントリビュート

[AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote) が公開されたら、まずそちらでプロジェクト概要、アーキテクチャ、コントリビューションガイドを確認してください。

デスクトップのパッケージング、インストーラー、リリースに関する問題は [AnvilNote/anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) へ報告してください。

組織全体のコントリビューションガイドは、`.github` リポジトリの [CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md) を参照してください。
