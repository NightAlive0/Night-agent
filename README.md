<div align="center">

# ⟡ NYX

### **NEURAL eXecutive**

*A local-first AI companion for Android.*

<br>

[![Flutter](https://img.shields.io/badge/Flutter-3.x-00E676?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Android](https://img.shields.io/badge/Android-8.0%2B-00E676?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![License](https://img.shields.io/badge/License-Open%20Source-151515?style=for-the-badge)](#-license)

<br>

> **Think it. Tell NYX. Let it handle the rest.**

</div>

---

## ◉ What is NYX?

**NYX** is an Android AI agent built around natural-language interaction and device automation.

Instead of manually navigating through multiple screens, NYX is designed to understand a task, interact with the Android interface, and execute the required actions.

> **Make your phone feel more intelligent without making the interface more complicated.**

---

## ⚡ Core Capabilities

| Capability | Description |
|---|---|
| 🧠 **AI Interaction** | Communicate with an AI assistant using natural language |
| 📱 **Screen Control** | Interact with Android applications through accessibility services |
| ⚙️ **Task Automation** | Execute multi-step actions from a single instruction |
| 🎙️ **Voice** | Voice input and text-to-speech capabilities |
| 🔒 **Local-first Design** | Designed around keeping control of your configuration and data |
| 🛰️ **Background Tasks** | Monitor ongoing agent activity while using other applications |

---

## 🖥️ The NYX Interface

NYX is being redesigned around a darker, minimal interface.

```text
        ┌─────────────────────────┐
        │                         │
        │          NYX            │
        │                         │
        │    NEURAL EXECUTIVE     │
        │                         │
        │       ● READY           │
        │                         │
        └─────────────────────────┘

             BLACK × GREEN
```

**Black backgrounds · subtle surfaces · neon green accents · minimal clutter**

---

## 🚀 Getting Started

### Requirements

- Android **8.0 / API 26 or newer**
- An AI provider/API configuration supported by the project
- Accessibility permission for screen automation

### Clone the Repository

```bash
git clone https://github.com/NightAlive0/Night-agent.git
cd Night-agent
```

### Install Dependencies

```bash
flutter pub get
```

### Build NYX

```bash
flutter build apk
```

The generated APK will be located in:

```text
build/app/outputs/flutter-apk/
```

---

## 🔐 Permissions

NYX uses Android permissions required for its functionality.

The accessibility service allows NYX to interact with the Android interface.

> ⚠️ Accessibility access gives an application significant control over the device. Only enable it for software you trust and understand.

---

## 🧩 Architecture

```text
                    ┌──────────────┐
                    │     NYX      │
                    │   Flutter    │
                    └──────┬───────┘
                           │
              ┌────────────┼────────────┐
              │            │            │
              ▼            ▼            ▼
         AI Service    Task Engine   UI Layer
              │            │
              │            ▼
              │      Android Control
              │            │
              └────────────▼
                    Accessibility
                       Service
```

### Project Structure

```text
lib/
├── screens/
├── services/
├── widgets/
└── ...

android/
└── Native Android components
```

---

## 🛠️ NYX Roadmap

### Identity

- [x] NYX rebrand
- [x] NYX color system
- [ ] Custom NYX icon
- [ ] Custom splash screen
- [ ] Full UI redesign

### Agent

- [ ] Custom NYX personality
- [ ] Improved task planning
- [ ] Better task feedback
- [ ] Expanded automation capabilities

### Interface

- [x] Black + green theme
- [ ] HUD-style elements
- [ ] Better animations
- [ ] Custom agent status indicator
- [ ] More compact mobile UI

### Project

- [ ] NYX documentation website
- [ ] Release builds
- [ ] Public changelog
- [ ] More extensive testing

---

## 📸 Screenshots

> Screenshots will be added as the NYX interface evolves.

---

## 🧪 Development

NYX is currently under active development and customization.

Expect things to change.

If you're experimenting with the project, keep backups of your configuration before making major changes.

---

## 🌌 Philosophy

> **An assistant shouldn't make you adapt to it.  
> It should adapt to you.**

The goal is to make interaction with Android feel less like operating a collection of applications and more like communicating with an intelligent system.

---

## 🤝 Credits

NYX is a customized fork of **PrivateAgent**, originally created by **orailnoor**.

The original project and its contributors deserve credit for the underlying application, architecture, and functionality on which NYX is based.

### Original Project

https://github.com/orailnoor/private-agent

This repository contains modifications made for the NYX project.

---

## 📜 License

Please refer to the original project's license and retain all required copyright and attribution notices.

NYX does not claim authorship of the original PrivateAgent code.

---

<div align="center">

### ⟡ NYX

**NEURAL eXecutive**

`BLACK // GREEN // INTELLIGENCE`

<br>

**Built with Flutter • Powered by AI • Designed for Android**

</div>
