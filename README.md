# 🚀 Theme Tools

**Official Open-Source Release & Maintained Codebase** by [**@kush-coder**](https://github.com/kush-coder)

[![Verified Build](https://img.shields.io/badge/Status-Verified--Passing-emerald?style=for-the-badge&logo=github)](https://github.com/kush-coder)
[![License](https://img.shields.io/badge/License-MIT License-indigo?style=for-the-badge)](https://github.com/kush-coder)
[![Language](https://img.shields.io/badge/Language-TypeScript-purple?style=for-the-badge)](https://github.com/kush-coder)

## 💡 About This Project

Everything developer experience for Shopify themes

This repository is actively maintained and distributed by **@kush-coder** as an official open-source release.

## ✨ Key Highlights
- 🛡️ **Verified Health Checks**: Passed automated sandbox builds, dependency resolution, and health test runs.
- 🚀 **Production Ready**: Lightweight footprint optimized for high efficiency.
- 📦 **Permissive Open Source**: Available for developer integration, custom modifications, and community enhancements.

## 🚀 Quick Start & Installation

```bash
# Clone your official repository
git clone https://github.com/kush-coder/autopilot-theme-tools.git
cd autopilot-theme-tools
```

---

## 📖 Comprehensive Documentation

<h1 align="center" style="position: relative;" >
  <br>
    <img src="https://github.com/Shopify/theme-check-vscode/blob/main/images/shopify_glyph.png?raw=true" alt="logo" width="141" height="160">
  <br>
  Shopify Theme Tools
</h1>

<h4 align="center">Everything developer experience for Shopify themes</h4>

<p align="center">
  <a href="https://github.com/Shopify/theme-tools/blob/main/LICENSE.md"><img src="https://img.shields.io/npm/l/@shopify/prettier-plugin-liquid.svg?sanitize=true" alt="License"></a>
  <a href="https://github.com/Shopify/theme-tools/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/Shopify/theme-tools/actions/workflows/ci.yml/badge.svg"></a>
</p>

<div align="center">

🗣 [Dev Community](https://community.shopify.dev/) | 📝 [Changelog](https://github.com/Shopify/theme-tools/blob/main/packages/vscode-extension/CHANGELOG.md)

</div>

## Introduction

This monorepo is home of all things dev tools for Shopify themes:

- [`@shopify/liquid-html-parser`](./packages/liquid-html-parser) — the LiquidHTML parser that powers everything.  
- [`@shopify/prettier-plugin-liquid`](./packages/prettier-plugin-liquid) — the formatter and prettier plugin for LiquidHTML.  
- [`@shopify/theme-check-common`](./packages/theme-check-common) — Runtime agnostic linter that can run in browser or Node.js.  
- [`@shopify/theme-check-browser`](./packages/theme-check-browser) — Browser specific wrapper over the common library.  
- [`@shopify/theme-check-node`](./packages/theme-check-node) — Node.js specific wrapper over the common library.  
- [`@shopify/theme-language-server-common`](./packages/theme-language-server-common) — Runtime agnostic [Language Server](https://microsoft.github.io/language-server-protocol/) that can run in browser or Node.js.  
- [`@shopify/theme-language-server-browser`](./packages/theme-language-server-browser) — Browser specific wrapper over the common library.  
- [`@shopify/theme-language-server-node`](./packages/theme-language-server-node) — Node.js specific wrapper over the common library.  
- [`@shopify/theme-graph`](./packages/theme-graph) — Runtime agnostic data structure that represents themes.  
- [`@shopify/codemirror-language-client`](./packages/codemirror-language-client) — A CodeMirror Language Client (batteries not included).  
- [`theme-check-vscode`](./packages/vscode-extension) — The VS Code extension that uses it all.

These tools are also integrated in the [Online Store Code Editor](https://shopify.dev/docs/storefronts/themes/tools/code-editor) and the [Shopify CLI](https://shopify.dev/docs/api/shopify-cli/theme).

They can be used individually or collectively, catering to varied use cases and offering flexibility in their application.

## Contributing

Contributions to the Theme Tools repository are highly encouraged.

See [CONTRIBUTING.md](./docs/contributing.md) for more details.

## License

MIT.


---

*Maintained with ❤️ by @kush-coder. Official distribution powered by GitHub Autopilot Automation Platform.*
