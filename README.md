<div align="center">

<img src="assets/icon.svg" alt="MobileDeck Logo" width="120" />

<h1>
  <span style="color:#4CAF50;">Mobile</span><span style="color:#2196F3;">Deck</span>
</h1>

<p>
  <img src="https://img.shields.io/badge/Version-1.1.0.0--alpha-brightgreen" />
  <img src="https://img.shields.io/badge/Platform-Windows%20x64-blue" />
  <img src="https://img.shields.io/badge/Release-Alpha-orange" />
<img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FNilesh-Prajapat%2FMobileDeck&label=Visitors&countColor=%232ccce4&style=flat"/>
</p>

<p>
  <img src="https://img.shields.io/badge/For-Gamers-4CAF50?style=flat-square" />
  <img src="https://img.shields.io/badge/For-PC%20Testers-03A9F4?style=flat-square" />
  <img src="https://img.shields.io/badge/For-Developers-FFC107?style=flat-square" />
</p>

<i>Seamless control across devices — your desktop, reimagined.</i>

</div>

---

## 🚀 MobileDeck v1.1.0.0-alpha — Stats & Stability Upgrade

**MobileDeck v1.1.0.0-alpha** introduces the **first functional hardware stats panel**, providing real-time CPU and GPU telemetry directly on your mobile device.

This release focuses on:
- Hardware monitoring
- Stability improvements
- Reliable communication

This repository contains **release builds only**.  
Source code remains private.

---

## 📌 What is MobileDeck?

**MobileDeck** is a desktop companion application that allows you to monitor and control your PC using your phone.

It is designed for:
- 🎮 **Gamers** who need quick access without alt-tabbing
- 🧪 **PC testers** who require hardware telemetry
- 👨‍💻 **Developers** who want efficient remote controls

MobileDeck prioritizes **performance and privacy** without subscriptions or bloat.

> **Initialization Delay:**  
> After connecting, both the **App Dock data** and **hardware sensor stats** may take **30–60 seconds** to fully appear.  
> This happens during service startup and sensor initialization.
>
> **Troubleshooting (if mobile fails to connect):**  
> - If you're using **mobile hotspot**, try toggling the hotspot off/on and reconnecting.  
> - If still no connection, **temporarily disable Windows Firewall (Private + Public)** and test again. *(Re-enable after pairing.)*
> - ## 🔐 Firewall Setup
>   
> - MobileDeck requires **TCP ports 8000–8010** open for communication.
>   
> - ### Steps (Windows)
>   
> - 1. Open **Control Panel → System and Security → Windows Defender Firewall**
> - 2. Click **Advanced settings**
> - 3. Go to **Inbound Rules → New Rule**
> - 4. Select **Port**
> - 5. Choose **TCP**
> - 6. Enter:  8000-8010
> - 7. Click **Allow the connection**
> - 8. Select network types as needed
> - 9. Name the rule: `MobileDeck TCP`
> - 10. Repeat the same steps for **Outbound Rules**
> - 11. Restart MobileDeck.
> - 12. It will take 40 sec to fetch data.

## 🛠 First-Time Setup (How It Works)

1. **Launch the Desktop App**
2. Click **Connect** to show the QR code
3. Open the Mobile App and **scan the QR**
4. **Approve the device** on desktop
5. **Connected 🎉**

---

## 🧩 Launch Command Format (Desktop App)

The **Launch Command** field allows MobileDeck to trigger apps, websites, or URI handlers directly from your mobile device.

MobileDeck supports **three input types**:

---

### **1️⃣ Executable Path (EXE)**  
Runs local Windows applications.

**Format:**
C:\Path\To\App.exe


**Example:**
C:\Program Files\Google\Chrome\Application\chrome.exe


---

### **2️⃣ Website URL**  
Opens a website using your default browser.

**Format:**
https://website.com
www.website.com


**Example:**
www.google.com
https://google.com

---

### **3️⃣ App URI Scheme**  
Opens applications that register URI protocols (Steam, Discord, Spotify, Mail, etc.)

**Format:**
scheme://


**Examples:**
discord://
steam://open/library
spotify://
mail://


> You can view installed URI handlers in:
> **Windows Settings → Apps → Default Apps → Choose defaults by link type**

---

### 📌 Quick Reference Table

| Type     | Example                                          | Description            |
|----------|--------------------------------------------------|------------------------|
| EXE      | `C:\Program Files\VSCode\Code.exe`               | Launch VS Code         |
| Website  | `www.youtube.com`                                 | Open YouTube           |
| URI      | `discord://`                                     | Open Discord           |

---

### 📝 Notes

- Paths must exist on the PC
- URI schemes depend on installed apps

## ✨ New in v1.1.0.0-alpha

### 📊 **System Hardware Statistics**
Stats are now **enabled and functional**, displaying:

#### **CPU Metrics**
- Temperature
- Load %
- Power draw
- RAM usage

#### **GPU Metrics**
- Temperature
- Load %
- VRAM usage
- Power draw

Data updates in **real-time** for performance monitoring.

### ⚙️ **Stability Improvements**
- Fixed **frequent disconnects**
- Improved mobile ↔ desktop socket reliability
- Reduced UI freezes during intensive polling
- Cleaner service lifecycle handling

---

## 📱 Mobile App Status

Available screens:

- 📊 **Stats Screen** → **Fully functional**
- ⚙️ **Quick Settings** → **Not yet linked**

More functionality will be enabled in upcoming builds.

---

## ✨ Features from Previous Release (v1.0.0)

- 🧩 **Customizable App Dock**
- 📱 **Secure QR Pairing**
- ⚡ **Background Service**
- 🎨 **Clean & Immersive UI**

These remain available in **v1.1.0.0-alpha**.

---

## 🖼 Screenshots

### 🖥 Desktop App

<table>
  <tr>
    <td><img src="screenshots/pc1.png" width="480" /></td>
    <td><img src="screenshots/pc2.png" width="480" /></td>
  </tr>
  <tr>
    <td><img src="screenshots/pc3.png" width="480" /></td>
    <td><img src="screenshots/pc4.png" width="480" /></td>
  </tr>
  <tr>
    <td><img src="screenshots/pc5.png" width="480" /></td>
    <td><img src="screenshots/pc6.png" width="480" /></td>
  </tr>
</table>

### 📱 Mobile App

<table cellspacing="24">
  <tr>
    <td><img src="screenshots/mb1.jpg" width="480" /></td>
    <td><img src="screenshots/mb2.jpg" width="480" /></td>
  </tr>
  <tr>
    <td><img src="screenshots/mb3.jpg" width="480" /></td>
    <td><img src="screenshots/mb4.jpg" width="480" /></td>
  </tr>
</table>

---

## 🔜 Coming Soon

- ⚙️ **Quick Settings**
  - Volume
  - Brightness
  - System toggles

- 🎯 **Custom Actions**
  - Media controls
  - Shortcuts
  - Macros

---

## 🧪 Release Notes

- Version: **v1.1.0.0-alpha**
- Stage: **Alpha Test Build**
- Platform: **Windows (x64)**

Minor issues may exist depending on hardware support.

---

<div align="center">

<b>Welcome to <span style="color:#4CAF50;">Mobile</span><span style="color:#2196F3;">Deck</span> 🚀</b><br/>
More features and improvements are on the way.

</div>








