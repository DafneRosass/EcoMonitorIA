# 🌱 EcoMonitor AI — Smart Resource & Carbon Footprint Analyzer

Submission for the **STEM2Connect AI Hackathon 2026** (Track: **Sustainability**).

## Overview
**EcoMonitor AI** is a lightweight, zero-dependency web application that analyzes daily personal resource consumption (electricity, water, transportation, and diet) using a heuristic scoring and anomaly-detection engine. Instead of relying on expensive external cloud APIs, it runs locally in the browser to compute weekly $\text{CO}_2\text{e}$ emissions, water footprint, and personalized optimization strategies in real time.

## Features
- **Interactive Telemetry Inputs:** Sliders and selectors for computing hours, water consumption, commute distance, transit mode, and dietary habits.
- **Heuristic AI Scoring Engine:** Evaluates multi-variable environmental load on a 0–100 scale and flags consumption anomalies (`OPTIMAL`, `MODERATE LOAD`, `HIGH ANOMALY`).
- **Visual Breakdown:** Real-time distribution bars comparing energy, transportation, and water/lifestyle impact.
- **Actionable Recommendations:** Dynamically calculates potential water (liters) and carbon ($\text{kg CO}_2\text{e}$) savings based on detected user bottlenecks.

## How to Run
1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari). No build tools, servers, or API keys are required.

## AI Usage Disclosure
In accordance with the STEM2Connect AI Hackathon 2026 rules:
- **Tools Used:** Google Gemini.
- **Contribution:** Used as a coding and design assistant to structure the responsive HTML/CSS interface, refine the JavaScript heuristic scoring formulas, and draft project documentation. All logic, parameter thresholds, and testing were reviewed and verified by the author.