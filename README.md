<p align="center">
	<img src="logo.png" width="376" height="128" alt="BinarOS Logo" />
</p>

# BinarOS

**BinarOS** is a customized fork of Winlator — an Android application that lets you run Windows (x86_64) apps using Wine and Box86/Box64 — with Kurdish localization, enhanced stability, and automated GitHub integration.

---

## Installation

1. Download the latest APK: [GitHub Releases](https://github.com/itz-binar/BinarOS/releases)
2. Install it on your Android device
3. Launch and allow it to extract required files

---

## Video Previews

[![Play on YouTube](https://img.youtube.com/vi/ETYDgKz4jBQ/3.jpg)](https://www.youtube.com/watch?v=ETYDgKz4jBQ)
[![Play on YouTube](https://img.youtube.com/vi/9E4wnKf2OsI/2.jpg)](https://www.youtube.com/watch?v=9E4wnKf2OsI)
[![Play on YouTube](https://img.youtube.com/vi/czEn4uT3Ja8/2.jpg)](https://www.youtube.com/watch?v=czEn4uT3Ja8)
[![Play on YouTube](https://img.youtube.com/vi/eD36nxfT_Z0/2.jpg)](https://www.youtube.com/watch?v=eD36nxfT_Z0)

---

## Features

- Kurdish UI & configuration
- GitHub push automation (Termux-friendly)
- Improved Box64 performance & presets
- Compatible with Android 7+
- Root not required

---

## Tips

- Change Box64 preset to **Performance** for better FPS
- Install `.NET` via **Wine Mono** if needed
- Try setting: `MESA_EXTENSION_MAX_YEAR=2003` for older games
- Add `-force-gfx-direct` for Unity games
- Use **Force Fullscreen** for low-res games

---

## Auto Push Script (Termux)

1. Clone this repo:
```bash
git clone https://github.com/itz-binar/BinarOS.git
cd BinarOS
