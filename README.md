<div align="center">

<img src="myko-icon.png" alt="Myko" width="120">

# Myko

### The AI-native developer workspace.

**Terminal. Editor. Git. AI. Preview. One desktop workspace.**

Build, debug, review, and ship software without constantly switching between tools.

<br>

[![Website](https://img.shields.io/badge/Website-Myko-111111?style=for-the-badge)](https://myko-beta.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-111111?style=for-the-badge\&logo=github)](https://github.com/mustafa-lil-dev/myko-ai)
[![License](https://img.shields.io/badge/License-GPL--3.0-111111?style=for-the-badge)](LICENSE)

</div>

---

## What is Myko?

Myko is a desktop development workspace built with **Tauri 2, Rust, React, and TypeScript**.

Instead of jumping between a terminal, editor, Git client, browser preview, and AI tools, Myko brings the core development workflow into one focused application.

```text
┌───────────────────────────────────────────────────────────────┐
│                           MYKO                                │
├──────────────┬──────────────────────────────┬───────────────┤
│              │                              │               │
│ File         │       Code Editor            │   AI          │
│ Explorer     │                              │   Workspace   │
│              │                              │               │
├──────────────┴──────────────────────────────┴───────────────┤
│                     Native Terminal                          │
├───────────────────────────────────────────────────────────────┤
│ Git • Preview • Processes • Tools                            │
└───────────────────────────────────────────────────────────────┘
```

Myko is designed around an **AI-first development workflow**, while keeping the traditional tools developers already rely on close at hand.

---

# Screenshots

Myko is designed to keep the entire development workflow inside one workspace.

## AI-native workflow

<table>
<tr>
<td width="50%" valign="top">

### AI Workflow

<img src="docs/ai-workflow.png" alt="Myko AI Workflow" width="100%">

Plan, build, review, and iterate with AI directly inside your development workspace.

</td>

<td width="50%" valign="top">

### Code Editor

<img src="docs/editor.png" alt="Myko Code Editor" width="100%">

A focused CodeMirror-powered editor with syntax highlighting, diagnostics, Vim mode, AI completion, and AI-assisted edits.

</td>
</tr>
</table>

## Developer workspace

<table>
<tr>
<td width="50%" valign="top">

### Native Terminal

<img src="docs/terminal.png" alt="Myko Terminal" width="100%">

A native PTY terminal with tabs, splits, background processes, WebGL rendering, and multiple shell environments.

</td>

<td width="50%" valign="top">

### Source Control

<img src="docs/source-control.png" alt="Myko Source Control" width="100%">

Stage, commit, push, search history, and explore Git history through a visual commit graph.

</td>
</tr>
</table>

## Make it yours

<table>
<tr>
<td width="50%" valign="top">

### Themes

<img src="docs/themes.png" alt="Myko Themes" width="100%">

Customize the workspace with application themes, editor themes, backgrounds, opacity, blur, and keyboard shortcuts.

</td>

<td width="50%" valign="top">

### Web Preview

<img src="docs/web-preview.png" alt="Myko Web Preview" width="100%">

Detect local development servers and preview web applications directly inside Myko.

</td>
</tr>
</table>

---

# Why Myko?

Modern development often looks like this:

```text
Terminal
   ↓
Code Editor
   ↓
Git Client
   ↓
Browser
   ↓
AI Assistant
   ↓
Debugger
   ↓
Database Tool
   ↓
Back to Editor
```

Myko brings the workflow closer together:

```text
                    ┌───────────────┐
                    │      AI       │
                    └───────┬───────┘
                            │
┌────────────┐      ┌───────▼───────┐      ┌─────────────┐
│   Files    │──────│     MYKO      │──────│     Git     │
└────────────┘      │               │      └─────────────┘
                    │  Development  │
┌────────────┐      │   Workspace   │      ┌─────────────┐
│  Terminal  │──────│               │──────│ Web Preview │
└────────────┘      └───────┬───────┘      └─────────────┘
                            │
                    ┌───────▼───────┐
                    │    Editor     │
                    └───────────────┘
```

---

# Features

## ⚡ Native Terminal

Myko includes a native terminal powered by a real PTY backend.

* xterm.js rendering
* WebGL rendering
* Native PTY powered by `portable-pty`
* Multiple terminal tabs
* Horizontal and vertical splits
* Background processes
* Background output streaming
* Inline terminal search
* Link detection
* True-color output
* Terminal serialization
* Process management
* PowerShell
* PowerShell 7 / `pwsh`
* Command Prompt
* Bash
* Zsh
* Fish
* Windows local environment
* WSL environments

The terminal is not a simulated command console. It connects to the native operating-system environment.

---

# ✦ AI Workspace

Myko is built around an AI-native development workflow.

AI can work alongside your project rather than existing as a separate chat window.

### AI capabilities

* Composer
* File references with `@path`
* Reusable prompt snippets with `#handle`
* Slash commands
* Voice input where supported
* File attachments
* Editor-selection attachments
* Terminal-selection attachments
* `MYKO.md` project instructions and memory
* Plan mode
* Todo tracking
* Custom agents
* Sub-agents
* File reading
* File writing
* File editing
* Multi-file editing
* Grep
* Glob
* Terminal tool integration
* Command approval
* Background processes
* Streaming responses
* Reasoning display
* Tool status
* Notifications
* AI-generated edit diffs
* Reviewable changes before applying them

### Bring your own AI

Myko supports multiple cloud and local AI providers.

**Cloud providers**

* OpenAI
* Anthropic
* Google Gemini
* Groq
* xAI
* Cerebras
* OpenRouter
* DeepSeek
* Mistral
* OpenAI-compatible endpoints

**Local AI**

* LM Studio
* MLX
* Ollama

You choose the provider, endpoint, and model.

---

# 🧠 AI-assisted editing

AI-generated code changes can be reviewed before they are applied.

Instead of blindly replacing files, Myko can present changes as editable diffs.

```text
AI
 │
 ├── Understand project
 │
 ├── Plan changes
 │
 ├── Generate edits
 │
 ▼
Review Diff
 │
 ├── Accept
 ├── Reject
 └── Continue editing
```

This keeps the developer in control of changes.

---

# 💻 Code Editor

Myko includes a CodeMirror 6 editor.

### Editor features

* CodeMirror 6
* Multiple editor tabs
* Syntax highlighting
* Diagnostics
* Vim mode
* AI autocomplete
* AI-assisted edits
* Edit diffs
* Unsaved-change protection
* Multiple programming languages
* Independent editor themes

Supported languages include:

* TypeScript
* JavaScript
* JSX
* TSX
* Rust
* Python
* Go
* C
* C++
* Java
* PHP
* HTML
* CSS
* JSON
* Markdown
* Vue
* And other common formats

---

# 📁 File Explorer

Navigate your project without leaving Myko.

* Directory tree
* Fuzzy file search
* Keyboard navigation
* Inline rename
* File context actions
* Directory context actions
* Catppuccin file icons
* File attachments for AI
* Editor-selection attachments
* Terminal-selection attachments
* File watching
* Workspace-aware file changes

---

# Git & Source Control

Git is integrated directly into the development workspace.

### Git features

* Repository status
* Branch status
* Stage files
* Unstage files
* Stage individual hunks
* Unstage individual hunks
* Commit changes
* Push changes
* Upstream awareness
* Detached HEAD display
* Commit search
* Commit filtering
* Visual commit graph
* Merge lanes
* Open commits on the configured remote
* Native Git command handling
* Git error handling

Commit shortcuts:

```text
Windows / Linux
Ctrl + Enter

macOS
Cmd + Enter
```

---

# 🌐 Web Preview

Myko can detect local development servers and preview applications without forcing you to constantly switch to another window.

### Web preview features

* Local development server detection
* Local server preview
* External URL preview
* Native child webview support
* Adjustable preview layout
* Development workflow integration

Run your application and preview it from the same workspace.

---

# 🎨 Themes & Customization

Your development environment should feel like yours.

Myko supports:

* Built-in application themes
* Custom application themes
* Import/export custom themes
* Background images
* Adjustable background opacity
* Blur effects
* Independent editor themes
* Custom keyboard shortcuts
* Persistent window layout
* Persistent panel layout

---

# 🔐 Privacy & Security

Myko is designed to keep control in the developer's hands.

### API keys

Provider credentials are stored in the operating system's credential store on macOS (Keychain) and Windows (Credential Manager).

On **Linux**, Myko uses the Secret Service (GNOME Keyring / KWallet over D-Bus) when one is reachable, and moves any keys it previously kept in a file into it the first time they are read. If no Secret Service is available (headless sessions, minimal window managers, a missing or locked daemon), Myko falls back to a JSON file in the app's local data directory, readable only by your user (mode `0600`). **That fallback file is not encrypted.** Treat it like an SSH private key: anyone who can read your home directory as your user can read it.

They are **not stored in `localStorage`** and are not written into project files.

### AI permissions

AI tools can be configured with specific capabilities.

Potentially destructive operations such as shell commands can require approval depending on configuration.

### No required Myko account

Myko does not require users to create an application account.

### No application telemetry

Myko does not include application telemetry.

AI requests go to the provider or local endpoint configured by the user.

---

# 🖥️ Cross-platform

Myko is designed as a desktop application using Tauri 2.

### Windows

Supported with native Windows development environments and WSL.

### Linux

Build targets can produce:

* AppImage

### macOS

Builds can target supported macOS architectures.

---

# 🚀 Installation

Installers are produced through the Tauri release build system.

## Windows

Run the Myko installer and launch the application.

If Windows SmartScreen displays a warning for an unsigned development build:

1. Select **More info**
2. Select **Run anyway**

WSL distributions can be used as workspace environments when installed.

---

## Linux

Depending on the build target, Myko can be distributed as:

```text
AppImage
```

For AppImage systems without FUSE support:

```bash
./Myko_*.AppImage --appimage-extract-and-run
```

For some Wayland rendering issues:

```bash
WEBKIT_DISABLE_DMABUF_RENDERER=1 ./Myko_*.AppImage
```

---

## macOS

Use the generated macOS application bundle or disk image for the target architecture.

Myko's current build configuration targets macOS 13 or newer.

---

# 🤖 Configure AI

After installing Myko:

1. Open **Settings → AI**
2. Select your provider
3. Enter your API key or local endpoint
4. Select a model
5. Save the configuration
6. Open the AI workspace

For local AI, start your local provider first.

Supported local environments include:

```text
LM Studio
MLX
Ollama
```



# 🔗 Links

**Website**

https://myko-beta.vercel.app/



---

<div align="center">

## Build without leaving your flow.

### Myko

**Your development workspace, built around AI.**

<br>

Made with Rust, React, TypeScript, and a lot of coffee.

</div>
