<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Lunar-crush-purple" />
  <img src="https://img.shields.io/badge/Google-SheetAutomation-17A2B8?logo=gnometerminal&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" />
</p>
# 🚀 LunarCrush Token Capture & Google Sheet Updater 💎

## 🌟 Overview
This Python script automates the process of capturing a **fresh Bearer token** from LunarCrush and updating your **Google Sheet** with the token and timestamp ⏰.  
Runs in a **24-hour loop**, keeping your token always fresh for crypto data fetches 🪙📊.

It uses:  
- **Playwright** for browser automation 🌐  
- **Requests** for optional topic data fetches 💻  
- **gspread** & **Google Service Account** to update Sheets 📋  

---

## ✨ Benefits
- 🔄 **Auto Token Refresh** – never worry about expired tokens again  
- 🗂️ **Google Sheet Integration** – keep token & timestamp neatly logged  
- ⚡ **Reliable & Persistent** – runs every 24 hours automatically  
- 🛠️ **Lightweight & Extendable** – easy to add more crypto metrics  
- 💡 **Early Access** – ready to expand for fetching LunarCrush topic stats  

---

## 🏷️ Features
- Capture Bearer token from LunarCrush dynamically 🎯  
- Update Google Sheet cells (`B1` for token, `B2` for timestamp) 📝  
- Optional: Fetch and log crypto topic metrics like `SOL`, `BTC`, `ETH` 🔥  
- Fully automated 24-hour refresh loop ⏱️  

## The `v0`
- Automatic Generation of Auth Token and adding it in Google Sheet using Google Service Account.
---
v0 -  [📁 Source Code](https://github.com/deepakdhaka-1/lunarcrush/blob/main/v0).
---
---
## The `v1 & v1.1`
- Majority Data Scraping into Google sheet Real Time with top news (supported by window version and linux version)
---
v1 -  [📁 Window Version](https://github.com/deepakdhaka-1/lunarcrush/blob/main/v1.py).
---
v1.1 -  [📁 Linux Version](https://github.com/deepakdhaka-1/lunarcrush/blob/main/v1.1.py).

## ⚡ Installation
1️⃣ Clone the repo:
```bash
git clone [https://github.com/deepakdhaka-1/lunarcrush/
cd lunarcrush
```
