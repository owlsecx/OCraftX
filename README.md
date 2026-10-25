# 🦉 OCraftX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OCraftX** — Advanced Network Packet Crafter

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OCraftX is an advanced network packet crafting and inspection GUI for authorised lab use. Analysts can build ARP, ICMP, TCP, UDP, and raw frames, edit bytes in a hex view, and decode protocol fields before optional AF_PACKET send. Live capture, session history, and export support hands-on protocol education and defensive packet analysis.

---

## ✨ Features

- Multi-protocol frame crafting for ARP, ICMP, TCP, UDP, and RAW payloads
- Real-time colour-coded hex dump with an inline hex editor before send
- Protocol field decoder and inspector panel for structured review
- Live packet capture via AF_PACKET on Linux (privileged)
- Session history with PCAP export for later analysis
- Interface and local addressing helpers for lab topologies

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OCraftX
./OCraftX -V
./OCraftX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
