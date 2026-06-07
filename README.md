# The Invisible Checkout
### ECON1626 Assessment 3 — AI Future Forecast · RMIT University 2026

**Live site:** https://Sachinfaa05.github.io/econ1626-ai-future-forecast/forecast.html

---

## What This Project Argues

By 2030, AI will not simply automate Australian retail. It will create a new form of competitive advantage called the **prediction rent** — the surplus value captured by whoever builds the most accurate forecasting infrastructure in a sector where margins are thin, demand is uncertain, and data is the new capital.

The central forecast is conditional: AI could create a more productive and responsive retail economy, but without deliberate policy it will almost certainly deepen the market power of the retailers and platforms that already hold the most data.

---

## How to Navigate the Essay

The essay is structured as a scrolling interactive webpage. Sections in order:

| Section | What it covers |
|---|---|
| **Landing / Thesis** | The prediction rent argument and the Hayek Inversion |
| **Retail Starting Point** | ABS and Deloitte data establishing market context |
| **Three Channels** | Scrollytelling section — sticky chart updates as you scroll through Operational, Personalisation, and Labour mechanisms |
| **Scenario Simulator** | Live sliders — adjust ACCC enforcement, skills investment, and data portability to see how policy shifts the 2030 productivity outlook |
| **Policy Playbook** | Three targeted interventions with tradeoffs and an implementation timeline |
| **Methods & Data** | Sources, AI tooling disclosure, and limitations |
| **References** | Full RMIT Harvard reference list |

---

## Repository Structure

```
econ1626-ai-future-forecast/
├── forecast.html       ← Main interactive essay (open this)
├── README.md           ← This file
└── .nojekyll           ← Tells GitHub Pages not to run Jekyll
```

---

## Key Interactive Features

- **Scrollytelling channels** — sticky right-panel chart switches automatically between three visualisations as you scroll through the economic mechanism sections
- **Scenario simulator** — three policy sliders update a live Chart.js productivity index in real time, naming which scenario the chosen policies produce
- **Animated stat counters** — figures count up when scrolled into view
- **Typewriter hero subtitle** — builds on load
- **Scroll progress bar** — gold/blue gradient at top of page

---

## Data Sources

All statistics are drawn from named primary sources: ABS Retail Trade (2025, 2026a), Jobs and Skills Australia (2025, 2026), ACCC Supermarkets Inquiry Final Report (2025a), ACCC Digital Platform Services Inquiry (2025b), RBA Technology and AI Bulletin (November 2025), McKinsey & Company (2023), Deloitte Access Economics (2026), and Productivity Commission Inquiry Report No. 111 (2025).

**AI Tooling Disclosure:** Claude (Anthropic) was used to assist in synthesising literature, stress-testing scenario logic and refining narrative structure. All data points were independently verified against primary sources. The prediction rent concept, the Hayek Inversion framing, and all policy arguments are the author's own.

---

## Economic Theory Base

- Autor, DH 2015 — task-based model of automation and labour demand
- Acemoglu & Restrepo 2018 — displacement-productivity-new tasks framework
- Hayek, FA 1945 — dispersed knowledge and the price system (inverted)
- McKinsey Global Institute 2023 — generative AI productivity estimates
- Productivity Commission 2025 — outcomes-based regulatory approach
