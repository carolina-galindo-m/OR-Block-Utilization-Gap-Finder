# OR Block Utilization Gap Finder

**Author:** Carolina Galindo Mendoza

**Status:** Work in progress; a concept tool built to explore surgical block efficiency analytics

**Tools:** HTML, CSS, JavaScript

---

## What this is

An interactive dashboard concept that identifies underutilized surgical block time by surgeon, service line, and day of week — and surfaces the estimated revenue impact of each gap.

Inspired by the KPIs that perioperative analytics platforms like LiveData PeriOp Manager track in real OR environments: block utilization rates, turnover times, and case scheduling efficiency. This tool asks a simple question: **which blocks are underperforming, and what is it costing the hospital?**

---

## The problem it solves

Hospitals allocate OR block time to surgeons and service lines in advance. When those blocks go underutilized; some cases run short, cancellations happen, or blocks sit empty, therefore the hospital loses revenue it can never recover. Without a clear visual of where the gaps are and how much they cost, OR leadership is left reacting instead of planning.

This tool makes the gaps visible and quantifiable at a glance.

---

## Features

- Filter by service line, day of week, and utilization threshold
- Color-coded status per block: critical gap (below 75%), monitor (75–84%), on target (85%+)
- Revenue at risk calculated per block based on unused hours and service line rate
- Summary KPIs: average utilization, total revenue at risk, critical gap count, worst-performing day
- Horizontal bar charts by service and day of week
- Sortable block detail table with surgeon-level breakdown

---

## How to run

Just open the HTML file in any browser:

```bash
open or_block_gap_finder.html
```

Or clone the repo and open locally:

```bash
git clone https://github.com/yourgithub/OR-Block-Utilization-Gap-Finder
cd OR-Block-Utilization-Gap-Finder
open or_block_gap_finder.html
```

---

## Current data

The dashboard currently runs on a simulated dataset of 15 surgical blocks across 5 service lines (Orthopedics, General Surgery, Cardiothoracic, Neurosurgery, Gynecology) and 5 days of the week. Data is synthetic and designed to reflect realistic OR utilization patterns.

**Next steps:**
- Connect to real EHR export data (CSV input)
- Add week-over-week trend view
- Build surgeon scorecard module showing individual performance over time
- Export filtered view as PDF report for morning huddle use

---

## Why I built this

Block utilization is one of the most impactful — and most overlooked — levers in surgical operations. A 10% improvement in block utilization across a mid-sized hospital can represent millions of dollars in recovered revenue annually, with no additional staff or resources required.

I built this concept tool to better understand the operational intelligence layer that perioperative analytics platforms provide, and to explore how data visualization can make that intelligence immediately actionable for OR leadership teams.

---

## Skills demonstrated

- Interactive dashboard design (HTML/CSS/JS)
- Healthcare operations domain research
- Data visualization for non-technical stakeholders
- Translating operational KPIs into visual decision tools

---

Carolina Galindo Mendoza
