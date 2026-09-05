# NPS – Network Protocols Script

[![GitHub release](https://img.shields.io/github/v/release/hiosw/nps)](https://github.com/hiosw/nps/releases)
[![Go Version](https://img.shields.io/badge/Go-1.22+-00ADD8?style=flat&logo=go)](https://golang.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/hiosw/nps)](https://github.com/hiosw/nps/issues)

**NPS** (Network Protocols Script) is a lightweight, compiled and interpreted programming language designed for network automation, packet filtering, cryptography, and system scripting. It combines the strictness of C++ preprocessor directives with the simplicity of Python‑like syntax.

> 🚀 **Alpha release v0.0.3** – see [Releases](https://github.com/hiodev/nps/releases) for downloads.

---

## ✨ Features

- **Cross‑platform** – works on macOS, Windows, Linux (single binary).
- **Built‑in network types**: `ip`, `port`, `packet`.
- **Two execution modes**:
  - **`nps build`** – compiles to native executable (requires Go).
  - **`nps run`** – interprets code directly (no Go needed).
- **Package manager** – `install`, `remove`, `list`, `update` libraries from central registry.
- **C‑style preprocessor** – `#include`, `#define`.
- **Modern syntax** – `if`, `while`, `match`, `task` functions, mutable variables.

---

## 📦 Installation

### macOS
```bash
curl -O https://hiosw.myarena.site/downloads/nps-macos
chmod +x nps-macos
sudo mv nps-macos /usr/local/bin/nps
xattr -d com.apple.quarantine /usr/local/bin/nps
