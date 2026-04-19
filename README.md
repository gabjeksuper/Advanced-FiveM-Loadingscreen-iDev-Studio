# 🚀 iDev Advanced Loading Screen

A premium, modern, and ultra-optimized Loading Screen for advanced FiveM servers. 
Created by server creators for server creators, it was designed to deliver a premium visual experience without impacting server or client performance.

## ✨ Core Features

* ⚡ **Extreme Performance (0.00ms):** No active loops on the client or server side. UI animations utilize hardware acceleration (GPU) to prevent FPS drops during server loading.
* 🛡️ **Anti-Exploit Security:** Integrated unique Token system and Rate Limiting. Completely immune to NUI Injections, Trigger Spamming (e.g., Eulen/RedEngine), and fake load events.
* 🎨 **100% Configurable (JS & LUA):** Customize colors, fonts, video, music, and content via a single `config.js` file, without ever needing to touch HTML or CSS.
* 🎵 **Advanced Music Player:** Built-in music playback system with a volume slider, perfect 144Hz UI sync, and cache memory (saves the player's preferred volume for future sessions).
* 📱 **Interactive Panels:** Full modules for Changelog (Updates), Rules (with a live search bar), Staff Team (with 3D cards and carousel), and interactive Keybinds.
* 🎥 **Native Video Backgrounds:** Perfectly optimized to prevent lag. Supports both local files (.mp4/.webm) and direct cloud hosting links (e.g., Fivemanage).
---

## 🛠️ Installation

1. Download the script folder from your CFX account.
2. Place the folder into your FiveM resources directory (e.g., `resources/[ui]/`).
3. Open your `server.cfg` and add this line at the beginning: ensure idev-loadingscreen
4. Replace the sample media files (videos, logos, songs) in the `html/assets/` folder with your own.
5. Configure the script (see the *Configuration* section below).
6. Start the server and enjoy your new loading screen!

---

## ⚙️ Configuration

The script is divided into two main configurations to ensure maximum security and ease of use.

### 1. Main File: `shared/config.js`
Here you can manage the aesthetics and content of the Loading Screen.
* **MainColor:** The primary color of your server (e.g., `#00d2ff`). The system will automatically calculate and apply shadows and glows based on this hex code.
* **FontType:** Choose between 4 built-in premium fonts (1: Poppins, 2: Montserrat, 3: Cal Sans, 4: Helvetica Now).
* **Updates, Rules & Team:** Fill in the arrays to automatically populate the UI menus.
* **Socials & Keybinds:** Enable or disable social links and custom keys.
*You can decide whether to enable/disable all navigation panels individually (Updates, Team, Rules, Keybinds) and social media links (including those embedded within the 3D staff cards) directly from the config file.*

### 2. Backend File: `shared/config.lua`
Here you set up the server-side functionality.
* **Framework:** Set to `STANDALONE`, `ESX`, `QBCORE`, or `QBOX`.
* **RateLimit:** Set the anti-spam request limit.

---

## 💡 Tips for Maximum Quality

* **Background Video:** To avoid black screens on lower-end PCs, do not use heavy .mp4 files. Convert your video to .webm format at 1080p60fps (max 20-30MB). For the best performance, we highly recommend hosting your video on a cloud service like Fivemanage. This ensures instant loading without lag for users with slower PCs and guarantees 100% compatibility with FiveM.
* **Team Images:** Use character images with a 3:4 aspect ratio and a transparent background to make them pop out of the cards and create a beautiful 3D effect.
* **Logo:** If your logo already has a built-in "glow" effect or a fixed shadow, set `LogoGlow: false` in `config.js` for a cleaner look.

---

## 💬 Support and Purchase
**Get the Script**
If you want to purchase the **iDev Advanced Loading Screen**, or if you want to check out our other premium scripts and security help, visit our store:
🌐 **[Join the iDev Discord Server](https://discord.gg/ZsMJYKpGDE)**
