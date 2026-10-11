<div align="center">

# 🕸️ Website Data Miner
### **Automation Made Simple — Extract Data at Scale**

[![Platform](https://img.shields.io/badge/Platform-Flutter-blue?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Language](https://img.shields.io/badge/Language-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![Build](https://img.shields.io/badge/Version-2.0.0-success?style=for-the-badge)](https://github.com/fuadk/Data-Miner)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**An advanced Flutter-based automation tool for mining data from websites using customizable parameters.**

---

[Explore Features](#-key-features) • [Visual Showcase](#-app-screenshot-gallery) • [Project Structure](#-project-structure) • [Tech Stack](#-tech-stack)

</div>

---

## 📖 Overview
**Website Data Miner** is a high-performance automation utility engineered for researchers, growth marketers, and data analysts to automate web crawling and extract targeted metadata. Supporting bulk URL ingestion via TXT or CSV formats, it delivers real-time progress monitoring, custom regex-powered extraction engines, and seamless tabular exports.

---

## 🖼️ App Screenshot Gallery

### 🏠 Home & Configuration
*The starting point for your mining sessions. Upload your website lists and customize extraction parameters.*

<p align="center">
  <img src="Photos/1.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Splash Screen">
  <img src="Photos/2.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Home Screen">
  <img src="Photos/3.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="File Uploaded">
</p>

---

### 📊 Smart Data Mining & Progress
*Real-time automation tracking with interactive charts and live progress indicators.*

<p align="center">
  <img src="Photos/4.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Automation Screen">
  <img src="Photos/5.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Progress Chart">
  <img src="Photos/6.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Extraction Logs">
</p>

---

### 📂 History & Data Insights
*Review your previous mining sessions and export results to multiple formats.*

<p align="center">
  <img src="Photos/7.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="History List">
  <img src="Photos/8.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Result Details">
</p>

---

### ⚙️ Customization & Themes
*Full control over app behavior, multi-language support, and seamless dark mode.*

<p align="center">
  <img src="Photos/9.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Settings Screen">
  <img src="Photos/10.jpg" width="200" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Dark Mode">
</p>

---

## ✨ Key Features

- 📁 **Bulk Import:** Seamlessly ingest large batches of URLs from `.txt` and `.csv` files.
- ⚙️ **Customizable Extraction:** Extract targeted parameters (Emails, Social Links, Meta Title, Description, Phone).
- 📊 **Real-Time Visual Tracking:** Monitor crawling speed, success rates, and queue health via interactive FL Charts.
- 🌓 **Dynamic Adaptive Theming:** Native Day/Night mode following system preferences with smooth color transitions.
- 🌐 **Multilingual Experience:** Full localized interface for both English and Bangla (বাংলা).
- 📂 **Multi-Format Export Engine:** Instantly export extracted datasets to structured Excel (.xlsx), CSV, or formatted PDF reports.

---

## 📁 Project Structure

```text
Data-Miner/
├── lib/
│   ├── controllers/    # Business logic & Automation handling
│   ├── models/         # Data structures & Settings models
│   ├── screens/        # UI Layers (Home, Automation, Settings, etc.)
│   ├── services/       # Exporting & Persistence services
│   ├── widgets/        # Reusable UI components
│   └── main.dart       # App entry point
├── Photos/             # App screenshots and visual assets
├── pubspec.yaml        # Dependencies & Configuration
└── README.md           # Project documentation
```

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Framework** | Flutter (SDK 3.x) |
| **Language** | Dart |
| **State Management** | Provider / Service-based Reactive Controllers |
| **Storage & Caching** | `shared_preferences` |
| **Visualization** | `fl_chart`, `percent_indicator` |
| **Animations** | `lottie`, `flutter_animate` |
| **Typography** | Google Fonts (Inter) |

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed ❤️ by Softece**

</div>
