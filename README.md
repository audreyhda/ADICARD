# 🎓 ADICARD

> **A digital student discount card app for University of Naples Federico II students — find restaurants and venues offering reduced prices with your ADiSU card.**

[![Swift](https://img.shields.io/badge/Swift-F54A2A?style=flat&logo=swift&logoColor=white)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white)](https://developer.apple.com/xcode/)

---

## 📌 Problem Statement

Students at the University of Naples Federico II receive an ADiSU card that entitles them to discounted meals at participating restaurants and venues around the city. But finding out which places accept it, what deals are available, and managing the card itself is scattered and inconvenient. ADICARD brings it all into one place — a clean, native iOS app that makes the most of your student card.

---

## 🧩 Project Overview

ADICARD was built as a **first group project** during the 2022/2023 programme at the [Apple Developer Academy](https://www.developeracademy.unina.it/en/) at the University of Naples Federico II, Italy. It was our very first collaborative Swift app: we identified a real, concrete problem shared by every student at the Academy, designed a solution together, and shipped a working iOS prototype using the **Challenge Based Learning (CBL)** methodology.

The app solves a problem we lived every day — making the ADiSU student discount card actually useful and easy to use.

---

## 🧩 Project Context

| | |
|---|---|
| **Programme** | Apple Developer Academy — University of Naples Federico II |
| **Location** | Naples, Italy |
| **Year** | 2022 / 2023 |
| **Type** | First group project |
| **Methodology** | Challenge Based Learning (CBL) |
| **Target users** | Students at the University of Naples Federico II |

---

## 🛠️ Tech Stack

### 🌐 Languages
- Swift 5

### 📦 Frameworks
- SwiftUI — Declarative iOS UI

### 🧪 Testing
- XCTest — Unit tests (`ADICARDTests`)
- XCTest UI — UI tests (`ADICARDUITests`)

### 🔧 Tools
- Xcode — IDE
- Git / GitHub — Version control and group collaboration
- Figma — UI/UX design

---

## ✨ Features

- **Digital student card** — Your ADiSU card always in your pocket, no need to carry the physical version
- **Venue discovery** — Browse restaurants and venues in Naples that accept the ADiSU student discount
- **Discount details** — See exactly what deal each venue offers for card holders
- **Student-focused UX** — Designed by students, for students at the University of Naples Federico II

---

## 📁 Project Structure

```
ADICARD/
├── ADICARD/                    # Main app source (Swift / SwiftUI)
│   ├── ADICARDApp.swift        # App entry point
│   ├── ContentView.swift       # Root view
│   └── ...                     # Models, Views, ViewModels
├── ADICARDTests/               # Unit tests (XCTest)
├── ADICARDUITests/             # UI tests (XCTest)
└── ADICARD.xcodeproj           # Xcode project file
```

---

## ⚙️ Getting Started

### Prerequisites
- Xcode 14+
- iOS 16+ simulator or device

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/audreyhda/ADICARD.git
cd ADICARD

# 2. Open in Xcode
open ADICARD.xcodeproj

# 3. Select a simulator and press Run (⌘R)
```

No external dependencies or API keys required.

---

## 🧪 Running Tests

In Xcode: **Product → Test (⌘U)**

Or from the command line:
```bash
xcodebuild test \
  -scheme ADICARD \
  -destination 'platform=iOS Simulator,name=iPhone 16'
```

---

## 👥 Team

Built as a group project at the **Apple Developer Academy**, Naples — 2022/2023.

- **Audrey** — [@audreyhda](https://github.com/audreyhda)
- [@acapone22](https://github.com/acapone22)
- *Add other team members here*

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

*Apple Developer Academy — University of Naples Federico II · First Group Project · 2022/2023*
