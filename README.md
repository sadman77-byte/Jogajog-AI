# Jogajog-AI

# যোগাযোগ (Jogajog) — Offline Interview, Riddle & Communication Simulator

https://endearing-gaufre-d98692.netlify.app/

A RAG-based, standalone, offline-first communication simulator combining professional interview practice, social interaction scenarios, bilingual conversational guidance, character-based feedback, and gamified logical challenges.

**যোগাযোগ (Jogajog)** is a zero-dependency, offline-first, single-file interactive web application designed to help users master high-stakes corporate interviews, logical brainteasers, professional attitude, stand-up humor, and formal/informal social banter.

Built inside a single `index.html` file with persistent `localStorage` state, it requires no backend server, API keys, or internet connection after download.

---

## ✨ Key Features

### 1. Phrase & Attitude Academy
- **Curated Phrase Bank:** Categorized across **Corporate Interviews**, **Professional Attitude & Ownership**, **Formal Flirting**, **Informal Flirting**, and **Wit & Humor**.
- **Bilingual Context:** English expressions paired with Bengali translations and pragmatic usage tips.
- **One-Click Board Injection:** Send any learned phrase directly into the live simulation room to test real-time reactions.

### 2. 100-Character Roster
- **50 Corporate Interview Board Members:** VPs of Product, Google-style Hiring Leads, Cross-Cultural Directors, Principal AI Researchers, and Executive Recruiters.
- **50 Social & Flirt Personas:** Coffee shop readers, gallery curators, conference co-panelists, rooftop musicians, and design partners.
- **Instant Filtering:** Search by character name, role, or simulation mode.

### 3. Google Meet-Style Simulation & Brainteaser Board
- **Visual Expression Engine:** Characters dynamically shift visual states (`Neutral`, `Impressed`, `Blushing / Amused`, `Laughing`, `Skeptical`, `Annoyed`) alongside a live **Impression Meter**.
- **Surprise Interview Riddles:** Built-in logic puzzle engine (3 Bulbs & Switches, Burning Ropes 45-Minute Timer, Round Manhole Covers, 3:15 Clock Angle, 25 Horses Race) with hint support and bonus coin rewards.
- **Gamified Coin & Streak Economy:** Earn or lose coins (`+` / `-`), build response streaks, and track **Riddles Solved**, **Professional Score**, and **Charm/Humor Score** offline via `localStorage`.

---

## 🚀 How to Run

### Option 1: Run Locally (100% Offline)
1. Download or clone this repository:
   ```bash
   git clone [https://github.com/sadman77-byte/jogajog-communication-simulator.git](https://github.com/sadman77-byte/jogajog-communication-simulator.git)
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari). No build tools or server required.

### Option 2: Host on GitHub Pages
1. Go to your repository **Settings** → **Pages**.
2. Under **Build and deployment**, select **Deploy from a branch** (`main` / `root`).
3. Your live interactive simulator will be accessible via your GitHub Pages URL.

---

## 🛠️ Tech Stack
- **Frontend:** Vanilla HTML5, CSS3 (Custom Dark UI, CSS Grid/Flexbox, Keyframe Animations), ES6+ JavaScript
- **Persistence:** Browser `localStorage` (Offline Coin, Score, and Progress Storage)
- **Architecture:** Single-file portable bundle (`index.html`)

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
