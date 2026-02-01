# 💻 ThinkBook 14 IIL – OpenCore EFI

OpenCore EFI files for **Lenovo ThinkBook 14 IIL**, built to run **macOS Ventura 13** 🍎

This repository focuses on achieving a stable and usable macOS experience on this specific laptop model. No unnecessary stuff — just what’s needed.

*Screenshot to be uploaded.*

---

## 🚀 Supported macOS Version

* **macOS Tahoe**
* *Supports from macOS Monterey up to Tahoe*

---

## 🧩 Hardware Specifications

| Component | Details                        |
| --------- | ------------------------------ |
| **CPU**   | Intel Core i5-1035G1 @ 1.0 GHz |
| **GPU**   | Intel Iris Graphics            |
| **RAM**   | 8 GB DDR4                      |

---

## ✅ What’s working?

| Feature              | Status |
| -------------------- | ------ |
| **Wi‑Fi**            | ✅ Yes  |
| **Bluetooth**        | ✅ Yes  |
| **GPU Acceleration** | ✅ Yes  |
| **Keyboard**         | ✅ Yes  |
| **USB**              | ✅ Yes  |
| **Battery Status**   | ✅ Yes  |
| **HDMI**             | ❌ No, won't be supported. |
| **Touchpad**         | ❌ No, work in progress.   |
> 🔄 **Updates soon**

---

> [!NOTE]
> You will need to edit the Info.plist file inside the itlwm.kext file to gain internet access. The file in question is in itlwm.kext/Contents. Change the YOURPASSWORDHERE and YOURWIFINAMEHERE accordingly.
> Or you can use the included itlwmPass.py Wi-Fi injector to edit the kext for you. (Works on Windows, Linux)

---

## 🛠️ Bootloader used

* **OpenCore**

---

## 👥 Credits

* **@devbyreqqel**
* **@prodbyeternal**

---
> [!WARNING]
> This EFI is made for **this exact hardware configuration**.
> If your ThinkBook differs, you’ll need to adjust the config accordingly.
> Also, Ice Lake CPU's suck, never doing Ice Lakes again.
