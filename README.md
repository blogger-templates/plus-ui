<div align="center">

# ⚡ Plus UI – Premium Blogger Template
### The Ultimate Solution for Professional Publishing

[![Blogger](https://img.shields.io/badge/Platform-Blogger-orange?style=flat&logo=blogger)](https://www.blogger.com)
[![Version](https://img.shields.io/badge/Version-v3.2.0-blue?style=flat)](https://github.com/blogger-templates/Plus-UI-V3.2.0/releases)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE)
[![Size](https://img.shields.io/badge/Size-~50KB-yellow?style=flat)]()

[Live Demo](https://plus-ul.blogspot.com/) • [Download](https://github.com/blogger-templates/Plus-UI-V3.2.0/releases) • [Documentation](https://plus-ul.blogspot.com/2024/10/getting-started-and-installation.html) • [Report Bug](https://github.com/blogger-templates/Plus-UI-V3.2.0/issues)

</div>

---

## 📖 About Plus UI
**Plus UI** is a cutting-edge, open-source Blogger theme designed for speed, SEO, and flexibility. Unlike traditional themes, Plus UI integrates **Hybrid AMP**, **PWA (Progressive Web App)** capabilities, and a **Safelink system** directly into the core.

Built for **developers** who want full control, it utilizes a modular widget-based settings system, meaning you can configure almost everything from the Blogger Layout menu without touching code.

---

## 🚀 Key Features

### ⚡ **Core Performance**
* **Hybrid AMP & Non-AMP:** Automatically serves the best version based on user device and settings.
* **Lighthouse Optimized:** Consistently scores 90-100 on PageSpeed Insights.
* **Native Lazy Loading:** Optimized handling for images, iframes, and YouTube embeds.
* **PWA Ready:** Built-in manifest and service worker logic for "Add to Home Screen" functionality.

### 🎨 **Design & UI**
* **System/Toggle Dark Mode:** Auto-detects OS preference with a manual toggle switch.
* **Tailwind-like Utility Classes:** Custom CSS variables for easy styling.
* **Responsive Layout:** Mobile-first architecture that scales from phones to 4K screens.
* **Infinite Scroll / Pagination:** Switch between Numbered, Load More, or Infinite Scroll.

### 🛠️ **Advanced Tools (Built-in)**
* **🛡️ Safelink System:** Integrated encrypted link redirection with countdown timer (Great for download sites).
* **🚫 Anti-AdBlock:** Gentle popup asking users to disable ad blockers.
* **🚧 Maintenance Mode:** Switch the site offline with a custom "Coming Soon" screen via Layout.
* **🍪 Cookie Consent:** GDPR compliant popup out of the box.

---

## 🔮 Roadmap: Coming in v3.7.0
We are actively working on the next major update. Here is a sneak peek at what's coming:

- [ ] **Core Web Vitals Rewrite:** Complete CSS overhaul to minimize Cumulative Layout Shift (CLS).
- [ ] **New Hero Headers:** 3 new styles for the homepage feature section.
- [ ] **Mega Menu:** Native support for dropdown mega menus without complex HTML.
- [ ] **Comment System v2:** Improved support for Disqus and Facebook comments integration.
- [ ] **Auto-TOC:** Enhanced Table of Contents that auto-generates from H2/H3 tags.

> **ETA:** Late 2025. Stay tuned!

---

## 🛠️ Installation Guide

You can install the theme using the standard upload method or the manual HTML replacement method.

### Option 1: Upload (Easiest)
1. Download the `.xml` file from the [Releases Page](https://github.com/blogger-templates/Plus-UI-V3.2.0/releases).
2. Go to **Blogger Dashboard** → **Theme**.
3. Click the **▼** arrow next to Customize.
4. Select **Restore** → **Upload** → Select `plus-ui-v3.2.0.xml`.

### Option 2: Manual HTML Replacement (Recommended for Clean Install)
If the upload method fails, use this method to ensure no old code remains.

1. Open the downloaded `plus-ui-v3.2.0.xml` file in a text editor (Notepad, VS Code, etc.).
2. Select all code (`Ctrl + A`) and copy it (`Ctrl + C`).
3. Go to **Blogger Dashboard** → **Theme**.
4. Click the **▼** arrow next to Customize and select **Edit HTML**.
5. Click anywhere inside the code editor and select all (`Ctrl + A`).
6. Press `Delete` to remove the old code completely.
7. Paste the copied code (`Ctrl + V`) into the editor.
8. Click the **Save** (Floppy Disk icon) button top right.

---

## 🙋 Frequently Asked Questions (FAQ)

### **Q: Why are my posts not showing on the Home Page?**
**A: This happens because your post content is too "heavy" for Blogger's auto-pagination.**

Blogger has a limit on the amount of data it fetches for the homepage. If your posts contain large images, lots of text, or scripts in the very first section, Blogger might only load 1 or 2 posts (or none at all) to keep the page load speed fast.

**✅ The Fix: Use the Jump Break**
You must tell Blogger where to "cut off" the preview.
1. Open your post in the **Blogger Editor**.
2. Place your cursor after the first paragraph or image.
3. Click the **"Insert Jump Break"** icon (it looks like a broken line `---`).
   - *Alternatively*, in HTML view, type `` manually.
4. Update the post.

This ensures Blogger only loads the summary on the homepage, allowing all your posts to appear correctly.

### **Q: Is this template compatible with mobile phones?**
**A:** Yes! Plus UI is fully responsive and mobile-first.

### **Q: Can I monetize this with AdSense?**
**A:** Absolutely. It includes optimized slots for In-Feed, Article Top/Bottom, and Sticky Sidebar ads.

---

## 🧩 Shortcodes
Plus UI supports shortcodes inside your posts to create rich content elements:

| Feature | Shortcode / Class | Description |
| :--- | :--- | :--- |
| **Buttons** | `<a class="button">Link</a>` | Standard theme button |
| **Download** | `<div class="dlBox">...</div>` | Styled download box |
| **Alerts** | `<div class="alert info">Msg</div>` | Info, Success, Warning, Error alerts |
| **Code** | `<pre><code>...</code></pre>` | Auto syntax highlighting |
| **Spoiler** | `<details class="sp">...</details>` | Collapsible spoiler text |

---

## 🤝 Contributing & Support

This project is maintained by **Deo Kumar**.

* **Found a bug?** Open an [Issue](https://github.com/blogger-templates/Plus-UI-V3.2.0/issues).
* **Want to contribute?** Fork the repo and submit a Pull Request.
* **Need Help?** Check the [Documentation](https://plus-ul.blogspot.com/2024/10/getting-started-and-installation.html).

---

<div align="center">
  <sub>Made with ❤️ by Fineshop Design</sub>
</div>
