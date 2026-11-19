# 🌍 NomadCost

**Blazing-fast Currency & Cost of Living Explorer for Indians**

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue.svg)](https://DBISHT4U.github.io/NomadCost) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![HTML](https://img.shields.io/badge/HTML-5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![Chart.js](https://img.shields.io/badge/Chart.js-4.x-ff6384.svg)](https://www.chartjs.org/)

*Compare currencies · Check visa status · Calculate survival budget · Find cheapest countries · Explore food prices*

[Live Demo](#live-demo) · [Features](#features) · [Screenshots](#screenshots) · [Setup](#setup) · [Contributing](#contributing)

---

## Why NomadCost?

If you're an **Indian traveler, student, digital nomad, or just curious** about how far your Rupees go abroad, you know the pain:

- 💱 **Exchange rates** scattered across different sites with no real context
- 💸 **Cost of living** data that never shows how it compares to India
- 🛂 **Visa info** buried across 50 different government websites
- 🍽️ **Food prices** — no idea if street food in Bangkok is cheaper than Delhi
- 🧑‍💻 **Digital nomad info** — WiFi speed, safety, coworking — nowhere in one place
- 🎓 **Student budgets** — nobody tells you the REAL monthly cost for students

**NomadCost** handles all of this — one HTML file, no backend, no dependencies. Open, explore, done.

## Features

| Module | What It Does |
|--------|-------------|
| 💱 **Currency Converter** | Live exchange rates for 35+ currencies vs INR. Real-time API + offline fallback. |
| 📊 **Cost Dashboard** | Monthly cost comparison for 35+ countries — rent, food, transport, internet, fun. |
| 🛂 **Visa Info** | Visa Free / On Arrival / Required status for Indian passport. Duration included. |
| 🧑‍💻 **Nomad Score** | WiFi speed, safety rating, coworking availability. Score out of 100 for each country. |
| 🎓 **Student Mode** | Separate budget for students — shared housing, basic food, public transport. |
| 🍽️ **Food Compare** | Street food vs restaurant vs cooking costs. Any country vs India side by side. |
| 🏕️ **Survival Guide** | 1 month complete budget breakdown — 12 cheapest countries with INR costs. |
| 📈 **Visual Charts** | Bar charts, doughnut charts, radar charts — all interactive with Chart.js. |
| 🔍 **Deep Dive** | Click any country for full breakdown — % cheaper/expensive than India + tips. |

## Live Demo

> 🔗 **[https://DBISHT4U.github.io/NomadCost](https://DBISHT4U.github.io/NomadCost)**

No installation needed. Works on mobile, tablet, desktop. Dark theme by default.

## Screenshots

```
┌─────────────────────────────────────────────────────┐
│  🌍 NomadCost                    Convert  Dashboard │
├─────────────────────────────────────────────────────┤
│                                                     │
│  Duniya Ki Har Currency & Cost Ek Jagah Dekho       │
│                                                     │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐          │
│  │ 10,000   │  │ INR  ▼   │  │ THB  ▼   │          │
│  └──────────┘  └──────────┘  └──────────┘          │
│            4,200.00 THB                             │
│                                                     │
│  ┌────────┐ ┌────────┐ ┌────────┐ ┌────────┐      │
│  │Cheapest│ │Expensive│ │Visa Free│ │Top Nomad│    │
│  │🇬🇪 Geo │ │🇨🇭 Swiss│ │15 Count│ │🇹🇭 Thai │    │
│  │₹18,000 │ │₹4,20,000│ │        │ │88/100  │    │
│  └────────┘ └────────┘ └────────┘ └────────┘      │
│                                                     │
│  Country  Currency  1INR=  Cost    Visa    Nomad   │
│  ────────────────────────────────────────────────  │
│  🇹🇭 Thai  THB      0.42   Cheap   Free    88/100  │
│  🇻🇳 Viet  VND      310    Cheap   OnArr   85/100  │
│  🇬🇪 Geor  GEL      0.03   Cheap   Free    82/100  │
│  🇲🇽 Mexi  MXN      0.21   Cheap   Free    84/100  │
│  ...                                               │
└─────────────────────────────────────────────────────┘
```

## Setup

### Just Open It (Recommended)

```bash
# Clone the repo
git clone https://github.com/DBISHT4U/NomadCost.git
cd NomadCost

# Open in browser — that's it
open index.html
```

### GitHub Pages (Free Hosting)

```bash
# 1. Push to GitHub
git init
git add .
git commit -m "Initial release"
git branch -M main
git remote add origin https://github.com/DBISHT4U/NomadCost.git
git push -u origin main

# 2. Go to: Settings → Pages → Source: main → Save
# 3. Live at: https://DBISHT4U.github.io/NomadCost/
```

### Any Static Host

Upload `index.html` to Netlify, Vercel, Cloudflare Pages, or any web server. It's a single file — no build step, no bundler, no npm.

## Usage

### 💱 Currency Converter

Convert between 35+ currencies with live exchange rates. API updates automatically on page load.

```
INR → THB    1 INR = 0.42 THB
INR → VND    1 INR = 310 VND
INR → USD    1 INR = 0.012 USD
INR → GEL    1 INR = 0.033 GEL
```

### 📊 Country Explorer

Sort, filter, and search across all countries:

- **Filter by region** — Asia, Europe, Americas, Africa, Oceania, Middle East
- **Sort by** — Cost (low/high), Exchange rate, Nomad score, Name
- **Tabs** — All / Cheapest / Expensive / Student Budget / Digital Nomad
- **Search** — Type any country name to filter instantly

### 🔍 Deep Dive (Click Any Country)

```
🇹🇭 Thailand — Deep Dive
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
India se ₹6,000 sasta (24% cheaper)
1 INR = 0.42 THB

Monthly Total     ₹19,000
Student Budget    ₹14,000
Rent              ₹6,500
Food              ₹6,500
Transport         ₹2,400
Internet          ₹500
Entertainment     ₹1,600

🍽 Food Prices (INR)
Street Food       ₹48/meal
Restaurant        ₹160/meal
Monthly Groceries ₹3,200

Visa: ✅ Free (30 days)
WiFi: 45 Mbps — Remote work friendly
Safety: 7/10 — Generally safe
```

### 🎓 Student Budget Mode

Sorted by cheapest student-friendly cost:

| Country | Student Monthly (INR) | Visa |
|---------|----------------------|------|
| 🇻🇳 Vietnam | ₹10,500 | On Arrival |
| 🇰🇭 Cambodia | ₹10,800 | On Arrival |
| 🇬🇪 Georgia | ₹13,000 | Visa Free (365 days!) |
| 🇳🇵 Nepal | ₹14,000 | On Arrival |
| 🇪🇬 Egypt | ₹14,500 | On Arrival |

### 🍽️ Food Price Compare

Select any country and see side-by-side comparison with India:

```
Street Food (1 meal)
🇹🇭 Thailand    ₹48    ✅ Sasta (-₹2)
🇮🇳 India       ₹50

Restaurant (1 meal)
🇹🇭 Thailand    ₹160   ✅ Sasta (-₹140)
🇮🇳 India       ₹300
```

## Data Coverage

| Data Point | Countries | Source | Update |
|-----------|-----------|--------|--------|
| **Exchange Rates** | 35+ | open.er-api.com (live) | Every page load |
| **Cost of Living** | 35+ | Numbeo + local research | Offline dataset |
| **Visa Info** | 35+ | Indian passport requirements | Manual updates |
| **Nomad Scores** | 35+ | NomadList methodology | Offline dataset |
| **Food Prices** | 35+ | Local averages | Offline dataset |
| **WiFi Speeds** | 35+ | Speedtest/Ookla data | Offline dataset |

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | Vanilla HTML5, CSS3, JavaScript (ES6+) |
| **Charts** | Chart.js 4.x (CDN) |
| **Fonts** | DM Sans + Space Grotesk (Google Fonts) |
| **Exchange API** | open.er-api.com (free, no key) |
| **Cost Data** | Curated offline JSON (embedded) |
| **Design** | Custom dark theme, responsive, mobile-first |

**Zero dependencies. No build step. No framework. Single HTML file.**

## Roadmap

- [x] Live currency converter (35+ currencies)
- [x] Cost of living comparison (35+ countries)
- [x] Visa info for Indian passport
- [x] Digital nomad scores
- [x] Student budget mode
- [x] Food price comparison
- [x] 1 month survival guide
- [x] Interactive charts (Chart.js)
- [x] Country deep dive panel
- [ ] Add 50+ more countries
- [ ] City-level data (not just country)
- [ ] Monthly cost calculator (custom budget)
- [ ] Flight price estimator
- [ ] Weather/best time to visit
- [ ] Currency trend charts (30 day history)
- [ ] Save favorite countries
- [ ] PWA support (offline mode)
- [ ] Multi-language support (Hindi, etc.)
- [ ] Dark/Light theme toggle
- [ ] API backend for real-time cost updates

## Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

The easiest way to contribute is **adding data for a new country** — we have a template in the contributing guide.

## License

MIT — see [LICENSE](LICENSE).

---

**Built with ☕ and curiosity for the Indian travel community**

*If this tool helped you, give it a ⭐ on GitHub!*
