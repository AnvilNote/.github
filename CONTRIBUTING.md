# Contributing to AnvilNote

Thank you for your interest in contributing. This guide covers organization-wide conventions that apply across all AnvilNote repositories.

## Multiple repositories, not a monorepo

AnvilNote is split across several repositories. Use the map below to find the right place for your issue or pull request before opening it.

| Repository | Use for |
| --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | Project overview, architecture, roadmap, source build guide |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | Editor, document UI, template selection |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | Local API, SQLite storage, export endpoints |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | Typst-based PDF rendering, templates, fonts, document compilation |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | DOCX export |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Desktop packaging, installers, signing, notarization, release builds |

If you are not sure which repository applies, open the issue in [anvilnote](https://github.com/AnvilNote/anvilnote) and it will be redirected.

## Before you start

- For large architectural changes, open an issue first and describe the change before writing code. This avoids wasted work if the direction needs to shift.
- For small fixes (typos, small bugs, minor doc corrections), a pull request without a prior issue is fine.

## Pull requests

- Keep pull requests focused on a single change. Avoid mixing unrelated fixes, refactors, and features in one PR.
- Reference the related issue where one exists.
- Use the pull request template; fill in the sections that apply.

## Commit messages

Use conventional commit style where possible:

- `feat:` a new feature
- `fix:` a bug fix
- `docs:` documentation only changes
- `refactor:` code change that neither fixes a bug nor adds a feature
- `chore:` maintenance work that doesn't change behavior
- `build:` changes to the build system or dependencies
- `ci:` changes to CI configuration or scripts

Example: `fix: correct footnote numbering in PDF export`

## Reporting security issues

Do not open a public issue for a security vulnerability. See [SECURITY.md](SECURITY.md).
