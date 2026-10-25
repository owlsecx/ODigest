# 🦉 ODigest

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **ODigest** — Deep Text Intelligence Engine ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ODigest is a deep text intelligence engine for frequency analysis, entropy, language cues, pattern extraction, and IOC-oriented scoring. It supports single-file and batch folder analysis, stego character hunts, and Base64 blob discovery so analysts can triage documents and dumps at scale. JSON output fits scripting pipelines.

---

## ✨ Features

- Frequency, entropy, readability, and NLP-oriented text scoring
- Pattern extraction and YARA-like rule matching helpers
- Zero-width steganography character scanning
- Base64 blob hunting and IOC scoring modes
- Single-file and batch folder analysis with top-N controls
- JSON stdout output for automation

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ODigest --file notes.txt
./ODigest --batch ./corpus --patterns --json
./ODigest --file dump.txt --stego --b64hunt --ioc-score
./ODigest --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
