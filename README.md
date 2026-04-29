# ⚔️ BattleForge

> A browser-based turn-based combat game.

**[▶ Play Now]https://jmleynes11.github.io/repo_leynes_barquilla/battleforge.html · **[View Website]https://jmleynes11.github.io/repo_leynes_barquilla/** · **[Meet the Team]https://jmleynes11.github.io/repo_leynes_barquilla/team.html**

---

## About

BattleForge is a 3-level tactical combat game built entirely with vanilla HTML, CSS, and JavaScript — no frameworks, no libraries, no build tools. You play as **Forger**, a warrior who must defeat three increasingly dangerous mages to save the realm.

Every decision matters. Resources (HP and SP) carry between levels, and the final boss adapts to your play style.

---

## Campaign

| Level | Enemy | HP | ATK Range | Special | Heals? |
|-------|-------|----|-----------|---------|--------|
| 1 | Shadow Apprentice | 80 | 10–18 | 20–30 | Never |
| 2 | Void Sorcerer | 120 | 14–26 | 30–46 | 18% chance |
| Boss | Monster Mage | 180 | 20–34 | 42–60 | 28% · Enrages at 25% HP |

Defeating a level awards permanent stat bonuses that carry into the next fight.

---

## Controls

| Action | How |
|--------|-----|
| **Attack** | Click ⚔️ — deals 15–25 damage, no SP cost |
| **Defend** | Click 🛡️ — halves incoming damage, +5 HP +5 SP |
| **Special** | Click ✨ — deals 30–45 damage, costs 10 SP |
| **Heal** | Click 💚 — restores 30–45 HP, costs 15 SP |
| Next Level | Click **NEXT LEVEL** after winning |
| Restart | Click **PLAY AGAIN** on the game over screen |

---

## Features

- **Weighted AI system** — enemy decisions adapt to health totals, SP availability, and aggression mode
- **Progressive campaign** — HP/SP bonuses from earlier victories affect later fights
- **Boss enrage mechanic** — Monster Mage enters berserk mode below 25% HP
- **SVG character art** — all three enemies and Forger are hand-coded inline SVG
- **Zero dependencies** — no npm, no bundler, no frameworks; just three HTML files

---

## File Structure

```
battleforge/
├── index.html          # Landing page (game info, how to play, controls)
├── battleforge.html    # The game itself
├── team.html           # Team page with roles and GitHub links
└── README.md
```

---

## Running Locally

No setup required. Clone the repo and open any HTML file directly in a browser:

```bash
git clone https://github.com/jmleynes11/repo_leynes_barquilla.git
cd battleforge
open index.html
```

Or use a local server if you prefer:

```bash
npx serve .
```

---

## Deploying to GitHub Pages

1. Push all files to the `main` branch
2. Go to **Settings → Pages**
3. Set source to `main` branch, root (`/`) folder
4. Your site will be live at (https://github.com/jmleynes11/repo_leynes_barquilla.git)

---

## Team

| Name | Role | GitHub |
|------|------|--------|
| John Matthew M. Leynes | Game Developer · Lead | [jmleynes11](https://github.com/jmleynes11) |
| Nash Michael T. Barquilla | UI Designer · Front-End | [nashmichael77](https://github.com/nashmichael77) |

---

## Tech Stack

- **HTML5** — semantic structure, no template engines
- **CSS3** — custom properties, grid, keyframe animations, no preprocessor
- **Vanilla JavaScript (ES6)** — weighted AI, game state machine, DOM manipulation
- **Inline SVG** — all character art coded by hand
- **Google Fonts** — Cinzel Decorative, Crimson Pro, Press Start 2P
- **GitHub Pages** — static hosting, zero config

---

*© 2026 BattleForge · BSIT Game Dev Sprint*
