# readmeter

Chrome extension that tracks reading time per tab

Built for my own use; public in case it helps someone.

## Features

- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- No remote calls, everything stays local

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```
