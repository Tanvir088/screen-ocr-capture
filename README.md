# screen-ocr-capture
A Windows-only Python tool that captures a selected screen area, extracts numbers using OCR, and automatically saves screenshots with intelligent filenames.
# 📸 Screen OCR Capture Tool

A **Windows-only Python automation tool** that allows you to:

- Select a screen area for **image capture**
- Select a screen area for **text (number) OCR**
- Automatically extract numbers using **Tesseract OCR**
- Use the detected number as the **image filename**
- Prevent filename overwrite intelligently
- Capture screenshots using a **floating draggable button**

---

## 🚀 Features

- 🖱️ Drag-to-select screen areas
- 🔍 OCR-based number detection
- 🧠 Auto filename cleanup (removes last digit safely)
- 📂 Custom save folder selection
- 🪟 Floating always-on-top capture button
- 🖼️ High-DPI display support (DPI aware)

---

## 🖥️ Supported Platform

- ✅ Windows 10 / 11 only  
(Due to `ctypes.windll` and `ImageGrab` usage)

---

## 🔧 Requirements

- Python **3.8+**
- Tesseract OCR (Windows)

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/screen-ocr-capture-tool.git
cd screen-ocr-capture-tool
