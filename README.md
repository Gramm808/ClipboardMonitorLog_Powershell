# Clipboard Monitor

![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)
![GitHub](https://img.shields.io/github/license/YOUR_USERNAME/YOUR_REPO?color=blue)

A real-time Windows clipboard monitor with logging capabilities, written in PowerShell.

## 📌 Table of Contents  
- [Features](#-features)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Contributing](#-contributing)  
- [License](#-license)  


## Features

- 📋 **Text/Number Detection**: Logs all copied text and numeric content
- ⏱️ **Timestamped Entries**: Local time tracking for all changes
- 📂 **Daily Log Files**: Auto-creates dated log files in `Documents/ClipboardLogs`
- 🚦 **Non-Text Alerts**: Detects images/files/cleared clipboard
- 🔒 **Privacy Focused**: No network calls, all data stays local

## Installation

1. Ensure PowerShell 5.1+ is enabled:
   ```powershell
   $PSVersionTable.PSVersion

## **🚀 Usage**  
- Copy and paste the script into powershell and click enter
- Use system clipboard as normal to view historical output in the PS window and to have it logged to .txt file startingi n v1.5
- Ensure focus on PS window and press Esc key to stop script.

## **🙏 Credits/Acknowledgments**  
- DeepSeek v3
- Qwen 2.5 max

## Versions

| Version | Changes |
|---------|---------|
| [v1.5](src/ClipboardMonitor_v1.5.ps1) | Session-based logging, skip initial content |
| [v1.4](src/ClipboardMonitor_v1.4.ps1) | Fixed log overwrite issues |
| [v1.3](src/ClipboardMonitor_v1.3.ps1) | Added truncation (250 chars) |
| [v1.2](src/ClipboardMonitor_v1.2.ps1) | Initial release with basic logging |
