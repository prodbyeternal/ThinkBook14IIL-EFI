# 💻 ThinkBook 14 IIL – OpenCore EFI

> [!NOTE]
> This EFI is soon going to be transfered to ThinkDifferentInc/ThinkBook-14IIL, more info soon.

OpenCore EFI files for **Lenovo ThinkBook 14 IIL**, built to run **macOS Sequoia (15)** 🍎

This repository focuses on achieving a stable and usable macOS experience on this specific laptop model. No unnecessary stuff — just what’s needed.

<img width="1920" height="1080" alt="Ventura2" src="https://github.com/user-attachments/assets/5959c44e-815d-47bd-a511-60eb04b4d689" />


---

## 🚀 Supported macOS Version

* **macOS Sequoia**
* *Supports from macOS Monterey up to.....*

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


---

> [!NOTE]
> You will need to edit the Info.plist file inside the itlwm.kext file to gain internet access. The file in question is in itlwm.kext/Contents. Change the YOURPASSWORDHERE and YOURWIFINAMEHERE accordingly.
> Or you can use the included itlwmPass.py Wi-Fi injector to edit the kext for you. (Works on Windows, Linux)

> [!NOTE]
> If you want a HDMI connection, you will have to buy a USB3.0 to HDMI adapter with macOS Driver support.


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
