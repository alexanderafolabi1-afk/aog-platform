# aog-platform
# AOG Logistics Arbitrage Platform

Proprietary aviation logistics intelligence tool for identifying and monetising Aircraft On Ground (AOG) events.

## What it does

Monitors two active commercial aviation routes using the **Grounding Risk Index (GRI)**:

```
GRI = (hours_stationary / turnaround_window) × (1 + congestion_multiplier) × 100
```

When GRI exceeds **80**, the dashboard triggers an immediate alert — audio, visual lockdown, and a live financial loss ticker — then generates a ready-to-send institutional outreach email.

## Routes monitored

|Route                             |Aircraft       |Hourly Cost|
|----------------------------------|---------------|-----------|
|London Stansted → Munich (STN–MUC)|Boeing 737-800F|$25,000/hr |
|Miami → Bogotá (MIA–BOG)          |Airbus A330-200|$85,000/hr |

## Revenue model

- **Logistics Spread**: 20–35% arbitrage margin on emergency transit quotes
- **Retainer**: Monthly priority routing agreement (sub-4hr response guarantee)
- **Sourcing Commission**: 5–10% on third-party parts acquisition

## How to use

1. Open `index.html` in any browser — no server required
1. Monitor GRI scores across both routes
1. When GRI > 80 — red alert fires automatically
1. Click **Initiate AOG Solution** to generate the outreach email
1. Edit your firm name and contact details, then send

## Deployment

Deployed via GitHub Pages at `https://[username].github.io/aog-platform/`

## Legal

All outreach emails include an NCNDA (Non-Circumvention, Non-Disclosure & Fee Protection Agreement) clause. Obtain legal review before use.

-----

*AOG Arbitrage Platform · Aviation Logistics Intelligence · Standalone Edition*