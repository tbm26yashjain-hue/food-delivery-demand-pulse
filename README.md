# Food Delivery Demand Pulse

Operational analytics case study analyzing surge pricing inefficiencies and delivery optimization opportunities in a regional food delivery platform.

---

## GitHub Repository

https://github.com/tbm26yashjain-hue/food-delivery-demand-pulse

---

## Problem Statement

The platform was:
- overpaying surge incentives
- activating surge during low-demand windows
- and still experiencing slower deliveries

The objective was to identify:
- demand timing inefficiencies
- operational bottlenecks
- and proactive rider positioning opportunities.

---

## Key Findings

### Surge Misfires
12.7% of surge activations occurred outside peak demand windows.

### Slower Delivery Despite Surge
Surge orders averaged:
- 43.2 minutes

Non-surge orders averaged:
- 39.5 minutes

### Weekend Demand Gap
Weekend surge rate:
- 32.2%

Weekday surge rate:
- 20.5%

### Demand Concentration
Nearly half of all daily orders occurred during:
- lunch peak
- dinner peak

---

## Recommendations

### Tighten Surge Windows
Restrict surge to:
- 12 PM – 2 PM
- 7 PM – 10 PM

### Weekend Pre-Position Bonus
Test proactive rider positioning before demand spikes.

### Kolkata Pilot
Pilot operational optimization in highest demand cluster.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Analysis | Python |
| Data Processing | Pandas |
| Statistics | scipy.stats |
| Forecasting | Rolling Mean |
| Visualization | Matplotlib |
| Notebook | Jupyter |

---

## Repository Structure

```text
food-delivery-demand-pulse/
│
├── food_delivery_analysis.ipynb
├── delhi_7day_forecast.csv
├── evaluator_deck.pdf
├── README.md
└── DECISIONS.md