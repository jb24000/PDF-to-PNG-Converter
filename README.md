# 📄➡️🖼️ PDF to PNG Converter

> Minimalist PWA for converting PDF files to high-quality PNG images

## ✨ Features

- 📱 **Installable PWA** - Works like a native app
- 🌐 **Works Offline** - No internet required after install
- 🖼️ **High Quality** - Multiple quality settings (1x, 2x, 3x)
- 📦 **Batch Download** - Download all pages at once
- 🎯 **Drag & Drop** - Simple file handling
- 📱 **Mobile Friendly** - Responsive design

## 🚀 Quick Setup

1. **Upload files** to your web server:
   ```
   index.html
   manifest.json
   sw.js
   icon-192x192.png
   icon-512x512.png
   icon-192x192-maskable.png
   ```

2. **Visit your site** and install the PWA

3. **Start converting** PDF files to PNG!

## 🎯 Usage

1. **Drop PDF file** or click to browse
2. **Select quality** (Standard/High/Ultra)
3. **Wait for conversion**
4. **Download individual** or **all pages**

## 📁 File Structure

```
pdf-converter/
├── 📄 index.html          # Main app
├── ⚙️ manifest.json       # PWA config
├── 🔧 sw.js              # Service worker
├── 🖼️ icon-192x192.png    # App icon
├── 🖼️ icon-512x512.png    # High-res icon
└── 🎯 icon-192x192-maskable.png # Android adaptive icon
```

## 🛠️ Tech Stack

- **PDF.js** - PDF processing
- **Canvas API** - Image rendering
- **Service Worker** - Offline functionality
- **Web App Manifest** - PWA features

## 📱 Browser Support

- ✅ Chrome/Edge (full PWA support)
- ✅ Safari (basic PWA support)
- ✅ Firefox (works, limited PWA features)

---

**Made with ❤️ for seamless PDF to PNG conversion**
