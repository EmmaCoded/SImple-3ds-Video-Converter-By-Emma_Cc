# 🎮 Simple 3DS Video Converter
### **By Emma_Cc**

[![Version](https://img.shields.io/badge/Version-1.0-blueviolet.svg)](#)
[![PowerShell](https://img.shields.io/badge/Made%20with-PowerShell-blue.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](#)

A lightweight and efficient tool designed to convert any video into the native format compatible with the **Nintendo 3DS Camera Photo and Video Viewer**.

---

## ⚠️ Hardware Limits & Performance

This tool is pre-configured to respect the **Nintendo 3DS hardware limitations**. Please note:

* **Maximum Frame Rate:** **30 FPS**. The 3DS screen and native player cannot render more than 30 frames per second smoothly.
* **Maximum Quality (Bitrate):** **2000 kbps**. Exceeding this value will cause playback lag or "Unsupported Data" errors on the console.

---

## ✨ Key Features

* **🖱️ Drag & Drop Support:** Simply drag your video files directly onto the app to load them.
* **🎨 Dual Themes:** Full support for **Dark Mode** and **Light Mode**.
* **🌍 Bilingual:** Interface available in **English** and **Spanish**.
* **⚙️ Smart Encoding:**
    * **Custom FPS:** Set your own (up to 30) or use the 20/30 presets.
    * **Custom Bitrate:** Adjustable from 100 to 2000 kbps (Max limit).
    * **Aspect Ratio:** Choose between "Stretch" or "Keep Aspect Ratio" (adds black bars).
* **🔢 Auto-Indexing:** Automatically names files as `HNI_0001.avi`, `HNI_0002.avi`, etc., for instant recognition.

---

## 🚀 Installation & Requirements

1.  **FFmpeg:** You must place `ffmpeg.exe` in the same folder as the script.
2.  **PowerShell:** Run on Windows (standard user permissions).

---

## 🛠️ How to Use

1.  **Load Video:** Click **Browse** or **drag and drop** a file.
2.  **Adjust Settings:**
    * **Bitrate:** Use **2000 kbps** for maximum clarity (recommended).
    * **FPS:** Use **30 FPS** for smooth motion or **20 FPS** to save space.
3.  **Convert:** Press **CONVERT FOR 3DS**.
4.  **Transfer:** Move the file to your SD card:
    > `SD:/DCIM/100NIN03`

---

## 📊 Technical Specs (3DS Native)

| Parameter | Limit / Value |
| :--- | :--- |
| **Max Bitrate** | 2000 kbps (Hard Limit) |
| **Max FPS** | 30 FPS (Hard Limit) |
| **Video Codec** | MJPEG |
| **Audio Codec** | ADPCM IMA WAV |
| **Resolution** | 400x240 px |

---

## 📝 Notes
- The app generates a `3ds_converter_log.txt` to save your preferences and the last file index.
- For long videos, consider using the **Video Player for 3DS** link provided in the app.

---