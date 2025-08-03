# Bongo Cat ESP32 Web Installer

A web-based installer for the Bongo Cat ESP32 project - a cute digital pet that types with you and displays system stats.

## 🌐 Live Demo

Visit the web installer at: https://vostoklabs.github.io/Bongo_cat_webflasher/

## 📁 Repository Contents

- `index.html` - Main web installer page
- `manifest.json` - ESP Web Tools manifest for flashing
- `build/` - Binary files for ESP32 flashing
- `web resources/` - Images, GIFs, and screenshots
- `BongoCat_Release/` - Desktop application installer

## 🚀 Features

- **One-click ESP32 flashing** using ESP Web Tools
- **No Arduino IDE required** - flash directly from browser
- **Cross-platform desktop app** for Windows and Mac
- **Electron-based app** with modern interface
- **Responsive design** works on all devices
- **Professional installer interface**

## 📱 What is Bongo Cat ESP32?

Bongo Cat is a cute digital pet that will type with you. It can show:
- CPU and RAM usage
- Typing speed in words per minute
- Current time
- Adorable animations that respond to typing speed

## 🛠️ How It Works

1. **Flash ESP32**: Use the web installer to flash firmware
2. **Download Desktop App**: Install the cross-platform application (Windows or Mac)
3. **Connect**: App automatically finds and connects to ESP32 over network
4. **Type**: Watch your Bongo Cat respond to your typing!

## 📦 File Structure

```
bongo-cat-website/
├── index.html                 # Main installer page
├── manifest.json             # ESP Web Tools configuration
├── build/
│   └── esp32.esp32.esp32/   # Binary files for flashing
├── web resources/
│   ├── cat1.png             # Cat image for hero section
│   ├── typing.gif           # Normal typing animation
│   ├── typing fast.gif      # Fast typing animation
│   ├── sleeping.gif         # Sleep animation
│   ├── tray screenshot.png  # Desktop app tray
│   └── settings.png         # Settings screenshot
└── BongoCat_Release/
    ├── BongoCat_Setup.exe   # Windows installer
    └── BongoCat_Installer.zip # ZIP package with installer
```

## 🌐 Hosting

This website can be hosted on:
- **GitHub Pages** (recommended)
- **Netlify**
- **Vercel**
- Any static hosting service

## 🔧 Development

To run locally:
1. Clone this repository
2. Start a local web server (required for ESP Web Tools)
3. Open `index.html` in Chrome or Edge

## 📋 Requirements

- **Browser**: Chrome, Edge, or Opera (for Web Serial support)
- **ESP32**: Board with 2.4" TFT display
- **OS**: Windows 10/11 or macOS 10.14+ (for desktop app)

## 🎯 Open Source

This project is open source and costs around $10 to build with no soldering required.

