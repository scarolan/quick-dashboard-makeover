# CLAUDE.md - Quick Dashboard Makeover Workshop

## Repository Overview

This repository contains materials for a hands-on Grafana workshop called "Extreme Dashboard Makeover". The workshop teaches participants how to transform boring, hard-to-read dashboards into visually appealing, informative monitoring tools using Grafana's features.

## Purpose

This is an educational workshop designed to teach:
- Grafana visualization techniques and best practices
- Dashboard design principles for operational monitoring
- How to transform raw data into actionable visual insights
- Effective use of colors, thresholds, and visual indicators

## Repository Structure

```
quick-dashboard-makeover/
├── README.md                          # Main workshop introduction
├── Dashboards/
│   ├── Overcharge.json               # Starting dashboard for Exercise 1
│   ├── Overcharge_Completed.json     # Reference solution for Exercise 1
│   ├── KitchenOps.json               # Starting dashboard for Exercise 2
│   └── KitchenOps_Completed.json     # Reference solution for Exercise 2
└── Labs/
    ├── 01_ExtremeDashboard.md        # Exercise 1: Overcharge Energy Drink SRE dashboard
    └── 02_KitchenOps.md              # Exercise 2: Restaurant kitchen monitoring dashboard
```

## Workshop Exercises

### Exercise 1: Overcharge Dashboard Makeover
**Theme:** Energy drink company (Overcharge™) SRE monitoring
**Focus:** Transform a functional but boring dashboard monitoring:
- RED metrics (Request rates, Error rates, Duration/latency)
- Kubernetes pod status
- Geographic user activity

**Key Transformations:**
1. Error Rates → Stat panel with SLO thresholds
2. K8s Service Status → Visual status board with color indicators
3. Customer Activity → Geographic heatmap
4. Latency Graph → Enhanced with better color distinction
5. Request Rates → Bar gauge with thresholds
6. Logo Addition → Professional branding with HTML panel
7. Layout Optimization → Logical grouping and sizing

### Exercise 2: KitchenOps Challenge
**Theme:** Restaurant kitchen operations monitoring
**Focus:** Create a Michelin-star worthy monitoring dashboard for:
- Spice freshness tracking (4-month threshold)
- Grill temperature (387°F ±7°)
- Salmon cooking times (150 seconds per side)
- Refrigerator temperature (35-38°F)
- MacOven temperature (375°F ±25°)
- Dining room lighting (100% operational)
- Room temperature across 8 zones (70°F ±1°)

## Technical Requirements

- Grafana instance (Cloud or OSS)
- TestData data source (built-in)
- Modern web browser
- Optional: Killercoda environment (https://killercoda.com/scarolan/scenario/grafana-dashboarding)

## Key Grafana Concepts Covered

1. **Visualization Types:**
   - Time Series → Stat panels
   - Tables → Visual status indicators
   - Geomaps for geographic data
   - Bar gauges for current values
   - HTML/Text panels for branding

2. **Design Principles:**
   - Color coding for status (blue/green = good, yellow = warning, orange/red = critical)
   - Thresholds and value mappings
   - Background gradients vs. solid colors
   - Horizontal vs. vertical orientation

3. **Data Transformations:**
   - Organize fields
   - Hide unnecessary data
   - Field renaming

4. **Dashboard Management:**
   - Saving and versioning
   - Panel arrangement and sizing
   - Logical grouping of related metrics

## How to Help Users

When users are working through this workshop:

1. **Understand Context:** They're learning Grafana dashboard design, not building production systems
2. **Reference Lab Files:** The step-by-step instructions in Labs/ are authoritative
3. **Completed Dashboards:** Use *_Completed.json files as reference solutions
4. **Encourage Exploration:** The workshop is about learning through doing
5. **Visual Design Focus:** Emphasize that good dashboards communicate status at a glance

## Common User Needs

Users may ask for help with:
- Finding specific Grafana panel options
- Understanding why certain visualization choices are better
- Troubleshooting panel configurations
- Importing dashboards or data sources
- Understanding dashboard design principles
- Customizing beyond the workshop instructions

## Design Philosophy

The workshop teaches that effective dashboards should:
- Communicate insights at a glance
- Use color meaningfully (not just decoratively)
- Show current status, not just historical trends
- Minimize cognitive load through clear visual hierarchy
- Group related information logically
- Use appropriate visualizations for data types

## Notes for AI Assistants

- This is an educational workshop focused on learning, not production deployment
- The TestData data source provides simulated data for safe experimentation
- Completed dashboard files exist as reference solutions, but learning happens through the transformation process
- Dashboard design is subjective - multiple valid approaches exist
- The Overcharge and KitchenOps themes add fun narrative context to technical learning
