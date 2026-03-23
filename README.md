# Complete Football Analytics in Python
 Implementation of [McKay Johns'](https://mckayjohns.com) **Complete Football Analytics in Python** course — covering everything from data collection to machine learning models and professional-grade visualizations.

---

## Overview

This repository contains all notebooks, scripts, and outputs produced throughout the course. The work spans four main areas: data sourcing, visualization, machine learning, and end-to-end projects. Each module builds on the previous one, going from raw scraped data all the way to trained models and publication-ready charts.

---

## Repository Structure

```
complete-football-analytics/
│
├── 01_python_fundamentals/
│   ├── 1.1_syntax.ipynb
│   ├── 1.2_variables.ipynb
│   ├── 1.3_data_types.ipynb
│   ├── 1.4_conditionals.ipynb
│   ├── 1.5_loops.ipynb
│   ├── 1.6_functions.ipynb
│   └── 1.7_error_handling.ipynb
│
├── 02_football_concepts/
│   ├── 2.1_types_of_data.ipynb
│   ├── 2.2_key_metrics.ipynb
│   └── 2.3_common_python_terms.ipynb
│
├── 03_data_collection/
│   ├── 3.1_web_scraping_basics.ipynb
│   ├── 3.2_statsbomb_api.ipynb
│   ├── 3.3_fbref.ipynb
│   ├── 3.4_sofascore.ipynb
│   ├── 3.5_understat.ipynb
│   ├── 3.6_fotmob.ipynb
│   ├── 3.7_whoscored.ipynb
│   └── 3.8_soccerdata_package.ipynb
│
├── 04_visualizations/
│   ├── 4.1_matplotlib_seaborn.ipynb
│   ├── 4.2_scatterplots.ipynb
│   ├── 4.3_radar_charts.ipynb
│   ├── 4.4_pizza_plots.ipynb
│   ├── 4.5_tables.ipynb
│   ├── 4.6_xg_flow_charts.ipynb
│   ├── 4.7_creating_a_pitch.ipynb
│   ├── 4.8_pass_maps.ipynb
│   ├── 4.9_shot_maps.ipynb
│   ├── 4.10_heatmaps.ipynb
│   └── 4.11_pass_networks.ipynb
│
├── 05_machine_learning/
│   ├── 5.1_intro_to_ml.ipynb
│   ├── 5.2_data_cleaning_feature_engineering.ipynb
│   ├── 5.3_xg_model.ipynb
│   └── 5.4_model_evaluation.ipynb
│
├── projects/
│   ├── project_01/
│   └── project_02/
│
├── data/
│   └── .gitkeep
│
├── requirements.txt
└── README.md
```

---

## Modules

### Module 1 — Python Fundamentals
Core Python needed to work with football data. Covers syntax, variables, data types (booleans, numbers, strings, lists, tuples, dicts), conditionals, loops, functions, and error handling.

### Module 2 — Football Analytics Concepts
Introduction to the types of data used in football analytics (event data, tracking data, aggregated stats) and the key metrics that matter: xG, xA, progressive passes, PPDA, and more.

### Module 3 — Data Collection
Pulling data from multiple sources using Python:

| Source | Method |
|---|---|
| StatsBomb | Official open data API |
| FBref | Web scraping |
| Sofascore | Web scraping |
| Understat | Web scraping |
| Fotmob | Web scraping |
| WhoScored | Web scraping |
| Soccerdata | Python package |

### Module 4 — Visualizations
Building every major chart type used in professional football analytics, all from scratch using `mplsoccer` and `matplotlib`:

- **Scatterplots** — player comparison across any two metrics
- **Radar Charts** — multi-attribute player profiles
- **Pizza Plots** — percentile-based player radars
- **Tables** — styled stat tables for reporting
- **xG Flow Charts** — match momentum over time
- **Pitch** — drawing and customizing a football pitch
- **Pass Maps** — directional pass plotting by player or team
- **Shot Maps** — shot location, outcome, and xG value
- **Heatmaps** — spatial player activity across the pitch
- **Pass Networks** — team connectivity and average positions

### Module 5 — Machine Learning
Building an Expected Goals (xG) model end to end:

- Sourcing and structuring raw shot data
- Data cleaning: dropping irrelevant rows, handling nulls, casting types
- Feature engineering: `shot_distance`, `shot_angle`, `is_header`, zone encoding
- Categorical encoding for model compatibility
- Training a classifier with `scikit-learn`
- Evaluating model output and interpreting xG probability scores

---

## Setup

**Clone the repo**
```bash
git clone https://github.com/Muhammadatef/football-data-analytics.git
cd complete-football-analytics
```

**Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

**Install dependencies**
```bash
pip install -r requirements.txt
```

**requirements.txt includes:**
```
pandas
numpy
matplotlib
mplsoccer
scikit-learn
requests
beautifulsoup4
soccerdata
statsbombpy
highlight-text
```

---

## Projects

Two end-to-end portfolio projects built as part of the course, applying all the above skills to real match and player data.

Details inside each project folder.

---

## Data Sources

All data used in this repository is publicly available:

- [StatsBomb Open Data](https://github.com/statsbomb/open-data)
- [FBref](https://fbref.com)
- [Understat](https://understat.com)
- [Sofascore](https://sofascore.com)
- [Fotmob](https://fotmob.com)
- [WhoScored](https://whoscored.com)

---

## Course

Based on the [Complete Football Analytics in Python](https://courses.mckayjohns.com/courses/football-analytics-course) course by McKay Johns.

All code in this repo is my own implementation written while following the course. It is not a copy of the course material.

---

## Author

**Mohamed Atef Fahmi**
Senior Data Engineer 

[LinkedIn]([https://linkedin.com/in/your-profile](https://www.linkedin.com/in/mohamed-atef-fahmy-khalil/))
