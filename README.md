# Orlim — macOS Releases

[![macOS 13+](https://img.shields.io/badge/macOS-13%2B%20Universal-blue)](https://github.com/Jambo-company/orlim-releases/releases/latest)
[![Apple Notarized](https://img.shields.io/badge/Apple-Developer%20ID%20%26%20Notarized-success)](https://github.com/Jambo-company/orlim-releases/releases/latest)
[![Homebrew Cask](https://img.shields.io/badge/Homebrew-Cask-orange)](https://github.com/Jambo-company/homebrew-tap)

**Orlim** is a native macOS menu bar workstation for developers working across multiple AI coding tools simultaneously (**Claude Code**, **OpenAI Codex**, **Cursor**, **Gemini**, **GitHub Copilot**, **Windsurf**, and more).

It brings live quota tracking, burn-rate & exhaustion predictions, provider routing recommendations, local session activity attribution, a desktop companion, and system metrics into one lightweight macOS menu bar app and WidgetKit extension.

---

## Installation

### Option 1: Homebrew (Recommended)

```bash
brew tap Jambo-company/tap
brew trust jambo-company/tap 2>/dev/null || true
brew install --cask orlim
```

To upgrade via Homebrew:

```bash
brew update && brew upgrade --cask orlim
```

### Option 2: Direct Download (Universal `.dmg`)

Download the latest Apple-notarized universal `.dmg` (Apple Silicon `arm64` + Intel `x86_64`) from [**Releases**](https://github.com/Jambo-company/orlim-releases/releases/latest), open the disk image, and drag **Orlim.app** to `/Applications`.

---

## System Requirements

- **macOS 13.0 (Ventura)** or later (including macOS 14 Sonoma, macOS 15 Sequoia, and macOS 26 Tahoe)
- **Architecture:** Universal binary (`arm64` Apple Silicon & `x86_64` Intel)
- **Code Signing:** Signed with `Developer ID Application: Jambo Lab Inc. (7732Q53565)` and notarized by Apple

---

## Feedback & Bug Reports

Have a bug report or feature request? Open an issue in [**Jambo-company/orlim-releases/issues**](https://github.com/Jambo-company/orlim-releases/issues).
