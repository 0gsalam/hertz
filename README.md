# Refresh Rate Switcher (Rainmeter Skin)

A lightweight Rainmeter widget that lets you toggle your primary display's refresh rate between **60 Hz** and **144 Hz** directly from your desktop.

## 📋 Features

* **Dual Refresh Rate Toggle:** Dedicated buttons for 60 Hz and 144 Hz.

* **Hover Animations:** Dynamic border accent highlighting on mouse hover.

* **Zero Overhead:** Set to `Update=-1` so it consumes 0% CPU while idle.

* **Fully Parameterized:** Easily customize monitor resolution, accent colors, and path variables.

## 🛠️ Prerequisites

* [**Rainmeter**](https://www.rainmeter.net/) (v4.3 or higher recommended).

* [**QRes**](https://sourceforge.net/projects/qres/) (command-line display utility for Windows).

## 📁 Installation & Setup

1. **Download the Package:** Download the latest `.rmskin` file from the [Releases](../../releases) section.

2. **Install Skin:** Double-click the `.rmskin` file. Rainmeter will automatically unpack and install the skin.

3. **Verify QRes:** Ensure **QRes** is installed on your system (default path: `C:\Program Files (x86)\qres\QRes.exe`).

4. You can download the QRes in the qres branch

## ⚙️ Configuration

If your system uses a non-standard resolution or QRes install path, open `RefreshRate.ini` in any text editor and update the `[Variables]` section:

* **`Width` / `Height`:** Set your monitor's screen resolution (e.g., `1920` and `1080`).

* **`QResPath`:** Direct this to the exact location of `QRes.exe` on your system.

* **`Accent1` / `Accent2`:** Adjust the RGB colors for the button highlights.

## 🎮 Usage

* Click **60 Hz** to switch your monitor down for media or power saving.

* Click **144 Hz** to push your display to maximum refresh rate for high-FPS gaming.

* 