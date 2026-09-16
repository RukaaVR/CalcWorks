# CalcWorks

CalcWorks is a high-performance, stealth-focused web arcade designed to bypass strict network filters. By masquerading as a boring math/productivity utility and deploying via global developer CDNs, it remains unblocked while delivering a desktop-class gaming experience.

## ✨ Core Features

* **CDN Deployment:** Engineered to run flawlessly through the `jsDelivr` content delivery network, effectively bypassing standard web filters.
* **Native Execution Engine:** Uses direct native iframe loading rather than string injection. This completely bypasses origin security restrictions, allowing complex engines (Unity WebGL, Eaglercraft/Minecraft Service Workers) to run with full hardware acceleration.
* **The "Panic" Key:** Instantly vaporize the active screen. Pressing `~` (tilde) or `` ` `` (backtick) immediately redirects the browser tab to Google Classroom.
* **Tab Cloaking:** Active stealth cloak masks the document title and favicon as Google Docs to evade visual detection from a distance.
* **Matrix UI / Cyber OS:** Features a fully custom glassmorphism interface, CRT scanline overlays, magnetic hover physics, and dynamic theme switching.
* **Dynamic Asset Fetching:** Game assets, thumbnails, and the master database are fetched in real-time from external repositories, keeping this core repository incredibly lightweight.

## 🚀 How to Deploy (The jsDelivr Method)

To keep this portal unblocked, it is designed to be accessed through GitHub's open-source CDN mirror rather than a traditional web host.

1. **Fork or Upload:** Push `index.html` and the `html` folder to a **Public** GitHub repository.
2. **Construct the Link:** Use the following URL format to access your site through the CDN:
   
   ```text
   [https://cdn.jsdelivr.net/gh/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME@main/index.html](https://cdn.jsdelivr.net/gh/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME@main/index.html)
