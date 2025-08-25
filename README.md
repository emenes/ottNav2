# 📺 OTT Navigator Playlist — ottNav2

This repository provides a custom IPTV playlist for **OTT Navigator** (and other IPTV players such as TiviMate, Kodi, VLC).  
All streams are free-to-air channels and radio stations in Malaysia.  

> ⚠️ **Disclaimer**:  
> - All channels here are free-to-access and **must not be sold**.  
> - This project is for educational and personal use only.  
> - Main reference: [MIFNtechnology/siaranMy](https://github.com/MIFNtechnology/siaranMy) — full credit to them for inspiration.

---

## 📂 Repository Structure
- `channels/` — streaming files for each TV channel  
- `radio/` — streaming files for radio stations  
- `logo/` — channel & radio logos  
- `epg/` — Electronic Program Guide (EPG) in `.xml` and compressed `.xml.gz`  
- `index.m3u8` — main playlist file  

---

## 🚀 Usage Guide

### 1. Playlist
Add this URL to your OTT Navigator inside Provider (or any IPTV player):
`https://emenes.github.io/ottNav2/index.m3u8`

### 2. EPG (TV Guide)
Link to the EPG file:
`https://emenes.github.io/ottNav2/epg/epg.xml`



---

## 📌 Notes
- The playlist uses **`group-title`** to organize channels into categories, e.g. `TV Malaysia`, `Radio`, `Cartoon`.  
- File structure is kept modular (each channel has its own folder).  
- You are welcome to fork this repo and build your own custom playlist.  

---

## 📝 Credits
- Inspired by [MIFNtechnology/siaranMy](https://github.com/MIFNtechnology/siaranMy)  
- Maintained by [Emenes](https://github.com/emenes)  

---
