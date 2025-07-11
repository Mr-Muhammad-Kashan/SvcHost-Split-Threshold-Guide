# ⚙️ Interactive Guide & Calculator for `SvcHostSplitThresholdInKB`

---

## ➤ 🚀 [Live Demo](https://mr-muhammad-kashan.github.io/SvcHost-Split-Threshold-Guide/)

Click the link above to access the interactive guide and calculator.

An interactive, single-page web application designed to be the ultimate guide for understanding and configuring the `SvcHostSplitThresholdInKB` value in the Windows Registry.  
This tool demystifies the process of enhancing system stability by isolating Windows services.

---

## 🧭 Table of Contents

- ❔ [The Problem: Service Grouping & Instability](#-the-problem-service-grouping--instability)
- ✅ [The Solution: Service Isolation](#-the-solution-service-isolation)
- ✨ [Key Features](#-key-features)
- 🎯 [Who Is This For?](#-who-is-this-for)
- 🚀 [How to Use](#-how-to-use)
- 🛠️ [Technical Details](#-technical-details)
- ⚠️ [Disclaimer](#-disclaimer)
- 🤝 [Contributing](#-contributing)

---

## ❔ The Problem: Service Grouping & Instability

In Windows, the `svchost.exe` (Service Host) process is used to group multiple services into a single process.  
While this was designed to save memory on older systems, on modern PCs it can lead to stability issues.  

If one service in a group crashes, it can terminate the entire `svchost.exe` process, taking down all other unrelated services hosted within it. This can cause system-wide errors and instability.

---

## ✅ The Solution: Service Isolation

This tool provides an interactive guide and calculator for the `SvcHostSplitThresholdInKB` registry value.  
By setting this value to a number higher than your total system RAM, you force Windows to run each eligible service in its own separate, isolated `svchost.exe` process.

### 🧠 Benefits

- **Enhanced Stability**: A crash in one service no longer affects others.
- **Better Transparency**: Easily see individual resource usage in Task Manager.
- **Easier Troubleshooting**: Quickly identify and manage problematic services.

---

## ✨ Key Features

- 🔢 **Interactive Value Calculator**: Instantly calculate the registry value based on your system RAM (GB).
- 🧮 **Dual Value Display**: View both **Decimal** and **Hexadecimal** outputs.
- 📋 **One-Click Copy**: Copy generated values to clipboard instantly.
- 📚 **In-Depth Knowledge Base**: Tabbed interface covering:
  - Core concepts and benefits
  - Pros and cons
  - Who should apply this tweak
  - A military-grade, step-by-step procedure
- 📊 **Reference Tables**: Look-up values for common RAM sizes.
- 📱 **Responsive Design**: Clean UI works on desktop, tablet, and mobile.
- 💾 **Self-Contained**: A single HTML file, no dependencies or backend.

---

## 🎯 Who Is This For?

This tool is ideal for:

- 💻 Power Users & PC Enthusiasts
- 🎮 Gamers seeking max stability
- 🛡️ System Administrators & IT Pros
- 👨‍💻 Developers needing isolated environments
- 🧪 Troubleshooters investigating high `svchost.exe` usage

---

## 🚀 How to Use

### 🔗 Online

Just visit the [Live Application](https://mr-muhammad-kashan.github.io/SvcHost-Split-Threshold-Guide/).

### 💻 Locally

1. Download the `index.html` file from this repository
2. Open it in any modern web browser (Chrome, Firefox, Edge, etc.)

---

## 🛠️ Technical Details

- **Frontend**: HTML5
- **Styling**: Tailwind CSS (via CDN)
- **Logic**: Vanilla JavaScript
- **Architecture**: A single, self-contained `index.html` file (no server required)

---

## ⚠️ Disclaimer

Editing the Windows Registry can be risky.  
While this guide outlines a well-documented and safe optimization, always proceed with caution.

> **Backup your system** or create a **System Restore Point** before making registry changes.  
> The author and contributors are not responsible for any damage or data loss.

**Use this guide at your own risk.**

---

## 🤝 Contributing

We welcome contributions!  
Feel free to fork the project and submit pull requests.
