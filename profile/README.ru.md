# AnvilNote

**Languages:** [繁體中文](README.zh-TW.md) | [English](README.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [ไทย](README.th.md) | **Русский**

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Electron](https://img.shields.io/badge/Electron-Desktop-black?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)

AnvilNote — это офлайн-ориентированное приложение для письма и заметок, предназначенное для развёрнутых заметок, конспектов лекций, отчётов и академических документов.

Оно предлагает опыт письма, похожий на Notion, но с большим упором на структурированный экспорт документов, шаблоны, шрифты, формулы, блоки кода и генерацию PDF.

## Почему AnvilNote

- **Офлайн-режим по умолчанию.** Ваши заметки хранятся на вашем устройстве, а не требуют постоянного подключения к сети.
- **Не требует входа в систему для локального использования на десктопе.** Откройте приложение и начните писать.
- **Создано для развёрнутого письма и структурированных документов** — конспектов лекций, отчётов, академических работ, а не только коротких заметок.
- **Формулы, блоки кода, шаблоны и экспорт в PDF** — это базовые возможности, а не дополнения.
- **Рендеринг документов на основе Typst** обеспечивает быстрый и качественный вывод PDF.
- **Десктопное приложение включает все необходимые инструменты**, поэтому пользователям не нужно отдельно устанавливать Node.js или Typst.

## Репозитории

AnvilNote состоит из нескольких репозиториев, а не единого монорепозитория.

| Репозиторий | Назначение | Статус |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | Обзор проекта, документация, архитектура, дорожная карта и руководство по сборке из исходного кода | Планируется |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | Редактор, интерфейс документов, выбор шаблонов и веб-интерфейс | Планируется / внутренний |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | Локальный API, база данных SQLite, хранение документов и конечные точки экспорта | Планируется / внутренний |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | Рендеринг PDF на основе Typst, шаблоны, шрифты и компиляция документов | Планируется / внутренний |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | Конвейер экспорта в DOCX | Планируется / внутренний |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Оболочка десктопного приложения на Electron, встроенные sidecar-компоненты, упаковка, установщики и релизные сборки | Публичное превью |

## Загрузка

Десктопное приложение доступно здесь:

**https://github.com/AnvilNote/anvilnote-desktop/releases**

## Текущий статус

AnvilNote находится на ранней стадии разработки. Некоторые из перечисленных выше репозиториев пока являются внутренними или ещё не опубликованы, пока идёт разработка основной функциональности. Десктопное приложение находится в публичном превью; остальные репозитории будут открываться по мере готовности к поддержке внешних контрибьюторов.

## Участие в разработке

Как только [AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote) станет публичным, начните оттуда — там будет обзор проекта, архитектура и руководство по участию.

Вопросы, связанные с упаковкой, установщиками и релизами десктопной версии, следует направлять в [AnvilNote/anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop).

Полное руководство по участию на уровне организации см. в [CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md) в репозитории `.github`.
