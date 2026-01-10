# 🧟 Project Zomboid B42 ID Helper (Alpha)

[![Live Demo](https://img.shields.io/badge/Demo-Live_Now-green?style=for-the-badge&logo=vercel)](https://nazaguerrero.github.io/pzidhelper//)

A specialized tool for Project Zomboid server admins to generate clean `servertest.ini` configurations with full support for **Build 42 backslash formatting**.

## 📸 Preview
![Tool Screenshot](https://github.com/nazaguerrero/pzidhelper/blob/main/IdToolb42.png)

---

## 🚀 Features

* **⚡ Smart Scraping:** Extracts Mod IDs and Workshop IDs directly from Steam.
* **🛡️ Policy Filter:** Automatically blocks "ModdingPolicy" and junk IDs from search results.
* **📂 B42 Ready:** Toggle between B41 and B42 formats with a single click.
* **🗺️ Auto-Map Detection:** Identifies map mods and populates the `Map=` line automatically.
* **🖱️ Drag & Drop:** Reorder your mods visually to set the perfect load order.

---

## 🛠️ How to Use

1. **Search:** Type the name of a mod in the search bar.
2. **Select:** Pick the mod from the dropdown list.
3. **Verify:** Check the "Map?" box if it's a map mod (the tool usually does this for you!).
4. **Copy:** Use the green buttons to copy your `WorkshopItems`, `Mods`, and `Map` lines.

> [!TIP]
> If a mod is being blocked by the "Junk Filter," simply paste the full Steam URL into the search bar to bypass the security check.

---

## 📋 Config Outputs Generated
The tool generates three separate lines for your `.ini` file:
* `WorkshopItems=` 
* `Mods=` (Supports `\ModID` for B42)
* `Map=` (Includes `Muldraugh, KY` as fallback)

---

## 🏗️ Installation (Self-Hosting)
Since this is a single-file tool:
1. Download `index.html`.
2. Open it in any modern web browser.
3. (Optional) Host it on **GitHub Pages** for easy access.
