[**![Lang_farsi](https://user-images.githubusercontent.com/125398461/234186932-52f1fa82-52c6-417f-8b37-08fe9250a55f.png) فارسی**](README.fa.md)

# SnapBridge 🚀

A lightweight, fast web application for instantly sending and receiving images between two devices using a secure 6-digit code — no signup, no installation.

---

## 📌 GitHub Description

A lightweight web app for instant image transfer between devices using a secure 6-digit code. No signup, no installation.

---

## 🌐 Live Demo

👉 https://matindevelopment.github.io/snapbridge

---

## ✨ Features

- 📸 Send images from mobile or desktop
- 🔢 Secure 6-digit connection code
- 📥 Real-time image receiving
- 🧹 Automatic file cleanup
- ⚡ Fast and database-free
- 📱 Fully responsive (mobile-friendly)
- 🔊 Sound effects on send and receive

---

## 🧱 Tech Stack

- PHP (Vanilla, no framework)
- HTML5 / CSS3
- JavaScript (Vanilla)
- Browser-based QR Code Scanner

---

## 📂 Project Structure

```text
SnapBridge/
├── index.html
├── upload.php
├── list.php
├── cleanup.php
├── sender/
│   └── index.html
├── receiver/
│   └── index.html
├── assets/
│   └── mp3/
└── temp/
```

---

## ⚙️ Installation

1. Copy the project to your server or local environment:
   ```bash
   /var/www/html/snapbridge
   ```

2. Ensure PHP is enabled (PHP 7.4+ recommended)

3. Set write permission for the `temp` directory:
   ```bash
   chmod -R 777 temp
   ```

4. Open in browser:
   ```
   http://localhost/snapbridge
   ```

---

## 🔄 Root Folder Independence

The project does **not** depend on the root folder name.  
You can freely rename the main directory without breaking paths.

---

## 🔐 Security Notes

- Only image files (JPG / PNG) are accepted
- Randomized file names
- Temporary directories isolated per session
- Automatic cleanup on receiver exit

---

## 🚀 Future Improvements

- ⏱ Auto-delete after a time limit
- 📦 Support for non-image files
- 🔒 Server-side encryption
- ☁️ Cloud storage support
- 👥 Multi-user sessions

---

## 👨‍💻 Developer

Created by **Matin**  
GitHub: https://github.com/matinhajiseftjani400

---
## 💵 Donate
<a href="https://www.coffeebede.com/matindev"><img class="img-fluid" src="https://coffeebede.com/DashboardTemplateV2/app-assets/images/banner/default-yellow.svg" /></a>

---
