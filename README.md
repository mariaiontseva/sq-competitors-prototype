# SmarterQueue — Discover Competitors prototype

Static HTML prototype exploring a "Discover → Competitors" tab inside SmarterQueue.

## What's in here

A single self-contained `index.html` (no build step, no dependencies). Open it directly in a browser.

```bash
open index.html
```

## Layout

- **Sidebar** — `Overview` entry at top + tracked competitors (Hootsuite, Sprout Social, Metricool) + Reports.
- **Overview view** — your rank summary, audience / engagement / posting-frequency leaderboards, full-width cross-competitor top posts, normalised follower-growth chart for everyone.
- **Per-competitor view** — profile header, "Compare with your profiles" overlay toggle (IG / X / LI), KPI cards with `vs You` deltas, two charts (follower growth, engagement-rate over time), side-by-side metrics table, top posts, auto-generated "what they're doing differently" panel.

Every leaderboard row drills into the corresponding competitor; sidebar always reflects the current selection.

## Mock data

SmarterQueue is roughly equal to Metricool in audience; Hootsuite and Sprout Social are an order of magnitude bigger. Engagement story is inverted — smaller brands have higher rates.

## Reference

Competitor research that fed into the design lives in this Figma file (Metricool / Rival IQ / Sprout Social screenshots): see the team's `Explorations 2026` board.
