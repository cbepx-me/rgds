# Modified Official System Online Upgrade Program for Anbernic RGds / RGdsplus

[![GitHub release](https://img.shields.io/github/v/release/cbepx-me/rgds)](https://github.com/cbepx-me/rgds/releases)
[![License](https://img.shields.io/github/license/cbepx-me/rgds)](https://github.com/cbepx-me/rgds/blob/main/LICENSE)

This project provides a **modified-version online upgrade solution** for the official Linux system of the **Anbernic RGds / RGdsplus** handheld. With a lightweight script, the device can directly download and install modified system upgrade packages over the network — no computer flashing required — giving the device improved features and a smoother experience.

## ✨ Features

- **One-click online upgrade**: After the device is connected to the network, it automatically detects the latest modified upgrade package and completes download and installation by following the prompts.
- **Resume support**: If the network is interrupted during download, the download can continue after recovery without starting over.
- **Real-time progress display**: The interface shows download speed, progress percentage, and remaining size in real time, making the upgrade process clear.
- **Automatic extraction and installation**: After download, the package is automatically extracted and the upgrade is performed without manual intervention.
- **Automatic reboot after upgrade**: The device automatically reboots after all upgrade operations are complete, quickly entering the new system.

## 📋 Prerequisites

Before using this upgrade program, make sure your device meets the following requirements:

| Requirement | Details |
|------|------|
| System version | Official Linux system **20260513 or newer** |
| Network connection | The device is connected to Wi-Fi and can access the Internet normally |
| Storage card | A TF card (microSD card) that can be read and written normally |

> **Note**: This program is only for **Anbernic RGds / RGdsplus** devices. Do not use it on other models.

## 🚀 Installation and Launch

### Step 1: Download the upgrade package

Download the latest upgrade package from the [Releases page](https://github.com/cbepx-me/rgds/releases):

```
RGds+plus_mod_v1.x.x.7z
```

### Step 2: Extract the files

Extract the downloaded ZIP file. You will get two items:

- `RGds+plus_mod_v1.x.x.sh` — the upgrade script
- `upgrade` — the folder required for the upgrade

### Step 3: Copy to the TF card

Copy both the **script** and the **folder** to either of the following directories on the TF card:

- `ROMS/APPS`
- `Ports`

### Step 4: Run on the device

1. Insert the TF card into the device and power it on.
2. Go to `Applications` → `Apps` or `Ports`.
3. Find and run **`Modified_System_Online_Upgrade`**.

## 🔄 Upgrade Process

After launching the upgrade program, follow these steps:

1. **Automatic update check**: After the program starts, it automatically checks for the latest online upgrade package on the server.
2. **Confirm and start downloading**: Press the **A button** on the main screen to confirm the update. The program starts downloading the upgrade file. **Resume support** is available during download, and the interface shows speed, progress, and remaining size in real time.
3. **Automatic extraction and installation**: After download is complete, the program automatically extracts the files and starts installing the upgrade.
4. **Automatic reboot**: After all upgrade operations are complete, the device automatically reboots.

> ⚠️ **Important**: After reboot, the device may enter the Android system. In this case, **long-press the power button**, select **Shutdown**, and then power it on again to enter the Linux system.

## 📁 Repository Files

| File | Description |
|------|------|
| `README.md` | Project documentation (this file) |
| `app_ver.json` | Application version information, used for online upgrade detection |
| `software_list.json` | Software list and metadata, used for the app store feature |

## 🛠️ FAQ

**Q: What should I do if power or network is interrupted during the upgrade?**

A: The upgrade package download supports resume. Run the upgrade program again to continue from the breakpoint. If the interruption occurs during extraction/installation, it is recommended to run the upgrade program again to complete the installation.

**Q: After the upgrade, the device booted into Android. How do I return to Linux?**

A: This is normal. Long-press the power button, select "Shutdown", and then power the device on again to enter the Linux system.

**Q: How can I confirm whether my system version meets the requirement?**

A: Go to system settings and check the current Linux system version. It must be **20260513 or newer**. For devices with an older version, please upgrade the system through official channels first.

**Q: What should I do if the upgrade package download fails or is very slow?**

A: Check whether the Wi-Fi connection is stable. Try switching the network environment and then run the upgrade program again.

## 🤝 Contributing and Feedback

- Found a bug or have a feature suggestion? Feel free to submit an [Issue](https://github.com/cbepx-me/rgds/issues).
- Want to contribute code improvements? Feel free to open a [Pull Request](https://github.com/cbepx-me/rgds/pulls).

## 📄 License

This project follows the license specified in the [LICENSE](https://github.com/cbepx-me/rgds/blob/main/LICENSE) file in the repository.

## 🙏 Acknowledgements

- Thanks to **cbepx-me** for developing and maintaining this project.
- Thanks to Anbernic for providing the official Linux system foundation for RGds / RGdsplus.

---

*Made with ❤️ by cbepx-me*
