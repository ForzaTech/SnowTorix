# 🌐 Tor Browser + Snowflake + v2rayN Guide

> 🇮🇷 فارسی | 🇺🇸 English

---

# 🇺🇸 English

## 🚀 Introduction

Welcome to this repository!

This project provides a comprehensive, beginner-friendly guide for configuring **Tor Browser** with the **Snowflake Bridge** and using its local **SOCKS5 Proxy** inside **v2rayN**.

The purpose of this repository is educational: to explain how Tor Browser exposes a local SOCKS proxy and how compatible applications can be configured to send their traffic through that proxy.

Whether you're learning how Tor works or experimenting with proxy-aware software, this guide walks through every step with screenshots, videos, and troubleshooting tips.

---

## ✨ Features

- 📹 Complete video tutorial
- 📸 Step-by-step screenshots
- 📥 Required software download links
- ⚡ Easy setup for beginners
- 🌉 Snowflake Bridge configuration
- 🧦 SOCKS5 Proxy configuration
- 🔧 v2rayN setup
- ❓ Troubleshooting guide
- 🌍 English & Persian documentation
- 💡 Frequently Asked Questions

---

## 🛠 What does this project do?

This guide explains how to:

1. Install Tor Browser.
2. Configure the built-in **Snowflake Bridge**.
3. Connect successfully to the Tor network.
4. Use Tor Browser's local SOCKS5 proxy.
5. Configure v2rayN to use that SOCKS5 proxy.
6. Optionally enable TUN mode in v2rayN so compatible system traffic can use the configured proxy, depending on your operating system and setup.

---

## 🌍 How does it work?

After Tor Browser successfully connects to the Tor network using the Snowflake bridge, it starts a local SOCKS5 proxy on your computer.

```
Application
      │
      ▼
v2rayN (SOCKS5)
      │
      ▼
127.0.0.1:9150
      │
      ▼
Tor Browser
      │
      ▼
Snowflake Bridge
      │
      ▼
Tor Network
      │
      ▼
Destination Website
```

Instead of connecting directly to websites, applications configured to use this local SOCKS5 proxy send their traffic through Tor Browser, which then forwards it into the Tor network.

---

## 📂 Repository Contents

📁 Video Tutorial

📁 Screenshots

📁 Download Links

📁 Documentation

📁 Troubleshooting

📁 FAQ

---

## ⚠️ Disclaimer

This repository is intended for educational purposes only.

Always comply with the laws, regulations, and terms of service applicable in your country and when using third-party software or networks.



## 📥 Download Tor Browser

Get the latest Tor Browser package for your operating system.

---

### 🪟 Windows (64-bit Portable)

[![Download Tor Browser Windows](https://img.shields.io/badge/Download-Tor%20Browser%20Windows-7D4698?style=for-the-badge&logo=windows)](https://www.torproject.org/dist/torbrowser/15.0.18/tor-browser-windows-x86_64-portable-15.0.18.exe)

---

### 🍎 macOS

[![Download Tor Browser macOS](https://img.shields.io/badge/Download-Tor%20Browser%20macOS-7D4698?style=for-the-badge&logo=apple)](https://www.torproject.org/dist/torbrowser/15.0.18/tor-browser-macos-15.0.18.dmg)

---

### 🐧 Linux (64-bit)

[![Download Tor Browser Linux](https://img.shields.io/badge/Download-Tor%20Browser%20Linux-7D4698?style=for-the-badge&logo=linux)](https://www.torproject.org/dist/torbrowser/15.0.18/tor-browser-linux-x86_64-15.0.18.tar.xz)

---

### 🤖 Android

[![Download Tor Browser Android](https://img.shields.io/badge/Download-Tor%20Browser%20Android-7D4698?style=for-the-badge&logo=android)](https://www.torproject.org/download/#android)

---

🛡️ **Official Source:** Tor Project  
🌐 https://www.torproject.org/download/
