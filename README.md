# hackathon2
# ⚡ NITRO: The Inter-NIT Audio Grid

**NITRO** is a decentralized musical uplink designed to bridge the creative gap between all 31 NIT campuses. Built with a raw **Neo-Brutalist** aesthetic, the platform serves as a central stage for campus rappers, producers, and students to compete, collaborate, and influence their local college vibes.

## 🚀 Live Links
* **Deployment:** [hackathonnitro.netlify.app](https://hackathonnitro.netlify.app)
* **Status:** Hackathon Build v1.0

---

## 🛠️ Technical Architecture

### 1. Smart Verify Engine (Automation)
We engineered a custom JavaScript Regex parser that extracts identity data from the unique NIT email architecture (e.g., `name.branch.year@college.ac.in`).
* **Auto-Mapping:** Instantly translates domain codes (e.g., `nitj`) into full campus names (e.g., NIT Jalandhar).
* **Branch Detection:** Maps departmental segments (e.g., `bt`) to full specializations like Biotechnology.
* **3D Engagement:** A "rigged" 3D CSS slot machine reel built on-the-fly to "land" on the user's verified campus during signup.

### 2. Design Philosophy
* **Neo-Brutalist UI:** A high-contrast, function-over-form interface built with pure HTML5 and CSS3—rejecting generic templates for a raw engineering aesthetic.
* **Vector Engineering:** Minimalist NIT logos created entirely via **SVG code** rather than static images for infinite scalability and high performance.
* **Serverless State:** Utilizing `localStorage` for session persistence and high-speed demo performance without database latency.

### 3. Key Modules
* **Battle Arena:** A 3D Perspective CSS engine for immersive, game-style college rap battles with dynamic health bars and "Fight" animations.
* **Hype Meter (Events):** A crowd-sourced voting algorithm for upcoming fests (Freshers, Sports Meet, etc.), allowing students to "Fix the DJ" by voting on playlists.
* **Explore Hub:** A Gen Z-focused rebrand of the 31-campus network featuring cool, minimalist modifications of official logos.

---

## 📂 Project Structure
```bash
├── index.html      # Main Hub & Music Player (with Session Security Gate)
├── Home.html      # 3D Slot Machine & Smart Verify Portal
├── explore.html    # SVG-engineered NIT Logos & Network Grid
├── battle.html     # 3D Perspective Battle Arena Engine
├── events.html     # Hype Meter & Playlist Voting Logic
└── README.md       # Project Documentation
