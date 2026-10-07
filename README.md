# 🍷 tinto

A fast home for your coding agents: run Claude Code, Codex, Gemini CLI, OpenCode, Pi (or
any CLI) side by side, see which one needs you, approve from one inbox, keep policies and
memory across all of them. macOS, Linux and Windows.

This repository hosts **releases of the tinto CLI** (binaries and install scripts).

## Install

```sh
# macOS / Linux
curl -fsSL https://github.com/fperetti/tinto-releases/releases/latest/download/install.sh | sh
```

```powershell
# Windows (PowerShell)
irm https://github.com/fperetti/tinto-releases/releases/latest/download/install.ps1 | iex
```

Then run `tinto`. It updates itself automatically (only when no agent is running).

Every binary is listed with its SHA-256 in each release's `manifest.json` and `SHA256SUMS`;
the install scripts and the updater verify them.
