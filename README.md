# 23CSE301 — Machine Learning Capstone Project
## CardioSense · AeroFare · FinRisk

*Team: 20* 
*Members & track ownership:*
· Bandepalli Renuka — Regression-A
· Rupak E — Regression-B
· Vidhulashree M A — Classification-A

## Problem Statement
This capstone builds three end-to-end ML pipelines across Regression, Classification, and Clustering:

| Track | Dataset | Task |
|---|---|---|
| Regression | *AeroFare* (flight price data) | Predict flight ticket price (INR) from airline, route, class, duration, days-to-departure, stops |
| Classification | *CardioSense* (UCI Cleveland Heart Disease) | Predict presence/absence of heart disease from clinical features |
| Clustering (Review 2) | *FinRisk* (borrower/loan data) | Segment borrowers into risk archetypes, validated against default labels |

## Environment Setup
bash
python3 -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook


## How to Run
1. Open notebooks/capstone_review1.ipynb.
2. Run all cells top-to-bottom (Kernel → Restart & Run All). Datasets are pulled directly from public GitHub-hosted CSV mirrors at runtime — no manual download needed, provided you have internet access.
3. Outputs (tables, plots) are generated in place; no external files are required.

## Review 1 Scope
This notebook covers the *full Regression track* (10 algorithms on AeroFare) and *Classification Track Part A* (5 algorithms on CardioSense), per the Review 1 rubric. Classification Part B and the Clustering track (FinRisk) are reserved for Review 2.

## Results Summary
<paste your final R² leaderboard and classification comparison table here once the notebook has been run, e.g. best regression model + R², best classifier + weighted F1>

## Academic Integrity
Any code adapted from external sources (StackOverflow, blogs, etc.) is cited inline as a Markdown comment in the notebook. Generative AI tools were used for code scaffolding only, not for analysis or interpretation, per course policy.
