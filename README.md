# 📱 Merchant Device Operations Dashboard

An interactive operations intelligence dashboard tracking merchant activity, device deployments, churn, winback, and broadcast performance across regions and managers — built as a portfolio project.

🔗 **[Live Dashboard](https://ananyajain2606.github.io/Device-Operations-Dashboard/)**

---

## Overview

This dashboard provides a full-year (Apr '25 – Mar '26) view of merchant operations across zones, states, cities, and sales managers. It covers key operational metrics — active merchants, device bind counts, churn, winback, deployment efficiency, and broadcast success rates.

| | |
|---|---|
| **Coverage** | 22 zones · 15 states · 15 cities · 5 NSMs · 20 RMs |
| **Time grain** | Monthly (Apr '25 – Mar '26) + LMTD / MTD |
| **Tech** | HTML/CSS/JS + Chart.js · zero build step · works offline |

---

## Features

**3 dashboard tabs:**
- **Summary** — KPI cards, monthly trend charts (active/churn/winback), device deployments, broadcast success, deployment activation breakdown
- **Region Wise Analysis** — Winback by state, activation efficiency by zone, broadcast success by zone/city, upgrade rate, scorecards
- **Manager Wise Analysis** — NSM cards, active merchant trends, churn vs winback %, broadcast performance, RM leaderboard with search & sort

**Filter bar** — slice by Zone, State, City, NSM, or RM with instant KPI updates

**Sortable tables** — click any column header to sort zone / city / RM scorecards

---

## KPIs Tracked

| Metric | Description |
|---|---|
| Active Merchants | Merchants transacting in the period |
| Device Bind Count | Total devices bound to merchants |
| MTD Churn | Merchants who became inactive MTD |
| MTD Winback | Previously inactive merchants reactivated |
| Devices Deployed | New device installations MTD |
| Broadcast Success % | % of broadcast messages delivered successfully |
| 50%+ Fail Merchants | % of merchants with >50% broadcast failure |
| Activation Efficiency | % of deployed devices that became txn active |

---

## Tech Stack

| | |
|---|---|
| **Frontend** | HTML5, CSS3, Vanilla JS |
| **Charts** | Chart.js 4.4.1 (CDN) |
| **Hosting** | GitHub Pages |
| **Dependencies** | None (except Chart.js via CDN) |

---

## Notes

- All manager names are anonymised — replaced with generic names for portfolio use
- Metrics reflect patterns from a real operations pipeline; absolute values have been altered
- Broadcasting data partially simulated for illustration purposes

---

## How to Run

Just open `index.html` in any browser — no server or build step needed.

```bash
git clone https://github.com/YOUR-USERNAME/merchant-ops-dashboard
cd merchant-ops-dashboard
open index.html
```
