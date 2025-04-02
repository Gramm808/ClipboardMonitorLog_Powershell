# Clipboard Monitor

![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)
![GitHub](https://img.shields.io/github/license/YOUR_USERNAME/YOUR_REPO?color=blue)

A real-time Windows clipboard monitor with logging capabilities, written in PowerShell.

## Features

- 📋 **Text/Number Detection**: Logs all copied text and numeric content
- ⏱️ **Timestamped Entries**: Local time tracking for all changes
- 📂 **Daily Log Files**: Auto-creates dated log files in `Documents/ClipboardLogs`
- 🚦 **Non-Text Alerts**: Detects images/files/cleared clipboard
- 🔒 **Privacy Focused**: No network calls, all data stays local

## Versions

| Version | Changes |
|---------|---------|
| [v1.5](src/ClipboardMonitor_v1.5.ps1) | Session-based logging, skip initial content |
| [v1.4](src/ClipboardMonitor_v1.4.ps1) | Fixed log overwrite issues |
| [v1.3](src/ClipboardMonitor_v1.3.ps1) | Added truncation (250 chars) |
| [v1.2](src/ClipboardMonitor_v1.2.ps1) | Initial release with basic logging |

## Installation

1. Ensure PowerShell 5.1+ is enabled:
   ```powershell
   $PSVersionTable.PSVersion
