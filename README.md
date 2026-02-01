# SkollPath
Traque ta progression, ne laisse aucune chance à ton ombre.


**SköllGhost** is a high-performance biometric tracking application designed to turn weight loss into a mathematical hunt. Inspired by Norse mythology (Sköll, the wolf who pursues the sun) and built with rigorous software engineering principles, the app pits your real-time weight against a relentless theoretical trajectory: **The Ghost Mode**.

---

## 🚀 The Concept: Ghost Mode
Unlike standard fitness apps, **SköllGhost** doesn't just display a passive chart. It generates a "Ghost" trajectory that progresses at a steady pace of **-100g per day**. 

- **Ahead of the Ghost:** You earn credit points (unlocking *Cheat Meal* eligibility).
- **Behind the Ghost:** The shadow overtakes you, signaling a deviation from your target path.

The goal is simple: maintain the lead and stay ahead of the Ghost until the final target of **85 kg**.

## 🛠️ Tech Stack & Architecture
This project serves as a sandbox for implementing industry-leading software standards:

* **Framework:** React Native (Expo) / TypeScript.
* **Architecture:** **DDD (Domain-Driven Design)** & **Clean Architecture**.
    * Strict separation of layers: *Domain*, *Application (Use Cases)*, and *Infrastructure (Adapters)*.
* **Data Management:**
    * **Source of Truth:** Bi-directional synchronization with **Google Sheets API**.
    * **Local Storage:** MMKV for ultra-fast persistent caching.
* **Artificial Intelligence:** Integration of the **Gemini API** as a contextual assistant for trend analysis and personalized motivation.

## 📊 Key Features
- **Dual-Curve Visualization:** Real-time comparison between the "Ghost" trajectory and actual weight.
- **Context Logging:** Annotate weigh-ins to identify biases (sleep quality, hydration, caffeine intake).
- **AI Companion:** Proactive data analysis to explain plateaus and celebrate reached milestones.
- **Gamification:** Reward system based on mathematical consistency and progress.

## 📈 Project Status
The development roadmap is tied to real-world weight milestones:
- [x] **Phase 0:** Domain definition and UI design (Nyx/Dark Mode style).
- [ ] **Phase 0.5:** Google Sheets Bridge & AI Integration (In Progress).
- [ ] **Phase 1:** MVP (Minimum Viable Product) launch upon reaching the 85 kg milestone.

---

## 📥 Installation (WIP)

```bash
# Clone the repository
git clone [https://github.com/your-username/skollghost.git](https://github.com/your-username/skollghost.git)

# Install dependencies
yarn install

# Start the development environment
npx expo start
