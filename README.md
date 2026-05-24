# 🌍 WorldUnfold

> *An interactive world exploration platform for children aged 8–15.*

WorldUnfold opens with a single illustrated Earth floating in space. From there, you click into three worlds — **Land**, **Ocean**, and **Sky** — each unfolding into its own rich layer of content: countries and capitals, deep-sea creatures, constellations, satellites, and more.

Every piece of information is wrapped in story. Every click leads somewhere unexpected. WorldUnfold doesn't ask children to study — it invites them to explore.

---

## ✨ Features

### 🌎 Earth Module
- Illustrated flat world map in 2.5D style
- Click any country to open a detail card with its name, capital, a fun fact, and a short story or legend
- V1: 50 countries · V2: all 195

### 🌊 Ocean Module
- Vertical depth cross-section of the ocean — darker and more mysterious as you scroll deeper
- Five depth zones: Sunlight → Twilight → Midnight → Abyssal → Hadal
- Clickable sea creatures, depth landmarks (e.g. Mariana Trench), and shipwrecks
- V1: 25 creatures · 5 landmarks

### 🌌 Sky Module
- Vertical height chart ascending from ground level through the atmosphere into deep space
- Clickable clouds, birds, planes, the ISS, satellites, constellations, and named stars
- Constellation stories from multiple cultures (Greek, Indian Nakshatras, and more)
- Real-world prompt: *"Find this tonight"* with a seasonal indicator
- V1: 15 constellations · 10 named stars · 5 man-made objects

---

## 🗂️ Repo Structure

```
worldunfold/
├── images/                  # Illustrations and SVG assets
├── land_v4.html             # Earth module
├── ocean-v3.html            # Ocean module
├── night_sky_explorer.html  # Sky module
└── README.md
```

> **Note:** All content is loaded from local JSON data — no backend, no database. Pure static frontend.

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 + Flexbox / Grid |
| Interactivity | Vanilla JavaScript |
| Animations | CSS transitions + GSAP (free CDN) |
| Space visuals | CSS / SVG |
| Data | Local JSON files |
| Deployment | GitHub Pages / Vercel |

No npm. No build tools. No framework setup. Open in VS Code, run with Live Server, push to GitHub.

---

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/alanascodein/worldunfold.git
   cd worldunfold
   ```

2. **Open in VS Code**
   ```bash
   code .
   ```

3. **Run with Live Server**
   - Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
   - Right-click any `.html` file → *Open with Live Server*

That's it. No install step, no build step.

---

## 🎨 Design Language

- **Style:** 2.5D flat illustration with subtle shadow and depth
- **Palettes:** Earth (greens, earthy browns) · Ocean (deep navy, teal) · Sky (deep purple, dark blue, gold)
- **Typography:** Nunito or Poppins — two weights only (regular + bold)
- **Animations:** Smooth ease-in-out transitions, 800–1200ms · Respects `prefers-reduced-motion`
- **No stock icons, no stock photography** — all visuals are illustrated or SVG-based

---

## 🗺️ Roadmap

### V1 (Current)
- [x] Landing screen with 2.5D Earth and zoom-in transitions
- [x] Earth module — world map with country detail cards
- [x] Ocean module — depth cross-section with creatures and landmarks
- [x] Sky module — atmosphere and space height chart with constellation stories

### V2 (Planned)
- [ ] All 195 countries
- [ ] Quiz / gamification mode
- [ ] Audio narration and bedtime story mode
- [ ] Real-time sky data — seasonal constellation detection by location
- [ ] Three.js 3D starfield
- [ ] Classroom / teacher features
- [ ] User accounts and saved progress

---

## ♿ Accessibility

- All illustrations have descriptive `alt` text
- Text contrast meets WCAG AA minimum
- All interactive elements are keyboard-navigable
- Minimum body font size: 16px
- `prefers-reduced-motion` respected throughout

---

## 📄 License

This project is currently unlicensed. All rights reserved by the author.

---

<p align="center">
  <em>"In a world where we rarely look up anymore, this project reminds us that the sky still has stories waiting to be seen."</em><br>
  — WorldUnfold, Project Vision Statement
</p>
