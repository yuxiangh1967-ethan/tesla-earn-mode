# 🚗 Tesla FSD Earn Mode — Interactive Product Prototype

> **Turn your idle Model Y into an autonomous income asset.**  
> A high-fidelity mobile prototype demonstrating Tesla's proposed *FSD Earn Mode* feature — allowing HW4 Model Y owners to opt their personal vehicle into Tesla's managed Robotaxi fleet during idle hours and earn passive income.

---

## 📖 Background

This prototype was built as part of **MGMT 275: Product Management** at UCLA Anderson School of Management (Spring 2026).

The core insight: Tesla's FSD subscription has a **~13% take-rate** on Model 3/Y. The primary barrier is cost — owners don't see $99/month as justified for a supervised driving assistant they still have to monitor. **Earn Mode flips the value proposition**: when the car earns money while parked, the $99/month subscription becomes a net-positive investment rather than a recurring expense.

Rather than a peer-to-peer sublease (which faces insurance and liability blockers), Earn Mode is structured as an **owner opt-in to Tesla's official Robotaxi network** — Tesla remains the licensed operator, insured party, and customer-facing brand. Owners simply set availability windows and collect weekly payouts.

---

## ✨ Features

The prototype is organized into four tabs mirroring a real Tesla mobile app experience:

### 🏠 Dashboard
- **Earn Mode toggle** — activates Robotaxi enrollment with an animated vehicle status transition
- **Live trip overlay** — when a trip is in progress, an animated card shows route, distance, accumulating fare counter, and ETA
- **FSD offset progress bar** — tracks how much of the monthly subscription cost the car has already earned back
- **Quick-stats grid** — trips completed, average passenger rating, total Robotaxi miles, disengagement count

### 📅 Schedule
- **Day-of-week chips** — tap to toggle individual days (Mon–Fri on by default)
- **Time window controls** — tap to cycle start/end times (default: 9 AM–6 PM)
- **Battery reserve floor** — sets minimum charge before trips stop being accepted (default: 20%)
- **Auto-return home** — geo-fenced home zone with automatic vehicle return
- **Live weekly bar chart** — projected earnings recalculate in real time as you adjust days and hours

### 💵 Earnings
- **Month-to-date total** with week-by-week bar chart
- **Available-payout card** — one-tap bank transfer to a linked account
- **Interactive real-world map** (OpenStreetMap + Leaflet.js, dark-themed) — plots today's completed Robotaxi routes as color-coded polylines with clickable pickup/drop-off markers showing route name and fare
- **Trip log** — individual trip history with route, timestamp, passenger rating, and payout

### ⚙️ Settings
- Trip radius cap (default: 25 mi)
- Battery reserve floor configuration
- Per-trip notification toggle
- Auto-cleaning cadence selector
- Bank account management
- **Tesla $2M commercial Robotaxi insurance** status indicator

---

## 🚀 Quick Start

No build step, no server, no dependencies to install.

```bash
# Clone the repo
git clone https://github.com/<your-username>/tesla-earn-mode.git

# Open the prototype directly in your browser
open tesla-earn-mode-prototype.html   # macOS
start tesla-earn-mode-prototype.html  # Windows
```

Or just **double-click** `tesla-earn-mode-prototype.html` in Finder / File Explorer.

