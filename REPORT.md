# KAIB Website Remake — Report

## Status: REMAKE COMPLETE

---

## What Was Built

A full static website remake of [kaib-invest.com](https://kaib-invest.com/) — `index.html` + `style.css` — deployed to this repository.

### Design Reference
Content style modelled on [kbs-partners.com](https://kbs-partners.com/): bold typographic hero, dark track-record section, numbered service cards, case-study rows, and a "how we work" grid.

### Source Site
Structure and copy sourced from [kaib-invest.com](https://kaib-invest.com/): KAIB brand, Labuan licensing details, four service lines, platform (PaaS) features, and regulatory disclosures.

---

## Sections Delivered

| # | Section | Notes |
|---|---------|-------|
| 1 | Navigation | Fixed, scroll-aware; mobile burger menu |
| 2 | Hero | Full-viewport, large typographic headline "Beyond the Limits." |
| 3 | Track Record | Dark section, 6-stat grid (assets, clients, mandates, returns, jurisdictions, uptime) |
| 4 | About KAIB | 2-col layout: numbered operator principles + mission/vision/regulatory boxes |
| 5 | Services | 4-card grid: Private Investment Mgmt, Liquidity/Brokerage, Financing, Venture Capital |
| 6 | Selected Work | 3 case studies in KBS-style row layout |
| 7 | Platform | 6-feature grid: real-time processing, blockchain, risk/compliance, cloud, e-KYC, UI |
| 8 | How We Work | Dark 4-step grid |
| 9 | Market Insight | 3 editorial cards with disclaimer |
| 10 | Focus / CTA | Sector · market · counterparty lists + contact CTA box |
| 11 | Contact | Dark section: address info + enquiry form |
| 12 | Footer | Logo, nav, legal, risk warning, links |

---

## Technical Details

- **Stack:** Vanilla HTML5 + CSS3 (no frameworks/dependencies except Google Fonts Inter)
- **Layout:** CSS Grid throughout; fully responsive (mobile, tablet, desktop)
- **Interactions:** Scroll-reveal (IntersectionObserver), smooth scroll, sticky nav, mobile menu, contact form UX
- **Fonts:** Inter (Google Fonts)
- **Colour palette:** Warm off-white `#f4efe6` bg, near-black `#1a1917` text, blue `#1a56f0` accent, `#111110` dark sections — closely matching KBS Partners' tone

---

## Files

```
opshk-/
├── index.html   — full single-page site
├── style.css    — all styles
└── REPORT.md   — this file
```

---

*Remake completed: 2026-11-16*
