# Android ADB Screenshot Capture Tool

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
[![ADB Required](https://img.shields.io/badge/ADB-v1.0.41%2B-orange)](https://developer.android.com/studio/releases/platform-tools)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

A Python script to capture Android screenshots via ADB, including workarounds for secured apps. Works with TECNO, Infinix, Xiaomi, and other Android devices.

## Features

- 📸 **One-click screenshots** via USB or Wi-Fi ADB
- 🛡️ **Bypasses FLAG_SECURE** protection (banking/DRM apps)
- ⏱️ **Timestamped filenames** for organized captures
- 📁 **Automatic folder creation**
- 🔄 **Wireless ADB support**

## Prerequisites

| Requirement           | Installation Guide                      |
|-----------------------|----------------------------------------|
| Python 3.7+           | [python.org](https://www.python.org/)  |
| ADB (Platform Tools)  | [Official Guide](https://developer.android.com/studio/releases/platform-tools) |
| Android Device        | USB Debugging enabled                  |

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/android-adb-screenshot.git
cd android-adb-screenshot

# Install dependencies
pip install pillow datetime
