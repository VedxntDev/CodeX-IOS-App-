# 🌌 CodeX Nebula

CodeX Nebula is a next-generation, gamified programming learning platform and competitive multiplayer coding arena built natively for iOS. Designed with a sleek cyberpunk aesthetic, the app makes mastering algorithms and programming concepts engaging, social, and intelligent.

---

## 🚀 Key Features

### 🎮 Gamified Learning Journey
* **Multi-Language Training:** Select from various programming languages (Swift, Python, JavaScript, and more) to begin your coding training.
* **Chapters & Level Progression:** Learn systematically with modular chapters and structured programming problems.
* **Progress Gamification:** Earn Experience Points (XP), maintain daily streaks, climb levels, and unlock badges for your achievements.

### ⚔️ Real-Time Coding Battles
* **Multiplayer Arenas:** Challenge friends or find opponents in matchmaking lobbies to face off in real-time coding duels.
* **Live Social Infrastructure:** Real-time presence detection, interactive lobby chat, and a robust friend invitation system.
* **Competitive Editor:** Feature-rich mobile code editor with real-time countdown timers and problem statements.

### 🤖 Gemini AI Judge & Assistant
* **AI Evaluation (AI Judge):** Automated post-battle evaluations evaluating code across correctness, readability, optimization, speed, and styling metrics.
* **Algorithmic Profiling:** Estimates time and space complexity (e.g., $O(N)$ time, $O(1)$ space) and provides custom optimization tips.
* **Interactive AI Coach (Neo):** An embedded assistant ("Neo") providing contextual coding hints, debugging assistance, and code comparison.

---

## 🛠️ Technical Stack & Architecture

CodeX Nebula leverages modern iOS architectures and scalable backend services:

* **Frontend:** SwiftUI (custom dark/glassmorphic design system), MVVM Pattern, and Combine for reactive state management.
* **Database & Real-time Sync:** Firebase Auth, Firestore (presence tracking, lobby syncing, friend list), and Apple Sign-In.
* **AI Integration:** Google Gemini API (`gemini-1.5-flash`) for real-time code analysis, feedback parsing, and interactive chatting.
* **Concurrency:** Swift native `async/await` for asynchronous operations.

---

## 📂 Project Structure

```text
CodeXNebula/
├── Frontend/
│   ├── Views/          # SwiftUI views (Authentication, Learning, Battles, AI Judge, Coding)
│   ├── Components/     # Custom reusable UI cards, buttons, and custom controls (GlassCard, etc.)
│   ├── Theme/          # Global Colors, Fonts, Spacing, and Assets
│   └── Utilities/      # Layout and View extensions
└── Backend/
    ├── Models/         # Core data entities (User, Battle, Problem, Achievement)
    ├── Services/       # API wrappers & business rules (GeminiService, AIJudgeService, FirebaseService)
    └── ViewModels/     # State holders and view binders
```
