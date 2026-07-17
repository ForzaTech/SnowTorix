# ⚙️ Configuration Guide

This document provides the basic configuration details for connecting Tor Browser with v2rayN using a local SOCKS5 proxy.

---

## 🧅 Tor Browser Configuration

First, open Tor Browser and enable the **Snowflake Bridge** from the connection settings.

After successfully connecting to the Tor network, Tor Browser creates a local SOCKS5 proxy that can be used by other applications.

---

## ⚡ v2rayN SOCKS5 Configuration

Open v2rayN and add a new SOCKS profile.

Use the following settings:

**Proxy Type:**
SOCKS

**Address:** 127.0.0.1

**Port:** 9150


After entering these values, save the configuration and enable the connection.

---

## 🌐 TUN Mode

v2rayN provides a **TUN Mode** option.

By enabling TUN Mode, more system traffic can be routed through the configured connection, allowing more applications to use the connection without individual proxy settings.

---

## 🔍 Connection Check

Before using the connection:

- Make sure Tor Browser is connected.
- Make sure v2rayN SOCKS settings are:
  - Address: `127.0.0.1`
  - Port: `9150`
- Test the connection.

If the test is successful, the configuration has been completed.

---

## ⚠️ Notes

- Tor Browser must remain open while using the SOCKS5 connection.
- Connection quality depends on the Tor network and Snowflake availability.
- Settings may vary depending on software versions.
- Always download software from official sources.
