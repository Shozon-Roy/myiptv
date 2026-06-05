# 📺 MY IPTV — Ultimate Premium Streaming Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
[![Developer: Shozon Roy](https://img.shields.io/badge/Developed%20By-Shozon%20Roy-ff0055.svg?style=flat&logo=telegram)](https://t.me/devXshozon)
[![Status: Active](https://img.shields.io/badge/Status-Live-brightgreen.svg)]()

**MY IPTV** is a lightweight, high-performance, and open-source web application designed to stream live television channels directly inside your web browser. Built with a stunning cinematic, dark-themed user interface, it offers zero buffering overhead, intelligent search, dynamic category filtering, and real-time HLS adaptive streaming.

---

## 🚀 Live Demo

Experience the premium interface live in action here:  
🔗 **[Live Demo](https://shozon-roy.github.io/MY-IPTV/)**

---

## 📸 Preview & Interface

![MY IPTV Main Interface](https://raw.githubusercontent.com/shozon-roy/MY-IPTV/main/preview.png)  
### ✨ Key Features Overview:
*   **Cinematic Video Engine:** In-app sticky fluid player supporting adaptive `.m3u8` streams (HLS).
*   **Dynamic UI Architecture:** Beautiful grid styling with dynamic logo backups and interactive glowing hover properties.
*   **Ultra-Responsive Layout:** Perfectly engineered for Mobile, Tablet, and Desktop screens.
*   **Smart Global Search:** Instant client-side parsing filtering through dozens of networks locally.
*   **Floating FAQ Widget & Back-To-Top Matrix:** Streamlined accessibility panels featuring instant contact buttons.

---

## 🛠️ Technology Stack

This project leverages cutting-edge web technologies optimized for speed, aesthetics, and portability without bloated build steps:

*   **HTML5 & CSS3 Architecture:** Built with semantically accurate DOM structure.
*   **Tailwind CSS (via CDN):** Utilized for fast utility-first layout sculpting and rich premium gradients.
*   **Hls.js:** High-fidelity JavaScript library ensuring cross-browser support for HTTP Live Streaming protocols.
*   **FontAwesome Icons:** Integrated for uniform vector glyphs across panels.
*   **Native Fetch API:** Used to securely parse channel payloads from dynamic remote JSON databases asynchronously.

---

## 📂 Quick Installation & Setup

Since this is a fully client-side monolithic architecture, deployment takes less than 10 seconds.

1. **Clone the repository:**
```bash
   git clone [https://github.com/your-username/MY-IPTV.git](https://github.com/your-username/MY-IPTV.git)
   
 2. **Navigate into the project directory:**  
```bash

   cd MY-IPTV
   
 
3. **Run it instantly:**
Simply double-click the index.html file to run it in your favorite browser, or serve it via a local development server using VS Code Live Server.

. **Ensure your JSON schema matches the structure below::**
[
  {
    "name": "Channel Title",
    "logo": "[https://example.com/logo.png](https://example.com/logo.png)",
    "url": "[https://example.com/live/stream.m3u8](https://example.com/live/stream.m3u8)",
    "category": "sports"
  }
]
