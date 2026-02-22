# 🔧 RustCentral Editor

[![Sponsor](https://img.shields.io/badge/Sponsor-DeltaDinizzz-EA4AAA?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/DeltaDinizzz)

## 📜 License

RustCentral Editor
Copyright (c) 2025 DeltaDinizzz. All Rights Reserved.

This software and associated documentation and materials (the "Work") are
proprietary and confidential. No license or right is granted to use, copy,
modify, distribute, or create derivative works of the Work. Unauthorized
reproduction, distribution, or use is strictly prohibited.

All rights reserved.



### 🔧**Configure your Rust server plugins with ease.**

Desktop app for Rust server admins: edit BetterLoot, BetterTC, Kits, HUD and more — without touching JSON. Sign in with your [RustPlugins](https://rustcenter.org) account and manage everything in one place.

---

## ✨ Features

- **📁 Visual editor** — BetterLoot, BetterTC, Kits, HUD Editor, custom expansions
- **🔐 RustPlugins account** — Sign in with rustcenter.org; entitlements and subscription sync
- **💾 Safe edits** — Automatic backup before save; full JSON structure preserved
- **🔄 Auto-updates** — Built-in updater when a new version is released
- **🪟 Windows** — MSI and NSIS installers (portable setup)

---

## 🚀 Quick start

### Prerequisites

- **Node.js** (LTS)
- **Rust** + Cargo
- **PowerShell 7+** (for setup scripts)

### Setup & run

```powershell
.\OpenProjectSTART.ps1
```

Or manually:

```powershell
.\setup.ps1
npm run tauri dev
```

### Build installers

```powershell
npm run tauri:build
```

Artifacts: `src-tauri/target/release/bundle/` (MSI, NSIS, updater zips).

---

## 📂 Project structure

| Path | Description |
|------|-------------|
| `src/` | Frontend — React, TypeScript, Vite |
| `src-tauri/` | Backend — Rust (Tauri), native APIs, auth, updater |
| `scripts/` | Build helpers (e.g. `tauri-build-with-env.js`, config generation) |

---

## 🛠 Tech stack

- **Frontend:** React 18, TypeScript, Vite, Ant Design, Zustand, XState
- **Desktop:** Tauri 2 (Rust)
- **Auth:** OAuth2 PKCE with [rustcenter.org](https://rustcenter.org); JWT + entitlements API

---

## ❤️ Support this project

If RustCentral Editor helps your server workflow, you can support ongoing development:

- GitHub Sponsors: [@DeltaDinizzz](https://github.com/sponsors/DeltaDinizzz)

---
