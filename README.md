# Qidi Q2 Mainline Klipper Configuration

This repository provides custom Klipper configuration files optimized for the **Qidi Q2 3D printer and Qidi Box**, built for the **Qidi Q2 Mainline Klipper ecosystem** from [cedbossneo/q2-offload](https://github.com).

---

## ℹ️ Project Information

The `q2-offload` framework offloads heavy computing tasks (such as Moonraker, Happy Hare, and web interfaces) to an external Linux host while the printer's board manages low-level MCU links, the touchscreen (HelixScreen), and the webcam.

---

## 🛠️ Supported Features

* **Multi-MCU Management:** Pre-configured for the mainboard, toolhead, and Qidi Box MCUs.
* **Advanced Probing & MMU:** Integrated load cell probing and Happy Hare MMU setup with Spoolman mapping.
* **Drying & Macros:** Smart filament drying safety features alongside utility macros for purge buckets and recovery.

---

## ⚠️ Essential Details

* **Network:** Use a wired ethernet link for the host to avoid "Timer too close" errors; Wi-Fi is not recommended.
* **Box Limits:** The Box heater is capped at half power with thermal safety cutoffs, and static LED animations are disabled to prevent MCU shutdowns.

---

## 🤝 Credits & License

* Base architecture by [cedbossneo/q2-offload](https://github.com).
* Distributed under the **GPL-3.0 License**.
