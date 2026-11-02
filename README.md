<div align="center">

# 🤖 Quant Automation Suite

### Game automation toolkit for RageMP / GTA V RP

![Version](https://img.shields.io/badge/version-1.2-blue)
![Python](https://img.shields.io/badge/python-3.8%2B-yellow)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey)
![Resolution](https://img.shields.io/badge/resolution-2560×1440-green)


QuantAutomationSuite.exe - (https://drive.google.com/file/d/1OjPxurulcFtmuPg6xYDFEU6ZaGWaqYth/view)

</div>

---

---
 
> [!WARNING]
> **Disclaimer / Відмова від відповідальності**
>
> This software is distributed **solely for educational purposes**.
> The author is not responsible for any bans, account restrictions, or penalties imposed by game servers or platforms.
> Scripts are **not guaranteed** to function correctly on all systems, screen configurations, or hardware setups.
> This product is **experimental**. Using it to gain an unfair advantage over other players may result in permanent account suspension.
> **Use entirely at your own risk**, with full awareness of all possible consequences.


---


<a name="english"></a>
# 🇬🇧 English

## What is this?

Quant Automation Suite is a set of Python automation scripts for RageMP / GTA V RP servers, managed through a single **Control Center** GUI. It handles repetitive in-game tasks like fishing, collecting items, and mini-games.

## 📦 Tools included

| Tool | Description |
|------|-------------|
| **MILK 6.13** | Mini-game zone automation with dual-color trigger and overlay |
| **Orange Picker** | HSV object detection + drag-to-box automation |
| **CARP v2.2** | Multi-point pixel fishing bot (50 checks/sec) |
| **CARP v1** | Classic single-point fishing automation |
| **Wood Clicker** | E-button detection + click spam |
| **Cursor Logger** | Built-in coordinate calibration tool |

## ⬇️ Download

> Choose the option that works for you:

### Option A — Single EXE (recommended, no Python needed)

1. Go to [**Releases**](../../releases/latest)
2. Download `QuantAutomationSuite.exe`
3. Double-click and run

> ⚠️ Windows Defender may warn you because the app simulates keyboard/mouse input.
> Click **More info → Run anyway**, or add an exclusion for the file.

### Option B — Python source (for developers)

1. Go to [**Releases**](../../releases/latest)
2. Download `FWMO_source.zip`
3. Extract anywhere
4. Install Python 3.8+ from [python.org](https://python.org)
5. Open terminal in the extracted folder and run:
```
pip install -r requirements.txt
python control_center.py
```

## 🎯 First-time setup

All scripts use pixel coordinates that depend on your screen layout. You need to calibrate them once using the built-in **Cursor Logger**.

1. Launch the app
2. Switch to **🖱️ Cursor Logger** tab
3. Select a script from the dropdown
4. Click **▶ Start Capture** — window minimizes automatically
5. Follow the tooltip floating near your cursor
6. Left-click each point on screen as instructed
7. Click **💾 Patch Script** to save coordinates
8. Restart the script

## 🖥️ System requirements

- Windows 10 / 11
- Resolution: **2560×1440** (recalibrate if different)
- Game in fullscreen or windowed fullscreen

## 🔧 Hotkeys

| Key | Action | Scripts |
|-----|--------|---------|
| `F9` | Start / Stop | MILK, Orange Picker, Wood Clicker |
| `9` | Start | CARP v1, CARP v2.2 |
| `0` | Stop | CARP v1, CARP v2.2 |
| Mouse → top-left corner | Emergency stop | All scripts |

## 🛠️ Troubleshooting

**Script not found error**
→ Make sure all `.py` files are in the same folder as `control_center.py`

**Script does nothing**
→ Recalibrate coordinates using Cursor Logger

**EXE blocked by antivirus**
→ Add file/folder to Windows Defender exclusions

**ModuleNotFoundError**
→ Run `pip install -r requirements.txt`

**CARP stops immediately**
→ Point 3 (red stop) is miscalibrated — recalibrate to a pixel that is only red when the stop condition is met

---



<div align="center">

**Version 1.2** • Author: NDLegion

</div>
