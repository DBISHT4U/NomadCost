# Contributing to NomadCost

Thanks for your interest in contributing! Here's how you can help.

## Ways to Contribute

### 🌍 Add a New Country (Easiest!)

This is the most impactful contribution. Find the `COUNTRIES` array in `index.html` and add an entry:

```javascript
{
  name: "Country Name",       // English name
  flag: "🏳️",                 // Flag emoji
  code: "CUR",               // ISO 4217 currency code
  region: "Asia",             // Asia / Europe / Americas / Africa / Oceania / Middle East
  rate: 0,                    // Leave 0 — fetched live from API
  monthly_local: 25000,       // Total monthly cost in LOCAL currency
  rent: 8000,                 // Monthly rent (1BHK/studio) in local currency
  food: 8000,                 // Monthly food budget in local currency
  transport: 3000,            // Monthly transport in local currency
  internet: 500,              // Monthly internet in local currency
  fun: 2000,                  // Entertainment/misc in local currency
  visa: "Visa Free",         // "Visa Free" / "On Arrival" / "Required" (for Indian passport)
  visa_days: 30,              // Days allowed on that visa type
  nomad: 80,                  // Digital nomad score 0-100
  wifi: 40,                   // Average WiFi speed in Mbps
  safety: 7,                  // Safety rating 0-10
  cowork: 7,                  // Coworking space availability 0-10
  street_food: 60,            // 1 street food meal in local currency
  restaurant: 200,            // 1 mid-range restaurant meal in local currency
  cooking: 4000,              // Monthly groceries in local currency
  student_monthly: 18000      // Student budget (shared room, basic food) in local currency
}
```

**Where to find data:**
- Cost of living: [Numbeo](https://www.numbeo.com/cost-of-living/), [Expatistan](https://www.expatistan.com/)
- Visa info: [VisaList](https://visalist.io/) (select Indian passport)
- WiFi speeds: [Speedtest Global Index](https://www.speedtest.net/global-index)
- Safety: [Numbeo Safety Index](https://www.numbeo.com/crime/rankings_by_country.jsp)

### 🐛 Fix a Bug

1. Check [Issues](https://github.com/DBISHT4U/NomadCost/issues) for open bugs
2. Comment that you're working on it
3. Submit a PR

### ✨ Add a Feature

Check the [Roadmap](README.md#roadmap) for planned features, or propose your own in an Issue first.

### 📊 Update Data

Cost of living changes! If you notice outdated numbers:
1. Update the values in the `COUNTRIES` array
2. Add a comment noting the source and date
3. Submit a PR

## Development

```bash
# Clone
git clone https://github.com/DBISHT4U/NomadCost.git
cd NomadCost

# Open in browser — no build needed
open index.html

# Edit index.html — refresh browser to see changes
```

There is no build step. The entire app is one HTML file with embedded CSS and JS.

## Pull Request Process

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/add-japan-cities`)
3. Make your changes
4. Test in browser (mobile + desktop)
5. Commit (`git commit -m "Add city-level data for Japan"`)
6. Push (`git push origin feature/add-japan-cities`)
7. Open a Pull Request

## Code Style

- Keep everything in `index.html` (single file architecture)
- Use `const`/`let`, no `var`
- Template literals for HTML strings
- Descriptive variable names
- Comments for non-obvious logic

## Questions?

Open an [Issue](https://github.com/DBISHT4U/NomadCost/issues) — happy to help!
