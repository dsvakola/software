# software
Official software catalog of Vidyasagar Robotics Academy. Browse, download, and explore desktop tools, operating systems, mobile apps, and institutional software developed by Prof. Dattaraj S. Vidyasagar &amp; Prof. Yash D. Vidyasagar with detailed features, screenshots, and repository links.
# 🏛️ Vidyasagar Robotics Academy — Software Catalog
### Developed by Prof. Dattaraj S. Vidyasagar & Prof. Yash D. Vidyasagar
🌐 [Official Website](https://vsa.edu.in/) • ✉️ softinquiry@vsa.edu.in

---

## 📑 Software Categories
1. [Archive & Compression Utilities](#-archive--compression-utilities)
2. [Operating Systems & Low-Level Systems](#-operating-systems--low-level-systems)
3. [Mobile & Android Applications](#-mobile--android-applications)
4. [Image & Media Utilities](#-image--media-utilities)
5. [Business & Institutional Management](#-business--institutional-management)
6. [Web Systems & CMS](#-web-systems--cms)
7. [Robotics, Automation & Embedded Systems](#-robotics-automation--embedded-systems)

---

## 📦 Archive & Compression Utilities

### 9-zip — Windows Archive Manager
**Repository:** [github.com/dsvakola/9-zip](https://github.com/dsvakola/9-zip)  
**Platform:** Windows 10/11 (x64) • **Stack:** Tauri v2, Rust, Vanilla TypeScript • **License:** Proprietary / Free

9-zip is a modern, ultra-fast archive manager for Windows engineered with Tauri v2 and Rust. It offers full support for 10 archive formats (9Z, 7Z, ZIP, TAR, GZIP, BZIP2, XZ, ZSTD, LZ4, and BROTLI), complete with an Explorer shell context menu, multithreaded compression, and AES-256 encryption.

What sets 9-zip apart is its proprietary **.9z self-healing format**. Utilizing Reed-Solomon error correction and VSA Integrity Seal (SHA-256 fingerprints), `.9z` archives can automatically repair corrupted sectors caused by faulty storage media or incomplete network downloads.

![9-zip Screenshot](https://raw.githubusercontent.com/dsvakola/9-zip/master/Release/9-zip-screenshots/main-window.png)

---

## 🖥️ Operating Systems & Low-Level Systems

### Vidyasagar OS (विद्यासागर)
**Repository:** [github.com/dsvakola/Vidyasagar-OS](https://github.com/dsvakola/Vidyasagar-OS) *(or pending upload)*  
**Architecture:** x86_64, ARM64, RISC-V • **Language:** Rust

Vidyasagar OS is an independent, memory-safe operating system built from scratch in Rust. It utilizes a hybrid kernel / Hardware Abstraction Layer (HAL) architecture, featuring a custom PE32+ loader and Win32 subsystem emulation layer designed to combine Windows-like familiarity with modern kernel safety.

---

## 📱 Mobile & Android Applications

### Pixel Lock (Power Button Companion)
**Repository:** [github.com/dsvakola/Pixel-Lock](https://github.com/dsvakola/Pixel-Lock)  
**Platform:** Android 9.0+ • **Language:** Kotlin / Java

Pixel Lock is a specialized Android utility engineered for devices with malfunctioning physical power buttons. It provides an intelligent face-down auto-lock mechanism, home screen 1-tap lock widgets, and quick-settings tiles. By triggering Android's native Accessibility lock instead of Device Admin lock, it preserves seamless in-display biometric fingerprint unlock.

---

## 🖼️ Image & Media Utilities

### VRA Intelligent Image Optimizer
**Repository:** [github.com/dsvakola/VRA-Intelligent-Image-Optimizer](https://github.com/dsvakola/VRA-Intelligent-Image-Optimizer)  
**Platform:** Windows • **Stack:** Tauri, Rust, TypeScript

A high-speed batch image optimization utility that compresses high-resolution photographs and graphics without visual degradation, ideal for web publishing and archival workflows.

---

## 🌐 Web Systems & CMS

### VRAPress
**Repository:** [github.com/dsvakola/VRAPress](https://github.com/dsvakola/VRAPress)  
**Stack:** PHP, MySQL

A lightweight, independent content management foundation built for educational websites and institutional publishing without heavy third-party bloat.
