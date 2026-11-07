# QRes — Command-Line Display Mode Utility

[![Version](https://img.shields.io/badge/version-1.1-blue.svg)](https://github.com/)
[![License](https://img.shields.io/badge/license-As--Is-lightgrey.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-0078D6.svg)](https://microsoft.com)

**QRes** is a classic lightweight Windows command-line utility for dynamically changing screen resolution, color depth, and refresh rates directly from the Command Prompt, PowerShell, or batch scripts.

Originally created by Anders Kjersem in 2003, it remains a popular tool for automation, legacy application launching, and automated display profile switching.

---

## Features

- **Dynamic Resolution Switching:** Change horizontal and vertical screen dimensions on the fly.
- **Color Depth Control:** Adjust color bit depth (8-bit, 16-bit, 24-bit, or 32-bit).
- **Refresh Rate Adjustment:** Target specific display frequencies or query adapter defaults.
- **Display Mode Querying:** List all valid modes supported by your graphics hardware/monitor, or display your current settings.

---

## Command-Line Options

| Switch | Syntax Example | Description |
| :--- | :--- | :--- |
| `/x` | `qres.exe /x:1920` or `/x 1920` | Sets horizontal resolution width in pixels. |
| `/y` | `qres.exe /y:1080` or `/y 1080` | Sets vertical resolution height in pixels. |
| `/c` | `qres.exe /c:32` | Sets color bit depth (e.g., `8` = 256 colors, `16` = 16-bit, `32` = True Color). |
| `/r` | `qres.exe /r:144` | Sets the refresh rate in Hz (`0` = Adapter Default, `-1` = System Optimal). |
| `/l` | `qres.exe /l` | Lists all supported display modes for the current display configuration. |
| `/s` | `qres.exe /s` | Displays current display mode parameters. |

---

## Usage Examples

### 1. Change Resolution & Refresh Rate
Set display to Full HD ($1920 \times 1080$) at 60Hz:
```cmd
qres.exe /x:1920 /y:1080 /r:60