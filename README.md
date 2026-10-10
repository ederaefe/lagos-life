LIVE = https://lagoslife.app/
# 🇳🇬 Lagos Life: Browser Edition

> A lightweight, web-based life simulation game capturing the hustle, survival, and vibrant culture of Lagos, Nigeria. 

---

## 🌟 About The Project

**Lagos Life** is a multiplayer role-playing simulation where players manage daily life stats while navigating uniquely local experiences—from catching a *danfo* during rush-hour traffic to climbing the corporate ladder or running street-side side hustles. 

This repository contains the source code for building an interactive, browser-based life simulator with plans for real-time multiplayer interactions.

---

## 🚀 Key Features

* **Survival Stats Management:** Keep track of your character's *Hunger, Energy, Fun, Hygiene, Bladder,* and *Social* meters.
* **The Lagos Economy:** Earn Game Naira through various jobs, pay rent, buy food, and manage daily expenses.
* **Local Flavor & Events:** Navigate unpredictable Lagos realities like power outages ("NEPA/PHED"), gridlock traffic, and street markets.
* **Multiplayer Spaces (Coming Soon):** Hang out in shared virtual hubs across Lagos, Abuja, and Port Harcourt.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 / Tailwind CSS, Vanilla JavaScript (or React)
* **Backend (Multiplayer):** Node.js, Express, Socket.io
* **Hosting:** Vercel / Netlify (Frontend), Render / Railway (Backend)

---

## 📂 Project Structure

```text
lagos-life-clone/
│
├── public/              # Static assets (images, icons, sounds)
├── src/
│   ├── components/      # UI components (Stats, Map, Inventory)
│   ├── game/            # Game logic, player state loops, economy engine
│   ├── styles/          # CSS stylesheets
│   └── main.js          # Entry point
│
├── index.html           # Main game entry page
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
