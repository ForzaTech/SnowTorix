# ❓ Frequently Asked Questions (FAQ)

This section answers common questions about Tor Snowflake and v2rayN configuration.

---

## 🧅 Why does Tor Browser not connect?

Make sure that:

- Your internet connection is working.
- Snowflake Bridge is enabled.
- Tor Browser is updated to the latest version.

---

## ⚡ Why does v2rayN not connect?

Check the SOCKS5 configuration:
Address: 127.0.0.1
port:9150

Also make sure that Tor Browser is already connected.

---

## 🌐 Why do some applications not work?

When using SOCKS5 mode, only applications that support proxy settings can use the connection.

Enable **TUN Mode** in v2rayN if you need more system-wide support.

---

## 🐌 Why is the connection slow?

Tor network speed depends on:

- Available relays
- Snowflake availability
- Network conditions

Speed may change over time.

---

## 🔄 Do I need to keep Tor Browser open?

Yes. Tor Browser must remain running because it provides the local SOCKS5 proxy.

---

## 🔒 Is this a normal VPN?

No. This setup is based on Tor Browser, SOCKS5 proxy, and v2rayN.

It works differently from traditional VPN services.

---

## 📌 Where can I download the programs?

Always download software from official sources:

- Tor Browser:
https://www.torproject.org/

- v2rayN:
https://github.com/2dust/v2rayN/releases
