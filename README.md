# Nexus-V

<div align="center">

```
███╗   ██╗███████╗██╗  ██╗██╗   ██╗███████╗      ██╗   ██╗
████╗  ██║██╔════╝╚██╗██╔╝██║   ██║██╔════╝      ██║   ██║
██╔██╗ ██║█████╗   ╚███╔╝ ██║   ██║███████╗█████╗██║   ██║
██║╚██╗██║██╔══╝   ██╔██╗ ██║   ██║╚════██║╚════╝╚██╗ ██╔╝
██║ ╚████║███████╗██╔╝ ██╗╚██████╔╝███████║       ╚████╔╝
╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝        ╚═══╝
```

**AI-Powered Desktop Assistant for macOS**

[![Latest Release](https://img.shields.io/github/v/release/The-Nexus-V/nexus?style=for-the-badge&logo=github&color=blue)](https://github.com/The-Nexus-V/nexus/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-11.0+-black?style=for-the-badge&logo=apple)](https://www.apple.com/macos/)
[![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-M1%2FM2%2FM3%2FM4-orange?style=for-the-badge&logo=apple)](https://www.apple.com/shop/mac/apple-silicon)
[![License](https://img.shields.io/github/license/The-Nexus-V/nexus?style=for-the-badge)](LICENSE)

[🌐 Website](https://www.nexus-v.tech/) • [📥 Download](https://github.com/The-Nexus-V/nexus/releases/latest) • [📖 Documentation](https://www.nexus-v.tech/docs) • [🐛 Report Bug](https://github.com/The-Nexus-V/nexus/issues)

</div>

---

## ✨ Features

- 🤖 **AI-Powered Intelligence** - Advanced AI capabilities for smart assistance
- 🖥️ **Native macOS Experience** - Built specifically for Apple Silicon Macs
- ⚡ **Lightning Fast** - Optimized performance on M1/M2/M3/M4 chips
- 🔒 **Privacy First** - Your data stays on your device
- 🔄 **Auto Updates** - Differential updates for faster downloads
- 🎨 **Beautiful UI** - Modern, clean interface that feels native

---

## 📦 Installation

### Quick Install (Recommended)

Run this single command in your terminal:

```bash
curl -fsSL https://raw.githubusercontent.com/The-Nexus-V/nexus/main/install.sh | bash
```

The installer will:
1. ✅ Check and install required dependencies (Homebrew, wget)
2. ✅ Download the latest Nexus-V release automatically
3. ✅ Install the application to your Applications folder
4. ✅ Apply code signing for macOS security
5. ✅ Launch Nexus-V for you

### Manual Installation

1. **Download** the latest `.dmg` file from [Releases](https://github.com/The-Nexus-V/nexus/releases/latest)
2. **Open** the DMG and drag **Nexus-V** to your Applications folder
3. **If blocked by Gatekeeper**, run this command:
   ```bash
   xattr -cr /Applications/Nexus-V.app
   ```
4. **Launch** Nexus-V from your Applications folder

---

## 💻 System Requirements

| Requirement | Minimum |
|------------|---------|
| **macOS** | 11.0 (Big Sur) or later |
| **Processor** | Apple Silicon (M1, M2, M3, M4) |
| **RAM** | 8 GB recommended |
| **Storage** | 500 MB free space |

---

## 🔄 Updates

### Automatic Updates
Nexus-V includes built-in auto-update functionality. When a new version is available, you'll be notified and can update with a single click.

**Differential Updates**: Only changed components are downloaded, making updates faster and more efficient.

### Manual Update
Simply re-run the installation command:
```bash
curl -fsSL https://raw.githubusercontent.com/The-Nexus-V/nexus/main/install.sh | bash
```

---

## 📁 Release Files

| File | Description |
|------|-------------|
| `Nexus-V-*.dmg` | Disk image for manual installation |
| `Nexus-V-*.zip` | ZIP archive for auto-updates |
| `*.blockmap` | Differential update metadata |
| `latest-mac.yml` | Update metadata for electron-updater |

---

## 🛠️ Troubleshooting

### App won't open (Security Warning)
```bash
xattr -cr /Applications/Nexus-V.app
```

### Complete Reinstall
The installer automatically cleans previous installations. For manual cleanup:
```bash
rm -rf ~/Applications/Nexus-V.app
rm -rf /Applications/Nexus-V.app
rm -rf ~/Library/Application\ Support/Nexus-V
rm -rf ~/Library/Caches/Nexus-V
rm -rf ~/Library/Preferences/com.nexus-v.app.plist
```

### Check Running Processes
```bash
pgrep -x "Nexus-V" && killall "Nexus-V"
```

---

## 📜 Install Script Features

The `install.sh` script provides a seamless installation experience:

| Feature | Description |
|---------|-------------|
| 🔧 **Dependency Management** | Automatically installs Homebrew and wget if needed |
| 📥 **Auto-Download** | Fetches latest release from GitHub API |
| 🧹 **Clean Install** | Removes previous installations and cache |
| 🔐 **Code Signing** | Handles ad-hoc signing for macOS Gatekeeper |
| 🎨 **Beautiful UI** | Colorful terminal output with progress indicators |
| ⚡ **Retry Logic** | Smart download retry with fallback methods |
| 🚀 **Auto-Launch** | Launches the app after successful installation |

---

## 📄 License

This project is proprietary software. All rights reserved.

---

## 🔗 Links

- **Website**: [https://www.nexus-v.tech/](https://www.nexus-v.tech/)
- **GitHub**: [https://github.com/The-Nexus-V/nexus](https://github.com/The-Nexus-V/nexus)
- **Releases**: [https://github.com/The-Nexus-V/nexus/releases](https://github.com/The-Nexus-V/nexus/releases)

---

<div align="center">

**Made with ❤️ by the Nexus-V Team**

⭐ Star this repository if you find it useful!

</div>