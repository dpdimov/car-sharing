# Car-Share Venture: Financial Model Explorer

An interactive financial modeling tool for analyzing the unit economics of a car-sharing business.

## Overview

This single-page application provides a comprehensive framework for exploring the financial dynamics of a car-share venture, including pricing strategies, cost structures, and customer lifetime value analysis.

## Features

### Pricing Strategy
Adjust key pricing levers (annual membership fee, hourly rate, per-mile charge) and instantly see their impact on 5-year revenue projections, net income, and breakeven timing.

### Cost Structure
Visualize how local office costs break down across four categories:
- Per-member costs (billing, servicing)
- Per-new-member costs (background checks, processing)
- Marketing spend
- Fixed office overhead

### Plan vs Actual
Compare planned assumptions against actual September operating data, with:
- Variance waterfall analysis
- Hourly vs daily use economics breakdown
- Daily rate explorer for pricing adjustments

### Unit Economics Simulator
View the same gross margin from three perspectives:
- **Per Use** - Revenue, cost, and margin per trip
- **Per Member** - Monthly economics per customer
- **Per Car** - Asset-level profitability and overhead coverage

### Sensitivity Analysis
Identify which assumptions matter most through:
- Tornado chart showing Year 3 net income sensitivity
- Two-way heatmap (hourly rate vs members per car)

### Lifetime Value
Model customer LTV with adjustable:
- Monthly margin per member
- Annual attrition rate
- Customer acquisition cost

Includes cohort survival curves and cumulative margin visualization.

## Usage

Open `carshare-model.html` in any modern web browser. All calculations run client-side with no server dependencies.

## Live Demo

View the tool at: https://dpdimov.github.io/car-sharing/carshare-model.html
