# TYPO3 TypeScript Sources

[![Sync and Publish](https://github.com/maikschneider/typo3-typescript-sources/actions/workflows/sync-and-publish.yml/badge.svg)](https://github.com/maikschneider/typo3-typescript-sources/actions/workflows/sync-and-publish.yml)
[![npm version](https://badge.fury.io/js/typo3-typescript-sources.svg)](https://www.npmjs.com/package/typo3-typescript-sources)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

This repository contains the TypeScript sources from the TYPO3 Core, automatically extracted and published to npm.

## 📦 Installation

```bash
# Current LTS (v14)
npm install typo3-typescript-sources

# v13
npm install typo3-typescript-sources@v13-latest

# TYPO3 main (development, not published to npm)
npm install github:maikschneider/typo3-typescript-sources#main
```

## 🔍 Source

- **Original Repository:** [TYPO3/typo3](https://github.com/TYPO3/typo3)
- **Source Path:** `Build/Sources/TypeScript/`
- **Current TYPO3 Version:** `main@1f97877e0077 (15.0.0-dev)`

## 🌿 Branches

| Branch   | TYPO3 Source         | npm tag      |
|----------|----------------------|--------------|
| `main`   | `main` (every commit) | –            |
| `v14.x`  | v14.x releases       | `latest`     |
| `v13.x`  | v13.x releases       | `v13-latest` |

## 📝 License

This package maintains the same license as TYPO3 Core: **GPL-2.0-or-later**

## 🤖 Automation

This repository is automatically synchronized with TYPO3 Core releases via GitHub Actions.

## ⚠️ Note

This is an unofficial split package maintained by [@maikschneider](https://github.com/maikschneider).
For official TYPO3 packages, please refer to the [TYPO3 Core repository](https://github.com/TYPO3/typo3).
