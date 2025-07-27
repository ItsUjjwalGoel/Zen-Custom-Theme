# 🎨 Zen Browser CSS Mods – Minimal Exit & Glass Effect

Custom `userChrome.css` tweaks for [Zen Browser](https://zen-browser.app) to improve its minimalism and design.
This repository currently includes:

* 🟢 **Minimal Exit** – A cleaner, distraction-free window control style
* 🔹 **Glass Effect** – Adds a blurred, translucent background like macOS/Windows acrylic

---

## ✨ Features

### 🔹 Minimal Exit Mod

* Replaces standard close/minimize/maximize buttons with **three minimal dots**
* On hover: each dot **fills with color and extends slightly**, providing subtle interactivity
* Ideal for those who want a **super clean, logo-free browser chrome**

### 🔹 Glass Effect Mod

* Gives the browser a **frosted glass UI**
* Background becomes **translucent with blur**, revealing soft glimpses of your system wallpaper
* Adds elegance without harming readability

---

## 🧑‍💻 Installation Guide

> ⚠️ This only works if Zen supports `userChrome.css` (as it’s built on Firefox)

1. **Open Zen Browser**
2. Navigate to `about:support`
3. Click **"Open Folder"** next to **"Profile Folder"**
4. Inside that folder:

   * Create a folder named `chrome` (if it doesn’t exist)
   * Create or edit a file called `userChrome.css`
5. Copy-paste the CSS from any of the themes (`Minimal Exit`, `Glass Effect`) into this file
6. Enable support:

   * Open `about:config`
   * Set `toolkit.legacyUserProfileCustomizations.stylesheets` → `true`
7. **Restart the browser** to apply changes

---

## 🥉 Using Multiple Mods

You can combine multiple themes by pasting them **in the same `userChrome.css` file**.
Each section is commented and separated for easy identification.

Example layout:

```css
/* ===== Minimal Exit Mod ===== */
/* Paste code here */

/* ===== Glass Effect Mod ===== */
/* Paste code here */
```

---

## 📁 Folder Structure

```
Zen-Minimal-exit/
│
├── minimal-exit/
│   ├── userChrome.css
│   └── preview.png
│
├── glass-effect/
│   ├── userChrome.css
│   └── preview.png
│
├── README.md         ← You are here
├── LICENSE
└── mod.json          (optional if submitting to Zen Mods)
```

---

## 📸 Previews

### 🔹 Minimal Exit

![Minimal Exit Screenshot](minimal-exit/preview.png)

### 🔹 Glass Effect

![Glass Effect Screenshot](glass-effect/preview.png)

---

## 🧑‍🎨 Author

Crafted with minimalism in mind by [Ujjwal Goel](https://github.com/ItsUjjwalGoel)
Feel free to use, adapt, or contribute!

---

## 🪪 License

This project is licensed under the MIT License.
