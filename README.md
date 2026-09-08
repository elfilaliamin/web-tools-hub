# 🛠️ Web Tools Hub

A sleek, lightweight, client-side web tools library hosted entirely on GitHub Pages. Built using React and Tailwind CSS, this project serves as a single-page portal to access various fast browser-based utilities.

![License](https://img.shields.io/github/license/YOUR_USERNAME/web-tools-hub?color=indigo)
![Deployment](https://img.shields.io/github/deployments/YOUR_USERNAME/web-tools-hub/github-pages?label=GitHub%20Pages)

---

## ✨ Features

- ⚡ **Client-Side & Fast:** Every tool runs completely in your browser — zero server latency and no data collection.
- 🎨 **Modern Dark UI:** Glassmorphism aesthetics with dynamic filtering, live search, and smooth animations.
- 📱 **Fully Responsive:** Optimized for desktop, tablet, and mobile viewing.
- 🔌 **Plug & Play Architecture:** Easy to append new custom `.html` utility pages into the repository.

---

## 🚀 Available Tools

| Tool | Category | Description |
| :--- | :--- | :--- |
| **Image to PDF** | Images | Convert PNG/JPG images into a single PDF document instantly. |
| **JSON Formatter** | Dev Tools | Prettify, validate, and parse raw JSON strings. |
| **Text Utilities** | Text | Word count, case converter, and text manipulation tools. |

---

## 🛠️ Tech Stack

- **Frontend:** React 18 (via CDN) & Babel Standalone
- **Styling:** Tailwind CSS (via CDN)
- **Icons:** Lucide Icons
- **Hosting:** GitHub Pages

---

## 📦 How to Add a New Tool

1. **Create your tool page:** Add a new standard HTML file to the repository root (e.g., `my-new-tool.html`).
2. **Register it in `index.html`:** Add your tool metadata object to the `TOOLS_DATA` array inside `index.html`:

```javascript
{
  id: "my-new-tool",
  name: "My New Tool",
  desc: "A brief explanation of what this tool does.",
  path: "my-new-tool.html",
  category: "Dev Tools", // "Images", "PDF", "Text", etc.
  icon: "Wrench"
}
