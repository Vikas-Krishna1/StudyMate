# StudyMate 📚

> A multi-feature iOS productivity app combining budgeting, task planning, and AI-powered study tools in one unified mobile experience.

![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## Overview

StudyMate is an iOS productivity app built for students, combining the tools you actually need — budget tracking, task planning, and AI-assisted studying — all in one place. Built with SwiftUI and CoreData for a fully native experience, with OpenAI GPT-4 integration for intelligent study assistance.

Used by dozens of peers at Stony Brook University.

---

## Features

### 🤖 AI Study Chat
- Powered by **OpenAI GPT-4 API**
- Ask questions about your coursework and get intelligent, context-aware answers
- Study smarter with an AI tutor available anytime

### ✅ Task Planner
- Create, organize, and track academic tasks and deadlines
- Persistent local storage via **CoreData** — your data stays on your device
- Never miss an assignment again

### 💰 Budget Tracker
- Track your spending as a student
- Set budgets and monitor categories
- Simple, intuitive interface built for college students

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| UI Framework | SwiftUI |
| Local Persistence | CoreData |
| AI Integration | OpenAI GPT-4 API |
| Platform | iOS 16+ |
| Language | Swift |

---

## Requirements

- iOS 16.0+
- Xcode 14+
- OpenAI API key

---

## Installation

```bash
# Clone the repository
git clone https://github.com/vikaskrishna/studymate.git
cd studymate

# Open in Xcode
open StudyMate.xcodeproj
```

### Configuration

1. Open `Config.swift`
2. Add your OpenAI API key:
```swift
let openAIKey = "your_openai_api_key"
```
3. Build and run on simulator or device

---

## Architecture

StudyMate follows the **MVVM (Model-View-ViewModel)** architecture pattern:

```
StudyMate/
├── Models/
│   ├── Task.swift
│   ├── Budget.swift
│   └── CoreData models
├── Views/
│   ├── TaskPlannerView.swift
│   ├── BudgetTrackerView.swift
│   └── StudyChatView.swift
├── ViewModels/
│   ├── TaskViewModel.swift
│   ├── BudgetViewModel.swift
│   └── ChatViewModel.swift
└── Services/
    └── OpenAIService.swift
```

---

## Author

**Vikas Krishna** — [@vikaskrishna](https://github.com/vikaskrishna)

*Developed independently, May–November 2025*
