# Multi-Streamer Bot

> **Multi-Streamer System for Streamer.bot**
>
> 📖 **[READ THE WIKI DOCUMENTATION](https://github.com/Sythsaz/Multi-Streamer-Bot/wiki)**
>
> **Active Development! There may be breaking changes until things get ironed out a bit better**
>
> [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
> [![Streamer.bot](https://img.shields.io/badge/Streamer.bot-v0.2.3%2B-blueviolet)](https://streamer.bot)
> [![GitHub release](https://img.shields.io/github/v/release/Sythsaz/Multi-Streamer-Bot.svg)](https://github.com/Sythsaz/Multi-Streamer-Bot/releases)
>
> [![Markdown Lint](https://github.com/Sythsaz/Multi-Streamer-Bot/actions/workflows/markdown-lint.yml/badge.svg)](https://github.com/Sythsaz/Multi-Streamer-Bot/actions/workflows/markdown-lint.yml)
> [![C# 7.3 .NET Tests](https://github.com/Sythsaz/Multi-Streamer-Bot/actions/workflows/tests.yml/badge.svg)](https://github.com/Sythsaz/Multi-Streamer-Bot/actions/workflows/tests.yml)
>
> ![C# Version](https://img.shields.io/badge/C%23-7.3-blue)
> ![.NET Framework](https://img.shields.io/badge/.NET%20Framework-4.8-purple)

![Multi-Streamer Bot Banner](.github/assets/banner.png)

## 📖 Documentation

All documentation has moved to the **[GitHub Wiki](https://github.com/Sythsaz/Multi-Streamer-Bot/wiki)**.

- **[User Guide](https://github.com/Sythsaz/Multi-Streamer-Bot/wiki/User-Guide)**: Installation, commands, and configuration.
- **[Advanced Guide](https://github.com/Sythsaz/Multi-Streamer-Bot/wiki/Advanced-Configuration)**: Custom triggers, OBS
  integration, and power-user features.
- **[FAQ](https://github.com/Sythsaz/Multi-Streamer-Bot/wiki/FAQ)**: Troubleshooting and common questions.
- **[Developer Guide](https://github.com/Sythsaz/Multi-Streamer-Bot/wiki/Developer-Guide)**: Architecture,
  contributing, and building.

## ✨ Key Features

- **Remote Control & Automation**: Control programmatically via Streamer.bot variables (Stream Deck ready).
- **Smart Validation**: Blocks bots using entropy checks and account age verification.
- **Rich Feedback**: Windows **Toast Notifications**, **Localization** support, and highly visible chat alerts.
- **Bidirectional Sync (Mirror Mode)**: Update config settings directly from Streamer.bot Global Variables.
- **Auto-Update**: Built-in command `!ms update` to check for and download the latest version.

## 🚀 Quick Start

1. **Download** the latest `Multi-Streamer-Bot.cs` from [Releases](https://github.com/Sythsaz/Multi-Streamer-Bot/releases).
2. **Import** into Streamer.bot:
   - Create a new Action named "Multi-Streamer Bot".
   - Add a "Code > Execute C# Code" sub-action.
   - Paste the contents of `Multi-Streamer-Bot.cs`.
   - Click "Compile" (Ensure you have added the references first).
3. **Configure**:
   - The bot will generate a config file at `.../Streamer.bot/data/Multi-Streamer Bot/config/config.json`.
   - Edit this file or use the [Example Configs](examples/).
4. **Run**:
   - Type `!ms system test` in chat to verify installation.
   - See the **[Deployment Guide](https://github.com/Sythsaz/Multi-Streamer-Bot/wiki/Deployment-Guide)** for details.

## ⚙️ Compatibility

**Runtime Environment**: C# 7.3 / .NET Framework 4.8 (Streamer.bot's current runtime)

## 📦 Release Assets

Each GitHub release is expected to include these assets:

- `Multi-Streamer-Bot.cs`
- `CHANGELOG.md`

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) and
[Code of Conduct](CODE_OF_CONDUCT.md).

## 🔒 Security

We take security seriously. See our [Security Policy](SECURITY.md) for details.

---

**Maintained by [Sythsaz](https://github.com/Sythsaz)**

**[Website Homepage](https://sythsaz.dpdns.org)**
