# PredatorSense for Linux 🐧

This project brings PredatorSense-like functionality to Linux systems by enabling keyboard RGB control and Turbo key customization, powered through a custom kernel module and CLI tools. It’s a fork of the excellent [JafarAkhondali's original repo](https://github.com/JafarAkhondali/acer-predator-turbo-and-rgb-keyboard-linux-module), but with several tweaks for my own preference.

> ⚠️ **Disclaimer**: This is an unofficial project, built by reverse engineering. It directly interacts with WMI and hardware interfaces. You are responsible for your device—use it at your own risk.

---

## 🚀 Features in This Fork

This version of the project adds several new capabilities and fixes:

- ✅ **Turbo key profile switching**: Remapped the Turbo key to toggle between thermal profiles for now to avoid bugs.
- ✅ **Static RGB support for all zones**: New `--all-zones` flag lets you instantly apply a static RGB color across all keyboard zones.
- ✅ **Systemd startup integration**: Seamlessly applies your preferred RGB profile at boot—no more manual execution after every reboot.

## 🛠 Planned Features
1. 🕹️ **Turbo Key Dual Functionality** : <br>
Make the Turbo key context-aware for Short press = switch thermal profiles & Long press = toggle fan boost

2. 🌬️ **Custom Fan Speed Control**: <br>
Manual control over CPU and GPU fan curves—set exact speeds or create temperature-based profiles.

## 🔧 Installation
Detailed installation procedures and system requirements can be found in the original repo's [README.md](https://github.com/JafarAkhondali/acer-predator-turbo-and-rgb-keyboard-linux-module/blob/main/README.md)

## 💬 Feedback
Found a bug? Have a feature request? Want to help make this better?
Feel free to open an issue or submit a pull request. Contributions, fixes, and enhancements are always welcome!