> ⚠️ The interactive map (Earnings tab) requires an internet connection to load map tiles from OpenStreetMap/CartoDB. All other tabs work fully offline.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI | Vanilla HTML5 + CSS3 + JavaScript (zero frameworks) |
| Map | [Leaflet.js](https://leafletjs.com/) v1.9.4 |
| Map tiles | [CartoDB Dark Matter](https://carto.com/basemaps/) (OpenStreetMap data) |
| Fonts | System font stack (`-apple-system`, `Helvetica Neue`) |
| Icons | Unicode emoji |
| Hosting | Any static file host (GitHub Pages, Vercel, Netlify) |

---

## 📁 File Structure

```
tesla-earn-mode/
├── tesla-earn-mode-prototype.html   # Full prototype (single self-contained file)
├── README.md                        # This file
└── docs/
    ├── PR-FAQ_Tesla_Earn_Mode_v2.docx   # Full PR-FAQ product document
    ├── PR-FAQ_Tesla_Earn_Mode_v2.md     # Markdown version of PR-FAQ
    └── Tesla Model Y FSD — Product Strategy Report.docx
```

---

## 🌐 Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your prototype will be live at:
   ```
   https://<your-username>.github.io/tesla-earn-mode/tesla-earn-mode-prototype.html
   ```

---

## 🎮 How to Use the Prototype

| Action | What Happens |
|---|---|
| Flip the **Earn Mode toggle** (Dashboard) | Vehicle status switches to "In Duty"; a live trip card animates in after 2 seconds |
| Tap **day chips** (Schedule) | Days toggle on/off; weekly earnings estimate recalculates instantly |
| Tap **time values in blue** (Schedule) | Cycles through time options |
| Click **"Save Schedule"** | Toast confirmation appears |
| Open **Earnings tab** | Interactive LA map loads with 4 real trip routes; click any pin for fare details |
| Click **"Transfer Now"** (Earnings) | Payout confirmation toast |
| Tap **"Suspend Earn Mode"** (Settings) | Toast confirmation appears |

---

## 📊 Product Hypothesis

| Metric | Current | Target (12 mo) |
|---|---|---|
| FSD take-rate on Model Y | ~13% | 30%+ |
| Owner-contributed Robotaxi vehicles | 0 | 50,000+ |
| Median monthly owner earnings | — | $400–$580 |
| FSD offset rate (earnings vs. subscription) | 0% | > 100% for active enrollees |

---

## 🏗️ Product Architecture

```
Owner's Tesla (HW4 Model Y)
        │
        ▼
 Tesla App — Earn Mode
  ┌─────────────┐
  │  Dashboard  │ ← Toggle, live trip overlay, earnings offset bar
  │  Schedule   │ ← Availability windows, battery reserve, home zone
  │  Earnings   │ ← Real-time map, payout, trip history
  │  Settings   │ ← Radius, cleaning, insurance, bank
  └─────────────┘
        │
        ▼
 Tesla Robotaxi Dispatch System
  • Routes trips to enrolled owner vehicles
  • Manages insurance (Tesla $2M commercial policy)
  • Handles payments & weekly ACH payouts via Stripe Treasury
  • Auto-charges at Superchargers between trips
        │
        ▼
 Owner receives 70% of net trip revenue
 (after Supercharger, insurance, cleaning deductions)
```

---

## ⚖️ Key Design Decisions

**Why not peer-to-peer sublease?**  
P2P requires personal auto insurers to cover commercial ride-hail use (they won't), creates unresolved liability frameworks, and needs unsupervised FSD at scale. By keeping Tesla as the licensed operator and insurer, Earn Mode sidesteps all three blockers and can launch in 6–12 months using infrastructure already live in Austin.

**Why 20% battery reserve default?**  
Owners need confidence their car will always have enough charge to return home. 20% provides a comfortable buffer (~50–55 miles on a standard Model Y Long Range) while maximizing dispatch availability.

**Why 25-mile trip radius default?**  
Keeps the vehicle within a predictable return window for the 90-minute "Call My Car Home" guarantee, while still covering the vast majority of urban/suburban trip demand.

---

## 👥 Authors

**Kevin Meng & Ethan He**  
UCLA Anderson School of Management  
MGMT 275: Product Management — Spring 2026

---

## 📄 License

This prototype is submitted as an academic project for UCLA Anderson MGMT 275. Not affiliated with or endorsed by Tesla, Inc.

---

*Built with zero dependencies. Powered by the belief that every parked Tesla should be earning its owner money.*
