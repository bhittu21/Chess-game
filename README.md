# 🌌 Galaxy Chess Tournament Bracket

> **A futuristic, glassmorphism-styled visualization for a 30-player chess tournament.**

![Project Status](https://img.shields.io/badge/Status-Active-22d3ee?style=for-the-badge)
![Design](https://img.shields.io/badge/Design-Galaxy_UI-a855f7?style=for-the-badge)
![Logic](https://img.shields.io/badge/Logic-Automated-fbbf24?style=for-the-badge)

## 📜 Credits & Attribution

**Core Logic & Architecture:** Developed by **[Al-Mahmud-2019331048](https://github.com/Al-Mahmud-2019331048)** (University Lecturer).  
*The underlying algorithm for match scheduling, player seeding, and bracket progression remains 100% faithful to the original source code.*

**UI/UX Modernization:** Refactored with a **Galaxy/Sci-Fi aesthetic** featuring glassmorphism, deep space gradients, and neon typography.

---

## ✨ Key Features

### 🎨 Design (Galaxy Edition)
* **Glassmorphism Cards:** Match slots feature a frosted glass effect with backdrop blurring.
* **Deep Space Theme:** Background utilizes a custom indigo-to-black gradient (`#0f172a`).
* **Neon Accents:** Typography and active states glow with Cyan (`#22d3ee`) and Purple (`#a855f7`).
* **Responsive Typography:** Uses the 'Outfit' geometric font for a modern, clean look.

### 🧠 Logic (Original Flow)
* **30-Player Support:** Handles uneven brackets with specific "Waiting" slots.
* **Automated Progression:** Selecting a winner in the dropdown automatically moves their name to the next round.
* **Wildcard Support:** Specific support for a "Best Loser" selection in Round 2.
* **Dynamic Scheduling:** Automatically calculates match times based on a 3-match simultaneous start with 30-minute intervals.

---

## 🚀 How to Use

1.  **Download:** Save the `index.html` file to your local machine.
2.  **Run:** Open the file in any modern web browser (Chrome, Edge, Firefox, Safari).
3.  **Operate:**
    * Select winners using the dropdown menus inside each match card.
    * Watch as the bracket updates in real-time, moving winners to the next stage.
    * In **Round 2**, use the special Gold Dropdown to select the "Best Loser" entry.

---

## ⚙️ Configuration

To modify the participants, open `index.html` in a text editor and locate the `playerSeedings` array inside the `<script>` tag:

```javascript
const playerSeedings = [
    ["Player A", "Player B"], 
    ["Player C", "Player D"],
    // ...
];
