# Awesome-Source-Code-Editor

## Top Source Code Editor Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on AI-Assisted Coding, Extensible Editing & Developer Productivity*  

**Last updated: October 2026**



This repository tracks notable **commercial source code editors** and **open-source projects** that provide code editing, syntax highlighting, debugging, version control integration, and increasingly AI-powered development assistance.



**Examples** include Microsoft Visual Studio Code (VS Code), Sublime Text, Atom, Notepad++, Vim, Emacs, Nova, TextMate, Cursor, and Zed (the category leaders).



**Open-source emphasis**: Source code editing is one of the strongest open-source domains. **VS Code OSS**, **Vim**, **Neovim**, **Emacs**, **Zed**, and **Lapce** collectively power millions of developers, with **Helix** and **Kakoune** offering modern modal alternatives. **Cursor** and **Windsurf** lead AI-native editors, while **VSCodium** provides a telemetry-free VS Code build. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cursor](https://cursor.com/)**  

  **The leading AI-native code editor**, built as a VS Code fork with deep AI integration. Features **Composer** for multi-file editing, **Tab** for predictive code completion, and **Agent mode** for autonomous task execution . **Freemium model** — free tier with limited AI requests; Pro at $20/month, Business at $40/user/month . **The most widely adopted AI code editor** — used by 1M+ developers . **Trade-off**: proprietary fork of VS Code, not open source.



- **[Sublime Text](https://www.sublimetext.com/)**  

  Legendary proprietary editor known for speed, multiple cursors, and the Command Palette. **One-time purchase** ($99) with free evaluation. **The editor that inspired VS Code's UX** — still beloved for performance and minimalism .



- **[Nova](https://nova.app/)**  

  Panic's native macOS code editor with beautiful interface, built-in Git, and extensibility. **One-time purchase** ($99). **Best for macOS developers** wanting native performance without Electron .



- **[TextMate](https://macromates.com/)**  

  macOS editor that pioneered snippets, bundles, and scoped editing. **Open-sourced in 2012** but development has slowed. **Historically influential** — inspired Sublime Text and VS Code grammars .



- **[Windsurf](https://windsurf.com/)**  

  AI-native IDE (formerly Codeium) with Cascade agent for multi-file editing and deep contextual awareness. **Freemium model** with paid tiers. **The main competitor to Cursor** in the AI editor space .



## Open-Source GitHub Projects



- **[Visual Studio Code (VS Code OSS)](https://github.com/microsoft/vscode)**  

  **The most widely used code editor in the world**, MIT licensed with 160,000+ GitHub stars . Built with Electron and TypeScript. **Extensions ecosystem with 50,000+ plugins**, integrated terminal, Git, debugging, and IntelliSense . **VS Code OSS** is the open-source core; Microsoft's branded builds add telemetry and proprietary marketplace access . **Note**: The marketplace and some Microsoft-specific extensions are proprietary . **The de facto standard for modern development** — free and cross-platform .



- **[VSCodium](https://github.com/VSCodium/vscodium)**  

  **Fully open-source, telemetry-free build of VS Code**, MIT licensed . **Removes Microsoft branding, telemetry, and proprietary components** . Uses Open VSX marketplace instead of Microsoft's proprietary marketplace . **The best choice for privacy-conscious developers** who want VS Code without Microsoft's data collection .



- **[Vim](https://github.com/vim/vim)**  

  **The legendary modal text editor**, charityware licensed with 38,000+ GitHub stars . Terminal-based with incredibly efficient keyboard-driven editing. **Available on virtually every Unix-like system** — often pre-installed . Highly configurable via vimrc and thousands of plugins. **Steep learning curve but unmatched editing speed** once mastered .



- **[Neovim](https://github.com/neovim/neovim)**  

  **Modern refactor of Vim** with Lua scripting, built-in LSP, treesitter, and async plugin architecture . Apache-2.0 licensed with 85,000+ GitHub stars . **The preferred choice for new Vim users** — better defaults, active development, and a thriving plugin ecosystem (lazy.nvim, telescope, nvim-cmp) . **Turns Vim into a full IDE** without Electron overhead . **AI plugins available**: codeium.nvim, copilot.vim, avante.nvim .



- **[GNU Emacs](https://github.com/emacs-mirror/emacs)**  

  **The extensible, customizable, self-documenting editor**, GPL licensed with 4,500+ GitHub stars (mirror) . **More than an editor — a Lisp environment** that happens to edit text. Org-mode, Magit, Dired, and thousands of packages make it a complete workflow platform . **The most extensible editor ever created** — but requires investment to configure .



- **[Zed](https://github.com/zed-industries/zed)**  

  **High-performance, multiplayer code editor** written in Rust, GPL-3.0 licensed with 60,000+ GitHub stars . Built by the creators of Atom and Tree-sitter. **GPU-accelerated rendering**, built-in collaboration, and AI integration . **The fastest modern editor** — native performance without Electron . Available on macOS and Linux; Windows in development. **AI features**: integrated assistant, inline transformations, and Agent mode .



- **[Lapce](https://github.com/lapce/lapce)**  

  **Lightning-fast and powerful code editor written in Rust**, Apache-2.0 licensed with 35,000+ GitHub stars . **Built-in LSP, remote development, Vim mode, and WASI plugin system** . Custom GPU-accelerated renderer using Floem UI toolkit . **The most feature-complete Rust editor** after Zed — smaller community but rapid development . **AI features**: built-in AI chat with multiple provider support .



- **[Helix](https://github.com/helix-editor/helix)**  

  **Post-modern modal text editor**, MPL-2.0 licensed with 35,000+ GitHub stars . **Built-in LSP, treesitter, and multiple selections** by default . **Kakoune-inspired selection-first workflow** — different from Vim but logical . **The most promising Vim alternative** for users wanting modal editing with modern defaults . **AI features**: community plugins for Copilot and LLM integration .



- **[Atom](https://github.com/atom/atom)**  

  **The hackable text editor from GitHub**, MIT licensed with 60,000+ GitHub stars . **Electron-based with package ecosystem** — pioneered web-tech editors . **Note: development ended in December 2022** . **Historically significant** — inspired VS Code, Zed, and Pulsar . **Community fork Pulsar** continues development .



- **[Pulsar](https://github.com/pulsar-edit/pulsar)**  

  **Community-led successor to Atom**, MIT licensed . **Continues Atom's hackable philosophy** with modern updates and package compatibility . **Best for former Atom users** wanting a maintained alternative . **AI features**: community packages for Copilot and AI assistance .



- **[Notepad++](https://github.com/notepad-plus-plus/notepad-plus-plus)**  

  **Windows-only open-source editor**, GPL-2.0 licensed with 25,000+ GitHub stars . **Syntax highlighting for 80+ languages**, macros, and plugin ecosystem . **The standard Windows notepad replacement** — lightweight and fast . **AI features**: via plugins like NppOpenAI .



- **[Kate](https://github.com/KDE/kate)**  

  **KDE's advanced text editor**, LGPL-2.0 licensed . **Multi-document interface, session management, LSP support, and extensive plugin ecosystem** . **The best GUI editor for KDE Plasma** — integrates with Dolphin and Konsole. Available on Linux, Windows, and macOS .



- **[Lite XL](https://github.com/lite-xl/lite-xl)**  

  **Lightweight, fast, and simple code editor**, MIT licensed with 5,000+ GitHub stars . Written in C and Lua with **minimal resource usage** . **The spiritual successor to Atom** — extensible via Lua plugins without Electron overhead . **Best for low-resource systems** or users wanting simplicity .



### AI-Native Editors (Open-Source Foundation)



- **[Continue](https://github.com/continuedev/continue)**  

  **Open-source AI code assistant** that integrates with VS Code and JetBrains, Apache-2.0 licensed with 20,000+ GitHub stars . **Bring your own LLM** — supports OpenAI, Anthropic, local models via Ollama, and more . Features **autocomplete, chat, and edit** within your existing editor . **The leading open-source Copilot alternative** — no vendor lock-in .



- **[Cody (Sourcegraph)](https://github.com/sourcegraph/cody)**  

  **AI coding assistant with codebase-aware context**, Apache-2.0 licensed . **Understands your entire repository** — not just the current file . Features chat, autocomplete, and commands . **Best for large codebases** where context matters . **Note**: Sourcegraph has scaled back Cody's open-source development.



- **[Aider](https://github.com/Aider-AI/aider)**  

  **AI pair programming in your terminal**, Apache-2.0 licensed with 20,000+ GitHub stars . **Works with any LLM** — GPT-4, Claude, local models . Features **automatic Git commits**, multi-file editing, and voice input . **The most popular terminal-based AI coding tool** — integrates with any editor .



- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)**  

  **Open-source AI software engineer** (formerly OpenDevin), MIT licensed with 35,000+ GitHub stars . **Autonomous coding agent** that can write code, run commands, browse the web, and call APIs . **The most capable open-source coding agent** — runs in Docker sandbox . **AI features**: full software engineering automation .



### Additional Strong Open-Source Options



- **Kakoune** — Modal editor with multiple selections and orthogonal design, inspiring Helix .

- **Micro** — Terminal editor with familiar keybindings (Ctrl+S, Ctrl+Q), MIT licensed .

- **Geany** — Lightweight IDE/editor with GTK+ interface, GPL-2.0 licensed .

- **CudaText** — Cross-platform editor with syntax highlighting for 300+ languages .

- **amp** — Terminal-based modal editor written in Rust .

- **Xi Editor** — Experimental editor with rope data structure (development slowed).

- **GNOME Text Editor** — Modern GNOME editor with session restore, GPL-3.0 licensed .



**Frameworks for building custom editing solutions**: Choose based on workflow and AI needs. **VS Code OSS** for the largest extension ecosystem and Microsoft's backing . **VSCodium** for telemetry-free VS Code . **Cursor** or **Windsurf** for the most integrated AI experience (proprietary) . **Zed** for maximum performance with built-in AI and collaboration . **Neovim** or **Emacs** for terminal-based extensibility with AI plugins . **Helix** for modern modal editing with sensible defaults . **Continue** or **Aider** for adding AI to any editor . Note that true AI-native editing with proprietary models and deep codebase indexing remains primarily commercial territory; open-source stacks provide strong editing, extension, and AI-assistant foundations that require configuration for complete workflows.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Source code editors handle proprietary code and potentially credentials. **AI features may transmit code to external services** — review privacy settings and data handling policies before enabling AI assistance on sensitive codebases.

- **VS Code's marketplace and some Microsoft extensions are proprietary** — VSCodium and Open VSX provide fully open-source alternatives, but extension compatibility may vary . Evaluate gaps before switching .

- **Cursor and Windsurf are proprietary VS Code forks** — they offer the most integrated AI experience but are not open source. The open-source ecosystem provides alternatives via Continue, Aider, and editor plugins .

- **Modal editors (Vim, Neovim, Helix, Kakoune) require learning investment** — productivity gains are real but not immediate .

- The open-source ecosystem provides strong editing, extension, and AI-assistant foundations, but **proprietary AI models, vendor-supported enterprise features, and integrated collaboration** remain primarily commercial offerings.



---



**Made for developers, software engineers, and anyone who lives in a code editor.**  

Let's make source code editing more open, transparent, and intelligent.
