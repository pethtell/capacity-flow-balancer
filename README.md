# 📦 Returns FC — Capacity Flow Balancer

An intraday capacity calculator and flow balancer for Clean Decant and Spec 05 Grading operations.

## 🔗 Live Tool
👉 **[Open the Flow Balancer](https://YOUR-USERNAME.github.io/capacity-flow-balancer/)**

## 📋 What It Does
- Calculates hourly output for **Clean Decant Lines 1 & 2** based on headcount and rate
- Calculates hourly capacity for **Spec 05 Graders**
- Shows real-time **flow balance** between the two areas (balanced within +/- 10 units/hr)
- Tracks **cage inventory** across Line 1 RIV and Line 4/5 Inject Drop Zones
- Calculates **productive hours remaining** in the shift (accounts for breaks automatically)
- Recommends **headcount adjustments** to hit end-of-shift targets
- Shows a **10-hour projection table** with break flags and cage depletion tracking

## ✏️ Input Cells (Yellow fields)
| Input | Description |
|---|---|
| Line 1 & 2 HC / Rate | Clean Decant headcount and units per hour |
| Spec 05 HC / Rate | Grader headcount and units per hour |
| RIV Drop Zone Cages | Current cage count at Line 1 RIV |
| Inject Drop Zone Cages | Current cage count at Line 4/5 Inject |
| Target Cages (EOS) | How many cages to leave at end of shift |
| Current Time | Auto-set to Central Time on load |

## ⏰ Shift Details
- **Shift:** 7:30 AM – 6:00 PM
- **Break 1:** 11:00 – 11:30 AM
- **Break 2:** 3:00 – 3:30 PM
- **Total Productive Hours:** 9.5 hrs

## 📌 Notes
- Open in any browser — no login or install required
- All calculations update in real-time as you type
- Current time auto-syncs to Central Time (CST/CDT)
