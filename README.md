# String Cleaner [BETA]

[![Version](https://img.shields.io/badge/Version-Beta_1.0-blue.svg)]()
[![Status](https://img.shields.io/badge/Status-In_Development-orange.svg)]()
[![Discord](https://img.shields.io/badge/Discord-Join_Server-7289DA.svg)](https://discord.gg/4KBUY5tF3r)

**String Cleaner** is an advanced, currently unreleased tool designed to seamlessly remove memory strings from active processes. It effectively bypasses intrusive PC checks and screenshare (SS) scans.

---

## ✨ Features

*   **Deep Memory Cleaning:** Scans and removes specific memory strings and traces left behind by other applications.
*   **Auto-Process:** Automatically detects and connects to your target processes upon launch.
*   **Smart Configuration:** Fully customizable via a simple `settings.json` file. Define your target processes, strings to clean, and operational delays easily.
*   **Auto-Remove:** Automatically cleans its own traces and terminates silently after the cleaning process is complete (Self-Destruct).
*   **PC Check Bypass:** Specifically built to evade detection from popular anti-cheat tools and manual PC checks.

---

## 🛠️ Configuration (`settings.json`)

The tool is completely driven by your `settings.json` file. Here is an example configuration:

```json
{
    "settings": {
        "auto-process": "notepad.exe",
        "auto-remove": "firststring,secondstring"
    }
}
```
![String Cleaner Showcase](https://github.com/Aaxenn/String-Cleaner/blob/main/showcase.png "String Cleaner Showcase")
