# 🧟 Project Zomboid B42 ID Helper (Alpha)

[![Live Demo](https://img.shields.io/badge/Demo-Live_Now-green?style=for-the-badge&logo=vercel)](https://nazaguerrero.github.io/pzidhelper//)
[![Version](https://img.shields.io/badge/Version-Alpha_0.2-orange)](https://github.com/nazaguerrero/pzidhelper)

A specialized tool for Project Zomboid server admins to generate clean `servertest.ini` configurations with full support for **Build 42 backslash formatting**.

> ### 🚀 [Click here to open the Live Demo Page](https://nazaguerrero.github.io/pzidhelper//)

## 📸 Preview
![Tool Screenshot](https://github.com/nazaguerrero/pzidhelper/blob/main/IdToolb42B.png)

---

## 🚀 Key Features

* **⚡ B42 Formatting:** Instantly toggles between B41 and B42 (adds the required `\` before Mod IDs).
* **🛡️ Junk Filter:** Automatically detects and blocks "ModdingPolicy," "Version," and "Legal" IDs from search results.
* **🗺️ Auto-Map Detection:** Scans descriptions for map keywords and populates the `Map=` line automatically.
* **🖱️ Drag & Drop:** Visually reorder your mods to set the load order.
* **💡 Live Highlighting:** Output boxes highlight in real-time as you move mods to show exactly what changed.

---

## 🔍 Search & Reliability
![Search Demo](https://github.com/nazaguerrero/pzidhelper/blob/main/IDhelper.gif)
> [!IMPORTANT]
> The **Live Search** is currently in **Experimental Alpha**.

Because of how Steam handles external data requests, search results can occasionally be inconsistent.
* **Current Status:** Operational 🟢
* **Top Recommendation:** For 100% accuracy, **paste the Mod URL or Workshop ID** directly into the search bar. This bypasses the search filter and adds the mod exactly as it appears.

---

## 🛠️ How to Use

1. **Input:** Type a mod name to search or paste a Steam Workshop URL.
2. **Select:** If searching, pick the mod from the dropdown (the list closes automatically on selection).
3. **Organize:** Drag and drop mods to set your preferred load order.
4. **Copy:** Use the green buttons to copy your generated lines:
   * `WorkshopItems=`
   * `Mods=`
   * `Map=`

---

## ⚠️ Known Issues (Alpha)
* **Steam Rate-Limiting:** Rapid searching may cause Steam to temporarily block requests.
* **Non-Standard Formatting:** Some older mods use unusual text for their "Mod ID," which may require manual correction using the ✎ (Edit) button.
* **Policy Mods:** Some map mods include their modding policy under a "Mod ID" tag. Our filter catches most, but always double-check your list!

---
## 🚀 Recently Added (Alpha 0.2 - Testing Branch)
We've optimized the tool for large mod lists (30+ items).

- [x] **Sticky Control Bar**: Keep mod count and "Clear All" visible while scrolling.
- [x] **Smart Filter**: Search for mods and auto-scroll to their position without losing context.
- [x] **Index Numbering**: Every mod now has a sequence number (1, 2, 3...) for easier organization.
- [x] **Top/End Navigation**: Quick-jump buttons to navigate long lists instantly.
- [x] **INI Alignment**: Reordered output boxes to match `servertest.ini` (Mods > Map > Workshop).
- [x] **Policy Guard**: Automatic disclaimer/block when "Modding Policy" files are detected.
- [x] **Enhanced UI**: Custom scrollbars and glowing highlights for searched items.

*Created for the Project Zomboid Community with the help of "google.gemini" I'm not a programmer, this idea originated as a tool for personal use & fun project, which I later wanted to share with the community..Apologies if something isn't done correctly*
