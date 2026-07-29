# VoxCPM Local Studio — 1-Click GUI Desktop Suite (Windows & Mac)

> **Zero-Terminal Setup Environment for OpenBMB VoxCPM Real-Time Speech Generation**

[![Download Installer](https://img.shields.io/badge/Release-v1.0.4%20Stable-blue?style=for-the-badge&logo=windows)](https://gatamike.gumroad.com/l/voxcpm-windows-desktop-installer).
[![License](https://img.shields.io/badge/Build-Pre--Compiled%20GUI-green?style=for-the-badge)](https://gatamike.gumroad.com/l/voxcpm-windows-desktop-installer)

---

## 🚀 Overview

**VoxCPM Local Studio** is a pre-compiled, standalone graphical interface (GUI) wrapper for the **VoxCPM** real-time speech generation pipeline. 

Installing open-source speech models via standard CLI frequently throws terminal environment errors (`ModuleNotFoundError`, PyTorch CUDA version mismatches, C++ build tools missing). This release packs the entire runtime, HuggingFace model fetching pipeline, and audio routing dependencies into a **single, double-clickable desktop executable**.

---

## ⚡ Key Features

- **Zero-Command Launch:** No Python, `uv`, or terminal environment setup required.
- **Auto-Dependency Management:** Bundles pre-built PyTorch wheels and CUDA audio execution libraries.
- **Embedded Graphical UI:** Simple desktop dashboard to select input/output devices, voice cloning audio files, and generation speed.
- **One-Click Updates:** Automated fetch script for keeping up with upstream model checkpoints.

---

## 📥 Downloads & Installation

Due to binary packaging host limits, compiled `.exe` and `.dmg` installers are distributed via our direct build server below:

| OS Platform | Architecture | Status | Package Link |
|---|---|---|---|
| **Windows 10 / 11** | x64 / NVIDIA CUDA | Stable (v1.0) | [**Download 1-Click Installer ($49)**](https://gatamike.gumroad.com/l/voxcpm-windows-desktop-installer) |
| **macOS** | Apple Silicon (M1/M2/M3) | Stable (v1.0) | [**Download 1-Click Installer ($49)**](https://gatamike.gumroad.com/l/voxcpm-windows-desktop-installer) |

> *Note: Build packages are capped at 50 download licenses per release cycle to maintain fast model weight download speeds.*

---

## 🛠 Manual vs. GUI Comparison

| Installation Method | Technical Skill Required | Setup Time | Terminal Errors |
|---|---|---|---|
| **Raw GitHub Repo** | High (Python, PyTorch, CLI) | 45–90 Mins | Common |
| **VoxCPM Studio (GUI)** | **Zero (Double-click)** | **< 2 Mins** | **None** |

---

## 📞 Support & Issue Tracking

If you encounter issues during your 1-click execution, check the included `ReadMe_Setup.txt` inside your release download folder or use the link above to fetch the latest pre-compiled build patch.
