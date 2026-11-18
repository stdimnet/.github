<div align="center">

<img src="https://raw.githubusercontent.com/stdimnet/forge/main/app/src-tauri/icons/128x128@2x.png" width="112" alt="Forge logo">

# stdim

**Developer tools built in Rust. Home of Forge, a fast, memory-safe IDE in the spirit of PHPStorm.**

[![Latest release](https://img.shields.io/github/v/release/stdimnet/forge?include_prereleases&label=forge&color=e8590c)](https://github.com/stdimnet/forge/releases)
[![Downloads](https://img.shields.io/github/downloads/stdimnet/forge/total?color=e8590c)](https://github.com/stdimnet/forge/releases)
[![AUR](https://img.shields.io/aur/version/forge-ide-bin?logo=archlinux&label=AUR)](https://aur.archlinux.org/packages/forge-ide-bin)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue)](https://github.com/stdimnet/forge#license)
[![Stars](https://img.shields.io/github/stars/stdimnet/forge?style=flat&logo=github)](https://github.com/stdimnet/forge/stargazers)

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Tauri 2](https://img.shields.io/badge/Tauri_2-24C8DB?logo=tauri&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-2C4F7C?logo=solid&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)

</div>

---

## 🔥 Forge

A PHPStorm-style IDE for **Windows, Linux and macOS**, built with **Rust + Tauri 2** and a
**SolidJS + CodeMirror 6** UI. One native binary, a familiar layout and the PHPStorm keymap
1:1, with its own look ("Ember" dark, "Anvil" light).

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/stdimnet/forge/main/docs/screenshots/workbench-light.png">
  <img src="https://raw.githubusercontent.com/stdimnet/forge/main/docs/screenshots/workbench-dark.png" alt="The Forge workbench">
</picture>

### Language packs

| Pack | Covers |
| --- | --- |
| **PHPForge** | PHP, Laravel, Symfony, Doctrine, WordPress, Composer, PHPUnit, Xdebug |
| **WebForge** | HTML, CSS, JavaScript / TypeScript, React, Vue, Angular, npm / pnpm / yarn / bun |
| **PyForge** | Python, virtual envs (uv, Poetry, conda, …), Django, Flask, FastAPI, Jupyter |
| **GoForge** | Go modules, Go Build / Test, Delve, golangci-lint, pprof |
| **RustForge** | Cargo, rustup, rust-analyzer, Clippy, nextest, LLDB / GDB |
| **JavaForge** | Java, Maven, Gradle, JUnit, Kotlin, Groovy, Scala, Android, Spring Boot |
| **CForge** | C / C++, clangd, CMake, CTest, sanitizers, PlatformIO, ESP-IDF, Zephyr |
| **DotNetForge** | C#, F#, VB, solutions, NuGet, xUnit / NUnit / MSTest, netcoredbg |
| **RubyForge** | Ruby, Bundler, Rake, RSpec, RuboCop, Rails |
| **LuaForge** | Lua 5.1–5.4, LuaJIT, LÖVE, Neovim |

### Built into the core

- 🤖 **AI**: native chat with Claude Code or Gemini CLI, AI commit messages, any provider
  (Anthropic, OpenAI, OpenRouter, Ollama, LM Studio, llama.cpp, …)
- 🔀 **Code review**: pull / merge requests, issues and CI for GitHub, GitLab and Forgejo / Gitea
- 👥 **Code With Me**: edit together over direct, host-approved QUIC connections
- 🚀 **Deployment**: SFTP, FTP / FTPS, upload on save, Sync with Deployed
- 🧩 **Browser Companion**: click a component in your running app, its source opens in Forge
- ⌨️ **Vim emulation**: IdeaVim-style, reads `~/.ideavimrc`

---

## 📦 Projects

| Project | Description | |
| --- | --- | --- |
| [**forge**](https://github.com/stdimnet/forge) | The IDE: Rust core, Tauri shell, SolidJS UI and all language packs | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) ![release](https://img.shields.io/github/v/release/stdimnet/forge?include_prereleases&label=) |
| [**php-lsp**](https://github.com/stdimnet/php-lsp) | A PHP language server in pure Rust, built into Forge. Standalone server, Intelephense drop-in, Rust / C / WebAssembly library | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) ![license](https://img.shields.io/github/license/stdimnet/php-lsp?label=) |
| [**forge-dist**](https://github.com/stdimnet/forge-dist) | Packaging: AUR (`forge-ide-bin`, `forge-ide-git`) and a signed apt repository for Debian / Ubuntu | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?logo=gnubash&logoColor=white) |

### 🛠️ Coming soon

More projects are on the way and will be opened up here:

- **Forge Marketplace**: discover and install plugins and packs
- **Forge Plugins**: official plugins beyond the bundled packs
- **Forge Docs**: the user and developer guide as a website
- **forge website**: the project homepage and downloads

![Status](https://img.shields.io/badge/status-in_progress-yellow)

---

<div align="center">

**[Download Forge](https://github.com/stdimnet/forge/releases)** ·
**[Report an issue](https://github.com/stdimnet/forge/issues)** ·
**[Contribute](https://github.com/stdimnet/forge/blob/main/CONTRIBUTING.md)**

<sub>Forge is in beta. Feedback and bug reports are very welcome.</sub>

</div>
