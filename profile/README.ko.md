# AnvilNote

**Languages:** [繁體中文](README.zh-TW.md) | [English](README.md) | [日本語](README.ja.md) | **한국어** | [ไทย](README.th.md) | [Русский](README.ru.md)

[![Release](https://img.shields.io/github/v/release/AnvilNote/anvilnote-desktop?style=for-the-badge&label=Release&color=black)](https://github.com/AnvilNote/anvilnote-desktop/releases/latest)
[![Downloads](https://img.shields.io/badge/Downloads-GitHub-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple-black?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20AppImage-black?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/AnvilNote/anvilnote-desktop/releases)
[![Electron](https://img.shields.io/badge/Electron-Desktop-black?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)

AnvilNote는 장문의 노트, 강의 자료, 보고서, 학술 문서를 위한 오프라인 우선 작성 및 노트 앱입니다.

Notion과 유사한 작성 경험을 제공하면서도, 구조화된 문서 내보내기, 템플릿, 폰트, 수식, 코드 블록, PDF 생성에 더 중점을 둡니다.

## AnvilNote를 선택하는 이유

- **기본적으로 오프라인 우선.** 노트는 사용자의 기기에 저장되며, 항상 네트워크 연결이 필요하지 않습니다.
- **로컬 데스크톱 사용 시 로그인 불필요.** 앱을 열고 바로 작성을 시작할 수 있습니다.
- **장문 작성과 구조화된 문서를 위한 설계** — 짧은 메모뿐 아니라 강의 노트, 보고서, 학술 논문에도 적합합니다.
- **수식, 코드 블록, 템플릿, PDF 내보내기**는 부가 기능이 아니라 핵심 기능입니다.
- **Typst 기반 문서 렌더링**으로 빠르고 고품질의 PDF 출력을 제공합니다.
- **데스크톱 앱에는 필요한 도구가 번들로 포함**되어 있어 Node.js나 Typst를 별도로 설치할 필요가 없습니다.

## 저장소

AnvilNote는 단일 모노레포가 아니라 여러 저장소로 구성되어 있습니다.

| 저장소 | 목적 | 상태 |
| --- | --- | --- |
| [anvilnote](https://github.com/AnvilNote/anvilnote) | 프로젝트 개요, 문서, 아키텍처, 로드맵 및 소스 빌드 가이드 | 계획 중 |
| [anvilnote-web](https://github.com/AnvilNote/anvilnote-web) | 에디터, 문서 UI, 템플릿 선택 및 웹 인터페이스 | 계획 중 / 내부 |
| [anvilnote-api](https://github.com/AnvilNote/anvilnote-api) | 로컬 API, SQLite 데이터베이스, 문서 저장 및 내보내기 엔드포인트 | 계획 중 / 내부 |
| [anvilnote-renderer](https://github.com/AnvilNote/anvilnote-renderer) | Typst 기반 PDF 렌더링, 템플릿, 폰트 및 문서 컴파일 | 계획 중 / 내부 |
| [anvilnote-docx-exporter](https://github.com/AnvilNote/anvilnote-docx-exporter) | DOCX 내보내기 파이프라인 | 계획 중 / 내부 |
| [anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop) | Electron 데스크톱 셸, 번들된 사이드카, 패키징, 설치 프로그램 및 릴리스 빌드 | 공개 프리뷰 |

## 다운로드

데스크톱 앱은 다음에서 받을 수 있습니다.

**https://github.com/AnvilNote/anvilnote-desktop/releases**

## 현재 상태

AnvilNote는 초기 개발 단계에 있습니다. 위에 나열된 일부 저장소는 아직 내부용이거나 공개되지 않았으며, 핵심 기능이 계속 개발되고 있습니다. 데스크톱 앱은 공개 프리뷰 상태이며, 다른 저장소들은 외부 기여자를 지원할 수 있을 만큼 안정화되는 대로 순차적으로 공개될 예정입니다.

## 기여하기

[AnvilNote/anvilnote](https://github.com/AnvilNote/anvilnote)가 공개되면, 프로젝트 개요, 아키텍처, 기여 가이드는 그곳에서 먼저 확인하세요.

데스크톱 패키징, 설치 프로그램, 릴리스 관련 문제는 [AnvilNote/anvilnote-desktop](https://github.com/AnvilNote/anvilnote-desktop)에 등록해 주세요.

조직 전체의 기여 가이드는 `.github` 저장소의 [CONTRIBUTING.md](https://github.com/AnvilNote/.github/blob/main/CONTRIBUTING.md)를 참고하세요.
