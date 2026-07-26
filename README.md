# Rx2HID Public

Official firmware and companion software releases for **Rx2HID**.

## Release Contents

Releases may include:

- **Rx2HID Utility**
  - Windows Installer (`Rx2HIDUtility-Setup-vX.X.X-win64.exe`)
  - macOS Disk Image (.dmg)
    - Apple Silicon (`Rx2HIDUtility-vX.X.X-macos-arm64.dmg`)
    - Intel (`Rx2HIDUtility-vX.X.X-macos-x64.dmg`)
  - Linux Distribution (`Rx2HIDUtility-vX.X.X-linux-x64.zip`)
    - Portable executable
    - One-time setup script (`install.sh`) for USB permissions

- **Firmware**
  - Firmware update files compatible with the official Rx2HID Utility

## Updating

The recommended way to update your device is through the **Rx2HID Utility**.

The Utility automatically checks for new firmware releases and downloads the appropriate files directly from this repository.

In most cases, **you do not need to manually download firmware files.**

## Installation

### Windows

1. Download the latest Windows Installer (`Rx2HIDUtility-Setup-vX.X.X-win64.exe`).
2. Run the installer and follow the on-screen instructions.
3. Launch **Rx2HID Utility** from the Start Menu or Desktop shortcut.

### macOS

1. Download the appropriate disk image for your Mac:
   - **Apple Silicon:** `Rx2HIDUtility-vX.X.X-macos-arm64.dmg`
   - **Intel:** `Rx2HIDUtility-vX.X.X-macos-x64.dmg`
2. Open the downloaded `.dmg`.
3. Drag **Rx2HID Utility** into the **Applications** folder.
4. Launch **Rx2HID Utility** from Applications.

### Linux

1. Download and extract `Rx2HIDUtility-vX.X.X-linux-x64.zip`.
2. Run the included setup script:
   ```bash
   ./install.sh
   ```
3. Enter your administrator password when prompted.
4. Unplug and reconnect your Rx2HID.
5. Launch the included `Rx2HIDUtility` executable.

> **Note:** The setup script installs a udev rule to allow access to the Rx2HID USB device. This only needs to be performed once per computer.

---

© KC3D LLC. All rights reserved.
