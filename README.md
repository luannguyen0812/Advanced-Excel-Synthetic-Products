# Advanced-Excel-Synthetic-Products
This repo contains synthetic/sample data structured to replicate a real-world retail analytics project. No confidential, proprietary, or identifiable data from any employer is included.

# Business Analyst & Reporting Portfolio — Luan Nguyen

Before you skim this and move on: every file in this folder is a **live, working Excel model** — not a screenshot, not a PDF export. Open any one of them and the pivot tables refresh, the VLOOKUPs resolve, and the dashboards recalculate in real time. If you want to see how someone actually thinks about reporting infrastructure rather than just talks about it, this is the fastest way to find out.

## Why these are worth five minutes of your time

These are eight reporting tools I built and maintained in a live retail operations environment — health & safety incident tracking, customer aggression scorecards, DC safety reporting, LMS/training compliance dashboards, and workforce rostering — covering roughly 19 months of operational reporting across a multi-brand retail group. I've swapped every real name, store, employee ID, and incident narrative for synthetic equivalents (so nothing here breaches a former employer's confidentiality), but the underlying architecture — every formula, every pivot table, every cross-sheet lookup — is untouched and fully functional. What you're looking at is the actual engineering, just with the real-world data blanked out.

## What's in the folder

| File | What it demonstrates |
|---|---|
| `19-month HS Claim incidents_synthetic.xlsx` | Multi-tab injury/claims tracker: raw data dump → feed logic → pivot summaries → chart-ready output, spanning 19 months of incident history. |
| `25_05 CustomerAggression Scorecard Calculator_synthetic.xlsx` | A scorecard rolling up security, psychosocial, and workplace injury incidents by store, brand, and fiscal period, with automatic YTD variance calculations. |
| `25_05 DC Safety Report Calculator_synthetic.xlsx` | Distribution centre incident and hazard reporting with automated month-over-month and 12-month trend views. |
| `25_07 Go1 Assigned Learning Dashboard Calculator_synthetic.xlsx` | A workforce-scale training compliance dashboard tracking assigned vs. completed learning across the full active employee base (11,000+ records). |
| `Mandatory Training Activites Calculator_synthetic.xlsx` | Compliance tracking by module and by brand, with pivot-driven status breakdowns and automated pie chart summaries. |
| `Roster_excel_V42.2_synthetic.xlsx` | A multi-brand rostering template with role-based dropdown validation, tolerance-hour logic, and store-level configuration across four retail banners. |
| `Work in Store Reporting Dashboard_synthetic.xlsx` | A consolidated store-performance dashboard pulling from per-brand feeds into unified pivot views. |
| `FFM timesheet template with breaks 8 July to 21 July_synthetic.xlsx` | A clean timesheet template with built-in break and total-hours formula logic. |

## What to actually click on when you open one

- **Any tab named `*FEED*` or `*Data Dump*`** — this is the raw layer everything else is built on. Worth a look at how the data is structured before it hits a formula.
- **Any `Pivot*` or `*Graphs*` tab** — these refresh live from the synthetic source data (they're flagged to auto-recalculate the moment the file opens).
- **`STORE LOOKUP` / `Store lookup` / `FIN CAL LOOKUP` tabs** — the reference tables that keep every VLOOKUP and fiscal-period join consistent across sheets.

## A quick note on the data

Names, store identities, employee IDs, and free-text incident narratives are all synthetic — generated so that no real individual or store from my previous employer is identifiable, while every date relationship, formula, and cross-sheet reference stays intact. If a number looks slightly different from what you'd expect operationally, that's the point: it's fictional data sitting inside real infrastructure.

If any of this is relevant to a role you're hiring for, I'd welcome the chance to walk through the build decisions behind any of these — happy to talk formulas, data architecture, or the reporting problems they were built to solve.

**Luan Nguyen**
Business Analyst · l.mnguyen@outlook.com
