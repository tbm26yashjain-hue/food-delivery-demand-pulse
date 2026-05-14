# Food Delivery Demand Pulse

Operational analytics case study analyzing surge pricing inefficiencies in a regional food delivery platform.

The project investigates whether surge incentives are actually improving delivery speed — or reacting too late after rider queues have already formed.

---

## Problem Statement

The food delivery platform was:
- overpaying surge incentives
- applying surge during non-peak periods
- and still experiencing slower deliveries

Analysis across 50,000 orders showed that:
- surge orders arrived 3.7 minutes slower than non-surge orders
- 12.7% of surge activations happened outside peak demand windows
- weekend surge behavior differed significantly from weekdays

The objective was to identify:
- operational inefficiencies
- demand timing patterns
- and opportunities for proactive rider positioning.

---

## Key Findings

### Surge Misfires
12.7% of surge orders occurred outside true peak hours.

### Slower Delivery Despite Surge
Surge orders averaged:
- 43.2 minutes delivery time
vs
- 39.5 minutes for non-surge orders

### Weekend Demand Gap
Weekend surge rate:
- 32.2%

Weekday surge rate:
- 20.5%

No separate weekend policy existed.

### Demand Concentration
Nearly half of all daily orders occurred during:
- lunch peak
- dinner peak

The strongest queue buildup started at 6 PM before surge activation fully ramped.

---

## Recommendations

### Tighten Surge Windows
Restrict surge activation to:
- 12 PM – 2 PM
- 7 PM – 10 PM

Expected:
- lower rider incentive waste
- no delivery impact

### Weekend Pre-Position Bonus
Test rider pre-positioning before demand spikes.

Expected:
- 2–4 minute delivery improvement

### Kolkata Pilot
Pilot proactive rider positioning in Kolkata due to highest demand concentration.

Expected:
- improved rider availability
- lower reactive surge dependency

---

## Tech Stack

| Layer | Technology |
|---|---|
| Analysis | Python |
| Data Processing | Pandas |
| Statistical Testing | scipy.stats |
| Visualization | Matplotlib |
| Forecasting | Rolling Mean |
| Notebook | Jupyter |
| Presentation | PptxGenJS |

---

## Repository Structure

```text
food-delivery-demand-pulse/
│
├── case3_food_delivery.ipynb
├── delhi_7day_forecast_output.csv
├── Execuitve Summary.docx
├── food_delivery_5slide_evaluator.pptx
├── README.md
└── DECISIONS.md
