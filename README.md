# 💻 ThinkBook 14 IIL – OpenCore EFI

OpenCore EFI files for **Lenovo ThinkBook 14 IIL**, built to run **macOS Ventura 13** 🍎

This repository focuses on achieving a stable and usable macOS experience on this specific laptop model. No unnecessary stuff — just what’s needed.

![Ice Lake CPU](https://github.com/prodbyeternal/ThinkBook14IIL-EFI/blob/main/Ventura.webp?raw=true)

---

## 🚀 Supported macOS Version

* **macOS Ventura 13**
* *Other macOS versions to be tested*

---

## 🧩 Hardware Specifications

| Component | Details                        |
| --------- | ------------------------------ |
| **CPU**   | Intel Core i5-1035G1 @ 1.0 GHz |
| **GPU**   | Intel UHD Graphics 620         |
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
| **HDMI**             | ❌ No   |
| **Touchpad**         | ❌ No   |
| **Battery Status**   | ❌ No   |
> 🔄 **Updates soon**

---

> [!NOTE]
> You will need to edit the Info.plist file inside the itlwm.kext file to gain internet access. The file in question is in itlwm.kext/Contents. Change the YOURPASSWORDHERE and YOURWIFINAMEHERE accordingly.

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
