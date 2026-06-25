# FI-System — Real-Estate FIRE Planner

A single-file interactive dashboard for planning a real-estate path to financial independence (FIRE).

**Live:** https://yufliu.github.io/fi-system/

## What it does
- **Where I am now** — editable current portfolio + other income.
- **Where I'm going** — a passive-income FIRE target ($400K / $300K).
- **How / how long** — an acquire-then-snowball (debt-payoff) engine with best / realistic / worst scenarios and a do-nothing floor.
- **Mortgage/PITI calculator** for a "typical door" you'd buy, with editable expenses.
- **LTR ↔ STR/MTR toggle** that re-rates the whole model, plus a side-by-side strategy comparison and interest-rate sensitivity.
- Charts (Chart.js) for income vs target, doors owned vs paid off, and equity vs debt.

All inputs live-recompute and persist in your browser (localStorage) — nothing is sent anywhere.

## Run locally
Just open `index.html` in a browser (charts need internet for the Chart.js CDN).

## Caveats
Figures are pre-tax, exclude appreciation, and assume rents are flat unless a growth rate is set. The snowball assumes all rental cash flow plus your annual contribution is reinvested.
