<div align="center">

# 🎯 Pinterest Pro Downloader

**A fast, powerful, and modern desktop application for bulk downloading Pinterest board content.**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=for-the-badge&logo=windows)](https://www.microsoft.com/windows)
[![Python](https://img.shields.io/badge/Python-3.12-yellow?style=for-the-badge&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-PolyForm%20Noncommercial-red?style=for-the-badge)](LICENSE)

** [🇮🇷 فارسی](README.md) | 🇬🇧 English**

</div>

---

## ✨ Key Features

- 📥 **Full Board Download:** Supports downloading the entire content of a board (even boards with 260+ pins).
- 🔒 **Private Boards Support:** Uses browser cookies (Chrome, Edge, Firefox) to access private boards without needing your password.
- 🎬 **All Formats Supported:** Automatically downloads images (JPG, PNG), GIFs, and videos (MP4) in the highest quality.
- ⚙️ **Auto FFmpeg Installation:** The app intelligently detects if FFmpeg is installed and automatically installs it if needed (for downloading long videos).
- 🖥️ **Graphical User Interface (GUI):** Works out-of-the-box without typing a single command in the terminal.
- 🚀 **Portable & Installer:** Available as a portable app (no installation) or a standalone installer with a desktop shortcut.

---

## ⚙️ Prerequisites

- **OS:** Windows 10 or Windows 11
- **Internet:** Stable internet connection (A VPN is required as Pinterest is blocked in some regions).
- **Browser:** (Optional) You must be logged into Pinterest in Chrome, Edge, or Firefox to download private boards.

---

## 🚀 Installation & Usage

### Option 1: Installer (Recommended)
1. Go to the [Releases](https://github.com/MortezaAbner/Pinterest-Pro-Downloader) section.
2. Download and run `PinterestPro-Setup-v1.0.0.exe`.
3. The app will install automatically and a shortcut will be created on your desktop.

### Option 2: Portable Version
1. Download `PinterestPro-Portable-v1.0.0.zip`.
2. Extract the zip file.
3. Run `PinterestApp.exe` (No installation required).

### Option 3: Run from Source Code
If you want to run the application directly from the source code, copy and paste the following commands into your terminal (CMD):

```bash
# 1. Clone the repository and navigate to the folder
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# 2. Install dependencies
pip install gallery-dl pyinstaller

# 3. Run the application
python PinterestApp.py
