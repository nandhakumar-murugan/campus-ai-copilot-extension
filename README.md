# ⚡ Campus AI Supercomputer Copilot

> **100% Zero-Cloud AI Coding Assistant, Autonomous Agent & Security Auditor for KGiSL Campus Intranet Network**  
> *Developed by Nandhakumar M. • Head of KGiSL Campus Google Community & Google Student Ambassador*

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Network](https://img.shields.io/badge/network-100%25%20Offline%20Intranet-success.svg)
![Security](https://img.shields.io/badge/security-Zero--Cloud%20Data%20Privacy-green.svg)
![Platform](https://img.shields.io/badge/platform-VS%20Code-007ACC.svg)

---

## 📌 Executive Summary

**Campus AI Supercomputer Copilot** brings local, privacy-first agentic intelligence directly into Visual Studio Code. Combining the best features of **GitHub Copilot, Google Antigravity 2.0, Antigravity IDE, and Claude Code Open-Source Skills**, it operates with zero external cloud dependencies. All code completions, chat conversations, refactoring operations, and security audits stay strictly within the local campus intranet (`http://172.16.110.12:3000`), guaranteeing absolute data privacy, IP protection, and sub-millisecond response latency.

---

## 🌟 Master Feature Breakdown

### 1. ⌨️ Real-Time Inline Ghost Text (`Tab` to Accept)
- Suggests single-line and multi-line code completions automatically as you type in any `.py`, `.js`, `.java`, `.cpp`, or `.html` file.
- Press **`Tab`** to accept and insert suggestions directly.

### 2. ✨ `Ctrl + I` Inline AI Code Generator & Refactor
- Press **`Ctrl + I`** inside any file to open a quick floating AI prompt bar.
- Type instructions like *"Refactor to async/await"* or *"Write Fibonacci function"* — code is applied directly at your cursor!

### 3. 🧩 Claude Code & Antigravity Agentic Skills Suite (`🧩 Skills`)
- Access built-in agentic skills from the header:
  - 🏗️ **`architecture-analyst`**: Codebase structure & dependency graphing.
  - 🛡️ **`security-auditor`**: OWASP Top 10 vulnerability & secret scanner.
  - 🚀 **`fullstack-builder`**: End-to-end full stack application creation.
  - ⚡ **`refactor-engineer`**: Automated code refactoring & performance tuning.
  - 🧪 **`test-suite-generator`**: Automated Jest, PyTest, and Mocha test generation.

### 4. 🛠️ Antigravity 8-Tool Native Execution Suite
- Natively executes terminal commands (`run_command`), codebase pattern searches (`grep_search`), directory listings (`list_dir`), file reading (`view_file`), and direct writing (`write_to_file`).
- Type **`Run command npm --version`** or **`Grep search queryAi`** into chat to see live terminal output directly!

### 5. 🚀 Long-Running Autonomous Goal Agent (`/goal`)
- Continuous 10–30 minute execution loop (`🚀 Build Full Stack App`) that plans, creates folders, and generates complete multi-file applications automatically with zero prompt questions!

### 6. 🌐 Live Online Deep Research Engine (`/research` & `🔬 Deep Research`)
- Queries live web search engines in real-time (`docs.python.org`, `geeksforgeeks.org`, `realpython.com`, `github.com`) and outputs executive reports with clickable web links (`🌐 Title`).

### 7. ⚡ Zero-Prompt Direct Workspace File Operations
- **`📝 Apply to File`** and **`✨ Create File`** buttons execute direct background file writes directly into workspace files with 0 popup questions!

### 8. 📜 Multi-Session Chat History (`📜 History` & `➕ New Chat`)
- Stores up to 15 recent chat sessions in persistent storage across VS Code restarts.

### 9. 🎨 Editor CodeLenses & QuickFix Error Squiggles
- Interactive **`✨ Refactor | 🧪 Write Tests | 🧠 Explain`** buttons above functions in code files.
- Hover over red/yellow error squiggles -> click **`⚡ Fix Error with Campus AI`**.

---

## ⌨️ Command & Shortcut Reference

| Shortcut / Command | Description |
|:---|:---|
| `Ctrl + I` (or `Cmd + I`) | Launch Floating Inline Code Generator / Refactor Box |
| `Tab` | Accept Inline Ghost Text Code Completion |
| `Enter` (in Chat) | Submit Prompt to Campus AI Studio |
| `/goal <prompt>` | Launch 10–30 min Autonomous Agent Goal Execution |
| `/research <topic>` | Launch Multi-Step Deep Web Research |
| `/explain` | Explain highlighted code snippet |
| `/fix` | Fix all diagnostic errors in active file |
| `Campus AI: Open Chat Studio` | Open AI Chat Sidebar Panel |
| `Campus AI: Fix All Errors in Active File` | Run Side-by-Side Diff Preview Error Fixer |

---

## 🏗️ Clean Modular Repository Architecture

```
campus-ai-copilot-extension/
├── src/
│   ├── aiProviders.js             <-- Multi-model client (Gemini 3.6 Flash, 3.1 Flash-Lite, Local Mesh)
│   ├── goalRunner.js              <-- Long-running autonomous goal execution engine
│   ├── webSearch.js               <-- Live web search grounding engine
│   ├── toolBridge.js              <-- Antigravity 8-Tool execution engine (run_command, view_file, etc.)
│   ├── skillsManager.js           <-- Claude Code & Antigravity agentic skills manager
│   ├── codeLensProvider.js        <-- Editor CodeLens & QuickFix CodeAction provider
│   ├── inlineCompletionProvider.js <-- Ghost text inline completion engine
│   ├── webviewProvider.js         <-- VS Code Webview Provider bridge
│   └── chatView.html              <-- Ultra-premium glassmorphism UI frontend
├── extension.js                   <-- Extension entry point & command registry
├── install-extension.bat          <-- 1-Click Windows build and local installation script
├── package.json                   <-- Extension manifest, commands, views, keybindings
├── .gitignore                     <-- Git ignore rules
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
code --install-extension campus-ai-copilot-1.0.0.vsix
```

---

## 🎓 Author & Credits

- **Author**: Nandhakumar M. (B.E. CSE Cybersecurity, 3rd Year / V Semester)
- **Institution**: KGiSL Institute of Technology (KGiSL ITech), Coimbatore, Tamil Nadu
- **Roles**: Head of KGiSL Campus Google Community & Google Student Ambassador
- **Engine**: Powered by Google AI Studio & KGiSL Campus Intranet Supercomputer Cluster.
