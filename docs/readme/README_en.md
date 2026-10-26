<div align="center">

<a href="https://blog.dei3c.com" target="_blank" rel="noopener noreferrer">
  <img src="https://github.com/user-attachments/assets/2830eb70-512c-4ddb-87ec-5213a6e465b1" alt="DEI Tech | DrvCeo Cleaner" height="70" />
</a>

<br /><br />

[繁體中文](../../README.md) · [简体中文](README_zh-CN.md) · **English**

# DrvCeo Cleaner

### Thoroughly remove DrvCeo residues, repair browser hijacks, and restore shortcuts
Designed for daily use, PC repair technicians, system deployment, and WinPE maintenance environments

[![Platform](https://img.shields.io/badge/Platform-Windows%207%20%7C%208%20%7C%2010%20%7C%2011%20%7C%20WinPE-blue?style=flat-square&logo=windows)](https://github.com/robert820/drvceo-cleaner)
[![License](https://img.shields.io/badge/License-Freeware-informational?style=flat-square)](../../LICENSE)
[![Type](https://img.shields.io/badge/Type-Freeware%20%7C%20Portable-success?style=flat-square)](#-download--usage)
[![GUI](https://img.shields.io/badge/GUI-Modern%20Native%20UI-blueviolet?style=flat-square)](#)
[![Download](https://img.shields.io/badge/Download-GitHub%20Releases-blue?style=flat-square&logo=github)](https://github.com/robert820/drvceo-cleaner/releases)

**Say goodbye to browser homepage hijacking, obsolete driver cache, and stubborn registry leftovers! Restore a pristine Windows environment with one click.**

[Overview](#-overview) · [Key Features](#-key-features) · [Screenshots](#-screenshots) · [Download & Usage](#-download--usage) · [System Requirements](#-system-requirements) · [FAQ](#-faq) · [Feedback](#-feedback--support)

</div>

---

## 📖 Overview

When building PCs, reinstalling Windows, or updating device drivers using "DrvCeo (驅動總裁)", have you ever experienced these frustrating issues?

- **Browser Homepage Hijacked**: Default homepages and new tabs in Chrome, Edge, and Firefox forcibly redirected to unauthorized third-party navigation portals.
- **Shortcut Trailing Parameters**: Desktop, Start Menu, and Taskbar shortcuts silently appended with unauthorized promotional URL query parameters.
- **Heavy Leftover Driver Cache**: System drives (C:) or external flash drives cluttered with massive uncompressed driver caches, temporary installers, and obsolete folders (`DrvCeo`, `SysCeo`, `DriverCeo`).
- **Residual Services & Registry Bloat**: Startup registry entries, background monitor services, and orphaned registry keys left behind, noticeably degrading boot times.

**DrvCeo Cleaner** is a native, lightweight, standalone utility crafted specifically to resolve these pain points, fully supporting Windows 7 through Windows 11 as well as WinPE offline environments. Purge residues and restore a clean, high-speed system with a single click!

---

## ✨ Key Features

### 1. ⚡ Deep Cleanup of DrvCeo Leftover Files & Caches
- Automatically scans all physical drives and external USB media, intelligently identifying leftover folders such as `DrvCeo`, `SysCeo`, `DriverCeo`, and `DrvCeo_Backup`.
- Uses advanced deletion routines that automatically strip read-only attributes and support extended-length paths (Win32 MAX_PATH bypass).

### 2. 🌐 Browser Homepage Restoration & Shortcut Disinfection (Anti-Hijack)
- Deeply inspects browser shortcuts across Desktop, Start Menu, Taskbar, and Quick Launch (supporting Chrome, Edge, Firefox, Brave, and other major browsers).
- Automatically detects and strips unauthorized promotional URL query parameters, restoring clean, official browser executables.
- Reverts hijacked registry homepage defaults and redirection values back to normal.

### 3. 🧹 Deep Registry & Background Service Purging
- Safely scans `HKEY_LOCAL_MACHINE` and `HKEY_CURRENT_USER` for Run/RunOnce auto-start items, residual services, and shell context menu extensions associated with DrvCeo.
- Completely cuts off background monitoring processes and prevent unwanted wakeups at startup.

---

## 📸 Screenshots

<div align="center">
  <img src="../../images/應用程式執行畫面.png" alt="DrvCeo Cleaner User Interface" width="720" />
</div>

---

## 📦 Download & Usage

### 📥 Download
Head to the [GitHub Releases page](https://github.com/robert820/drvceo-cleaner/releases) to download the latest binary.

### 🚀 Usage Guide
1. **Double-click `drvceo_cleaner.exe` to run**.
2. On the main interface, click the blue **"Start Cleanup"** button.
3. The application will scan drives, remove leftover driver caches, clean registry items, and repair browser shortcuts.
4. Once completed, click "Open Log" to review the detailed cleanup report.

---

## 🖥️ System Requirements

- **Operating System**: Windows 11 / 10 / 8.1 / 8 / 7 (SP1) & Windows PE (Preinstallation Environment)
- **Architecture**: Universal 32-bit (x86 / PE32, runs natively on both 32-bit and 64-bit Windows)
- **Privilege**: Administrator privileges (auto-elevated on double click)
- **Runtime**: Completely standalone, zero external dependencies (no .NET or VC++ Redistributable needed)

---

## ❓ FAQ

<details>
<summary><b>Q1: Is this software completely free?</b></summary>
A: Yes! This software is 100% Freeware. Individual users, enterprise IT staff, and computer repair workshops are free to use it for diagnosis and maintenance. However, selling, renting, or bundling this software with commercial paywalls is strictly prohibited.
</details>

<details>
<summary><b>Q2: Will the cleanup delete my actively functioning device drivers?</b></summary>
A: <b>Absolutely not!</b> This utility specifically targets temporary installation packages, uncompressed cache folders, logs, and unauthorized shortcut parameters left by DrvCeo. All hardware device drivers already installed into the Windows DriverStore remain untouched and fully operational.
</details>

<details>
<summary><b>Q3: Why might some antivirus software show a warning or false positive?</b></summary>
A: DrvCeo Cleaner is a clean, green application with zero backdoors or malicious code. Because it invokes low-level Windows APIs to repair corrupted shortcuts, stop orphaned background services, and clean system registry hives, some heuristic antivirus engines may flag it conservatively. If prompted, please add <code>drvceo_cleaner.exe</code> to your antivirus whitelist.
</details>

---

## 💬 Feedback & Support

- 🐛 **Bug Reports & Feature Requests**: Submit an issue on the [Issues page](https://github.com/robert820/drvceo-cleaner/issues).
- 🌐 **Official Website**: [https://blog.dei3c.com](https://blog.dei3c.com)

---

## 📄 License

This software is licensed under Proprietary Freeware terms. For full licensing terms, restrictions, and liability disclaimers, please refer to the [LICENSE](../../LICENSE) file.
