# Changelog

All notable changes to **MobileDeck** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/),  
and this project follows semantic versioning.

## [1.1.0.0-alpha] – Alpha Launch

### 🎉 Added
- **Advanced System Stats Panel** *(introduced in this version)*
  - Powered by a **custom hardware monitoring API** built using **LibreHardwareMonitor**
  - Displays real-time **GPU Metrics**:
    - Temperature, Load %, Memory usage, Power draw
  - Displays real-time **CPU Metrics**:
    - Temperature, Load %, Power draw, RAM usage
  - Live data updates for performance monitoring

### ✨ Improved
- Major improvements to overall app and desktop service stability
- More reliable Desktop ↔ Mobile communication loop
- **Fixed frequent disconnects** during active sessions
- Optimized stats polling intervals for higher accuracy and smoother graphs
- Reduced random freezes/crashes during rapid stat refresh cycles

### 🧪 Notes
- This is an **Alpha build** intended for internal/external testers
- Hardware metrics may vary based on vendor/driver support
- Power reporting may be limited on unsupported GPU/CPU models

---

## [1.0.0] – Initial Launch

### 🎉 Added
- Initial public release of MobileDeck
- Fully completed **Dock system**
- Desktop ↔ Mobile connectivity using QR-based pairing
- Background service support for stable communication
- Modern desktop UI optimized for daily use

### 🚧 In Progress
- System stats panel (CPU, RAM, performance metrics)
- Quick Settings (volume, brightness, system toggles)

### 🧪 Notes
- This is the first stable public version
- Some features are still under active development
- Minor bugs or UI inconsistencies may exist

---
