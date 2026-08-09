# ⚡ Campus AI Supercomputer Copilot

> **Zero-Cloud Autonomous AI Agent, Self-Healing Code Repair Engine & Security Auditor for KGiSL Campus Intranet Network**  
> *Architected & Developed by Nandhakumar M. • Head of KGiSL Campus Google Community & Google Student Ambassador*

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Network](https://img.shields.io/badge/network-100%25%20Offline%20Intranet-success.svg)
![Security](https://img.shields.io/badge/security-Zero--Cloud%20Data%20Privacy-green.svg)
![Platform](https://img.shields.io/badge/platform-VS%20Code-007ACC.svg)
![Engine](https://img.shields.io/badge/engine-Google%20Antigravity%202.0-00F2FE.svg)

---

## 📌 Executive Overview

**Campus AI Supercomputer Copilot** is a next-generation autonomous AI pair-programming assistant, self-healing code repair engine, and intranet mesh supercomputer built directly into Visual Studio Code.

Engineered to replicate and exceed **Google Antigravity 2.0, GitHub Copilot, Antigravity IDE, and Claude Code Agentic Skills**, Campus AI Copilot gives students and developers 100% free, unrestricted access to high-tier AI models (`Antigravity 60 RPM Agent`, `Deep Research Pro 500 RPD`, `Gemini 3.1 Flash-Lite`, `Gemini 3.5 Flash-Lite`), self-healing automated execution, and zero-cloud intranet data privacy.

---

## 🚀 Key Feature Benefits & Technical Breakthroughs

| Feature | Feature Benefit & How It Works |
|:---|:---|
| 🤖 **Antigravity Autonomous Agent** | **Zero-Click Project Generation**: Type `/antigravity Create a Quiz App` — the agent autonomously plans sub-tasks, creates directories, writes complete production code, and opens files live in VS Code editor tabs. |
| 🛡️ **Autonomous Self-Healing Repair** | **Zero-Debugging Maintenance**: Runs `node --check` and syntax diagnostics automatically. If a syntax error is detected, the agent catches the exact error traceback, fixes the code, and re-verifies until **100% syntax error-free**. |
| 🧠 **Smart Incremental Code Preservation** | **Zero Code Loss**: Before modifying files, the agent scans existing workspace code (`index.html`, `style.css`, `script.js`, `server.js`). Follow-up prompts (`"add color"`, `"continue"`) **preserve all existing logic** while seamlessly merging new enhancements. |
| 🚀 **Autonomous Server Launcher** | **Instant Live App Execution**: As soon as code is generated & verified, the extension opens a VS Code terminal (`⚡ Campus AI Server`), executes `node server.js`, and provides a clickable `http://localhost:8080` live preview link. |
| ⚙️ **Visual AI Running Indicator** | **Live Telemetry & Control**: Displays a glowing status bar (`⚙️ ⚡ Antigravity AI Agent is running...`), dynamic input placeholders, and a pulsing red stop button (`⏹`) with 1-click query cancellation. |
| 🎨 **1-Click Imagen 4 UI Styling** | **Instant Visual Upgrade**: 1-click prompt toolbar chips (`🎨 Glassmorphism UI`, `⚡ Cyberpunk UI`) apply ultra-modern glassmorphism neon styles and animations directly to `style.css`. |
| 🗳️ **Interactive Question Cards** | **1-Click Decision Alignment**: When design choices or technical decisions arise, the agent renders floating interactive cards (`[ASK_QUESTION]`) for 1-click user selection. |
| 🌐 **Live Deep Web Research Engine** | **Real-Time Knowledge**: `/research` queries live technical documentation (`docs.python.org`, `geeksforgeeks.org`, `github.com`) and generates executive reports with clickable web links (`🌐 Title`). |
| 💻 **P2P Intranet Mesh Cluster Engine** | **Subnet Supercomputing**: Auto-scans local subnet nodes (`172.16.110.x`) on Port 3000, pooling local RAM and VRAM across campus laptops into a shared Intranet AI Mesh cluster. |
| ⌨️ **Real-Time Inline Ghost Text (`Tab`)** | **Sub-300ms Autocomplete**: Suggests single-line and multi-line code completions in `.py`, `.js`, `.java`, `.cpp`, and `.html` files. Press **`Tab`** to accept. |

---

## ⚡ High-Quota Model Pool & Endpoint Routing

Campus AI Copilot connects directly to Google AI Studio's highest-tier quota endpoints with automatic multi-model failover:

- **`🤖 Antigravity Agent`** (`models/antigravity`) • **60 RPM / 100K TPM / 100 RPD**
- **`🔬 Deep Research Pro`** (`Deep Research Pro Preview`) • **500 RPD**
- **`⚡ Gemini 3.1 Flash-Lite`** (`gemini-3.1-flash-lite`) • **15 RPM / 250K TPM / 500 RPD**
- **`⚡ Gemini 3.5 Flash-Lite`** (`gemini-3.5-flash-lite`) • **15 RPM / 250K TPM / 500 RPD**
- **`💻 Local Intranet Mesh`** (`qwen-2.5-coder`) • **Unlimited Local Offline Fallback**

---

## ⌨️ Command & Keyboard Shortcut Reference

| Command / Shortcut | Action |
|:---|:---|
| `/antigravity <prompt>` | Launch Antigravity Autonomous Agent (Project Creation, Code Verification & Server Launch) |
| `/research <topic>` | Launch Multi-Step Deep Web Research with Grounded Citations |
| `/goal <prompt>` | Launch 10–30 minute Autonomous Goal Loop |
| `/explain` | Explain highlighted code snippet |
| `/fix` | Run Self-Healing Repair on active file diagnostic errors |
| `Ctrl + I` (or `Cmd + I`) | Launch Floating Inline AI Code Generator / Refactor Bar |
| `Tab` | Accept Inline Ghost Text Completion |
| `Enter` (in Chat) | Submit Prompt to AI Agent |
| `Campus AI: Open Chat Studio` | Open Campus AI Copilot Sidebar Panel |

---

## 🏗️ Repository Architecture

```
campus-ai-copilot-extension/
├── src/
│   ├── aiProviders.js             <-- Multi-model client & Google AI Studio Antigravity endpoint mapper
│   ├── goalRunner.js              <-- Autonomous Agent engine (Planning, File Generation, Self-Healing & Server Launch)
│   ├── webSearch.js               <-- Live Google Search grounding engine
│   ├── toolBridge.js              <-- Antigravity 8-Tool execution suite (run_command, view_file, write_to_file)
│   ├── skillsManager.js           <-- Claude Code & Antigravity agentic skills manager
│   ├── codeLensProvider.js        <-- Editor CodeLens & QuickFix CodeAction provider
│   ├── inlineCompletionProvider.js <-- Real-time ghost text autocomplete engine
│   ├── meshCluster.js             <-- Subnet P2P Mesh Cluster Engine (Port 3000 auto-discovery)
│   ├── webviewProvider.js         <-- VS Code Webview provider & event router
│   └── chatView.html              <-- Glassmorphism UI, running status indicator & interactive cards
├── extension.js                   <-- Extension entry point & command registry
├── install-extension.bat          <-- 1-Click Windows build & local installation script
├── package.json                   <-- Extension manifest, model pool configuration, commands
└── README.md                      <-- Master documentation manual
```

---

## 🚀 Installation & Setup

### Option 1: 1-Click Installation Script (Windows)
Double-click or run `install-extension.bat` in terminal:
```cmd
.\install-extension.bat
```

### Option 2: Manual Installation via VSIX
1. Package the extension:
```bash
npx @vscode/vsce package
```
2. Install into Visual Studio Code:
```bash
code --install-extension campus-ai-copilot-1.0.0.vsix --force
```

---

## 🔒 License & Business Rights

**Proprietary Commercial Software — All Rights Reserved © 2026 Nandhakumar M.**

- **No Unauthorized Use**: No individual, institution, organization, or enterprise may use, copy, reproduce, clone, modify, merge, publish, distribute, sublicense, sell, or rent this software without prior explicit written permission directly from **Nandhakumar M.**
- **Intellectual Property Rights**: All intellectual property, source code, agent logic, UI/UX designs, and technical architecture belong exclusively to **Nandhakumar M.**

For licensing, enterprise partnerships, or commercial permissions:
- **Architect & Author**: Nandhakumar M. (KGiSL Institute of Technology)
- **Role**: Head of KGiSL Campus Google Community & Google Student Ambassador
- **Email**: `24ucy129nandha@kgkite.ac.in` / `nandhakumar@kgisledu.com`
