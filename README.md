# Workflowy Viewer

A lightweight, fast, and minimal web-based viewer for Workflowy HTML exports. Perfect for viewing large Workflowy exports that are too big to import back into Workflowy.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML](https://img.shields.io/badge/HTML-Single%20File-orange)
![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red)

---

## 📋 Table of Contents

- [Why This Tool Exists](#why-this-tool-exists)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Performance](#performance)
- [Browser Support](#browser-support)
- [FAQ](#faq)
- [Technical Details](#technical-details)
- [Use Cases](#use-cases)
- [Privacy & Security](#privacy--security)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🤔 Why This Tool Exists

### The Problem

When working with **Workflowy**, you might encounter these common issues:

| Issue | Description |
|-------|-------------|
| 📊 **Large Export Files** | You've exported your Workflowy data as HTML, but the file contains thousands of items |
| ⚠️ **Import Limitations** | Workflowy has size limits and may not allow you to re-import large files |
| 🔍 **Need to Review** | You want to view and search through your exported data without importing it back |
| 🤝 **Sharing** | You need to share your outline with others who don't have Workflowy access |
| 💾 **Backup Access** | You want to view old backups without cluttering your active Workflowy workspace |

### The Solution

**Workflowy Viewer** provides a simple solution:

- ✅ Open and view large Workflowy HTML exports instantly
- ✅ Navigate through your data with the same expand/collapse functionality
- ✅ Search through thousands of items smoothly
- ✅ Preserve all formatting, links, and structure
- ✅ Work completely offline - no server needed
- ✅ Handle files with 10,000+ items without hanging

---

## ✨ Features

### 🎯 Core Features

- **⚡ Fast Loading**: Chunked processing prevents browser hanging on large files
- **📌 Workflowy-Style Navigation**: Familiar bullet-point expand/collapse interface
- **🔍 Real-time Search**: Find items instantly with keyword highlighting
- **🔗 Link Preservation**: All hyperlinks remain clickable and functional
- **🎨 Format Retention**: Bold, italic, line breaks, and other formatting preserved
- **📦 Zero Dependencies**: Single HTML file - works anywhere

### 🎨 Design Features

- **Minimal & Clean**: Distraction-free interface focused on content
- **📖 Readable Text**: Optimized font sizes (14px) for comfortable reading
- **📱 Responsive**: Works on desktop, tablet, and mobile devices
- **✨ Smooth Animations**: Subtle transitions for better user experience

### ⚡ Performance Features

- **🔄 Chunked Processing**: Processes 50 items at a time to prevent UI freezing
- **⏱️ Debounced Search**: Smart search with 300ms delay to reduce lag
- **💾 Memory Efficient**: Optimized data structures for large datasets
- **🌐 No Backend Required**: Pure client-side JavaScript

---

## 🎬 Demo

### Before Using This Tool:

- ❌ Large Workflowy export (10,000+ items)
- ❌ Can't import back to Workflowy (file too big)
- ❌ Can't view structure easily
- ❌ Can't search through data
- ❌ No way to share with non-Workflowy users

### After Using This Tool:

- ✅ Load any size HTML export
- ✅ Navigate like Workflowy
- ✅ Search instantly
- ✅ Share with anyone
- ✅ Works offline

---

## 📥 Installation

### Option 1: Download and Use (Recommended)

1. **Download** the `workflowy-viewer.html` file
2. **Save** it to your computer
3. **Done!** Double-click to open in your browser

### Option 2: Clone Repository

```bash
git clone https://github.com/yourusername/workflowy-viewer.git
cd workflowy-viewer