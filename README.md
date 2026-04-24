# US Domestic Flights — Exploratory Data Analysis

## Project Overview
An exploratory data analysis of 271,940 US domestic flights
from April to October 2013, covering 16 airlines and 36 states.
Completed as part of the YMCA/Seneca Bridge to IT Careers
programme (2026).

**Business question:** What patterns exist in flight delays
and cancellations, and what can passengers and airlines learn
from them?

---

## Key Findings

| Question | Finding |
|---|---|
| Average departure delay | 0.2 minutes after outlier removal |
| Most reliable airline | Alaska Airlines |
| Worst day to fly | Thursday - highest average arrival delay |
| Best day to fly | Saturday - lowest average arrival delay |
| Worst departure airport | Chicago Midway International |
| Dep vs Arr delay correlation | Strong positive relationship |

---

## Tools Used

- **Python 3** - programming language
- **pandas** - data loading, cleaning and aggregation
- **NumPy** - numerical calculations and outlier detection
- **Matplotlib** - all data visualisations (7 charts)

---

## How to Run

1. Clone this repository:
2. Install dependencies:
3. Run the analysis:
---

## Data Cleaning Decisions

- Cancelled flights: filled missing DepDel15 values with 0
  Note: a better approach would be to exclude cancelled flights
  entirely from departure delay analysis, as filling with 0
  mislabels cancellations as on-time flights. This is a known
  Limitation of the current analysis and will be corrected
  in the next version.

- Outliers removed using the IQR method on DepDelay and ArrDelay

---

## Author
Odoffin
---


