# 🔧 OCraftX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ONetwork%20%2F%20Packet%20Crafting-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-tkinter%20(stdlib)-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OCraftX** is a clean, modern GUI tool for crafting ARP Request packets. It provides real-time hex dump with colored sections (Ethernet + ARP + Padding), auto-fill for local MAC/IP, copy options (Hex, Raw Bytes, Scapy snippet), and raw frame transmission on Linux (requires root).

**Designed for authorized network testing and Layer-2 protocol research.**

---

## 📌 Overview

OCraftX simplifies ARP packet crafting with a professional dark-themed interface. It automatically builds a valid Ethernet + ARP Request frame, shows a detailed colored hex dump, and allows easy export or transmission.

Perfect for ARP spoofing simulations, network discovery testing, and educational Layer-2 experiments.

---

## 🖥️ Main Features

- **ARP Request Builder** — Full control over Sender MAC, Sender IP, Target IP
- **Auto-Fill** — Detects and fills local MAC and IP automatically
- **Colored Hex Dump** — Ethernet header, ARP packet, and padding clearly separated
- **Export Options**:
  - Copy Hex Dump (annotated)
  - Copy Raw Bytes (`\x` escaped)
  - Copy Scapy Snippet (ready-to-run code)
- **Raw Frame Transmission** — Send directly via AF_PACKET (Linux, root required)
- **Clean GUI** — Dark OwlSec theme with clear sections and status feedback
- **Safety Check** — Authorization checkbox before sending

---

## ⚙️ Requirements

- **tkinter** (included with Python)
- **Linux** recommended (for raw frame transmission)
- **Root / sudo** — Required to send raw Ethernet frames

**Standalone executable** — Runs as `./OCraftX` when built with PyInstaller.

---

## 🚀 Usage

```bash
sudo ./OCraftX

📁 Output

Live GUI — Real-time colored hex dump and construction log
Clipboard Exports:
Hex Dump (annotated with section labels)
Raw Bytes (\x escaped string)
Scapy Snippet (ready-to-paste Python code)


No files are saved automatically — all output is available via copy buttons.

📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
AUTHORISED NETWORK TESTING & LAYER-2 PACKET CRAFTING USE ONLY
