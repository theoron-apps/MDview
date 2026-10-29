<p align="center">
  <img src="assets/icon.png" width="128" alt="mdview icon">
</p>

<h1 align="center">mdview</h1>

<p align="center">A minimal Markdown reader and editor for macOS · by <a href="https://github.com/theoron-apps">Theoron</a></p>

<p align="center">
  <a href="https://github.com/theoron-apps/mdview/releases"><img src="https://img.shields.io/badge/pre--release-0.2.3-0A84FF?style=flat-square" alt="pre-release 0.2.3"></a>
  <a href="https://github.com/theoron-apps/mdview/releases"><img src="https://img.shields.io/github/downloads/theoron-apps/mdview/total?style=flat-square&label=downloads&color=30D158&logo=github&logoColor=white" alt="downloads"></a>
  <img src="https://img.shields.io/badge/macOS-13%2B-1C1C1E?style=flat-square&logo=apple&logoColor=white" alt="macOS 13+">
  <a href="https://t.me/TheoronApps"><img src="https://img.shields.io/badge/news-@TheoronApps-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

<p align="center">
  <a href="https://github.com/theoron-apps/mdview/releases"><b>Download pre-release</b></a> ·
  English · <a href="README.ru.md">Русский</a> · <a href="README.uk.md">Українська</a>
</p>

<p align="center">
  <img src="assets/workspace.png" width="900" alt="mdview with Markdown source and a live preview side by side">
</p>

---

## Features

Open a Markdown file from Finder in a lightweight reader. When you want to edit, choose **Open in mdview** to move into the full workspace.

- **Three modes:** focused reading, Markdown source, or an editor beside a live preview.
- **Your documents, together:** tabs, folders, recent files, an outline, and document search.
- **Useful editing tools:** H1–H6 headings, bold, italic, links, images, code, lists, quotes, tables, and undo/redo.
- **Rich Markdown, offline:** tables, task lists, syntax highlighting, Mermaid diagrams, and KaTeX formulas.
- **Make it yours:** light and dark themes, reading fonts and widths, four formatting toolbar styles, and Liquid Glass on supported macOS versions.
- **Small comforts:** autosave for existing files, draft recovery, checks for external file changes, and PDF export through the macOS print dialog.
- **Three interface languages:** Ukrainian, Russian, and English.

## Install

1. Open [Releases](https://github.com/theoron-apps/mdview/releases) and choose a pre-release.
2. Download **mdview-0.2.3.dmg**, open it, and drag **mdview** to **Applications**.
3. Eject the disk image and open mdview from Applications.

To update, quit mdview and replace the existing app in Applications. In-app update checking is not connected in this build; download new versions from Releases.

**This build is ad-hoc signed and is not notarized by Apple.** macOS may block its first launch. If you trust the download, consult [Apple’s instructions for opening an unverified app](https://support.apple.com/en-au/102445). A SHA-256 checksum is included with the release.

## Requirements

**0.2.3 · build 5 · pre-release.** Features and appearance may change. Keep backups of important documents and report problems through [Issues](https://github.com/theoron-apps/mdview/issues), including your macOS version, app version, and steps to reproduce.

| | Support |
| --- | --- |
| macOS target | macOS 13 or later |
| Processors | Universal app: Apple Silicon and Intel |
| Liquid Glass | macOS 26 or later; system materials on earlier versions |
| Validation | Apple Silicon and x86_64 under Rosetta on the development Mac |
| Still unverified | Older macOS versions, a physical Intel Mac, and installation on a clean Mac |

The editor works with Markdown source. Task checkboxes are changed in the source; MDX does not execute JSX components.

## Privacy

Your documents stay in the folders you choose. Markdown rendering works without a network connection. Remote images are off by default and can be enabled in Settings. mdview does not upload your documents or collect analytics.

Find the version history inside **Settings → What’s New**.

## About this repository

This repository contains the project page and downloadable releases. The application source code is not published, and no open-source license is granted for mdview. Bundled third-party components retain their own licenses; see [Third-party notices](THIRD_PARTY.md).

## Contact

News and support — Telegram [@TheoronApps](https://t.me/TheoronApps).
