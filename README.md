# Complete Football Analytics in Python

The official code repository for the [Complete Football Analytics in Python](https://courses.mckayjohns.com/courses/football-analytics-course) course by [McKay Johns](https://mckayjohns.com).

This repo contains all notebooks, scripts, and code referenced throughout the course — covering Python fundamentals, data collection from major football data sources, professional-grade visualizations, and machine learning models.

---

## Course

> **10+ hours of structured, no-fluff football analytics training.**
> Go from zero to building real analytical tools used by professionals in the game.

The course is available at: [courses.mckayjohns.com](https://courses.mckayjohns.com/courses/football-analytics-course)

---

## What You Will Learn

- Python from scratch, applied directly to football data problems
- How to collect data from every major football data source
- How to build every visualization type used by professional analysts
- How to build and train a machine learning xG model end to end
- How to structure two portfolio projects from real data

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
├── requirements.txt
└── README.md
```

---

## Modules

### Module 1 — Python Fundamentals
Everything you need to get started writing Python for football analytics. No prior experience required.

Topics: syntax, variables, data types, conditionals, for and while loops, functions, error handling.

### Module 2 — Football Analytics Concepts
Before writing a single line of analysis, you need to understand the data landscape. This module covers the types of data used in football analytics and the metrics that matter.

Topics: event data vs. tracking data vs. aggregated stats, key metrics (xG, xA, progressive passes, PPDA, and more).

### Module 3 — Data Collection
Learn how to source football data from every major platform using Python — web scraping, APIs, and dedicated packages.

| Source | Method |
|---|---|
| StatsBomb | Open Data API via `statsbombpy` |
| FBref | Web scraping |
| Sofascore | Web scraping |
| Understat | Web scraping |
| Fotmob | Web scraping |
| WhoScored | Web scraping |
| Soccerdata | Python package |

### Module 4 — Visualizations
Build every major chart type used in professional football analytics from scratch. All visualizations use `mplsoccer` and `matplotlib`.

| Visualization | Description |
|---|---|
| Scatterplots | Compare players across any two metrics |
| Radar Charts | Multi-attribute player profiles |
| Pizza Plots | Percentile-based player radars |
| Tables | Styled stat tables for reporting |
| xG Flow Charts | Match momentum and cumulative xG over time |
| Pitch | Drawing and customizing a football pitch |
| Pass Maps | Directional pass plotting by player or team |
| Shot Maps | Shot location, outcome, and xG value on pitch |
| Heatmaps | Spatial player activity across the pitch |
| Pass Networks | Team connectivity and average positions |

### Module 5 — Machine Learning
Build a working Expected Goals (xG) model from scratch using real shot data.

- Sourcing and structuring raw shot data
- Data cleaning: null handling, type casting, removing own goals
- Feature engineering: `shot_distance`, `shot_angle`, `is_header`, zone encoding
- Categorical encoding with scikit-learn
- Training and evaluating a classifier
- Generating xG probability scores from model output

---

## Setup

**Requirements**

- Python 3.8+
- Jupyter Notebook or JupyterLab

**Installation**

```bash
git clone https://github.com/mckayjohns/complete-football-analytics.git
cd complete-football-analytics

python -m venv venv
source venv/bin/activate       # Windows: venv\Scripts\activate

pip install -r requirements.txt
```

**Dependencies**

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

## Data Sources

All data used in this course is publicly available:

- [StatsBomb Open Data](https://github.com/statsbomb/open-data)
- [FBref](https://fbref.com)
- [Understat](https://understat.com)
- [Sofascore](https://sofascore.com)
- [Fotmob](https://fotmob.com)
- [WhoScored](https://whoscored.com)

---

## Note on Course Updates

As of November 2025, active updates to the course have stopped. All existing code and notebooks remain relevant and functional. No additional modules will be added.

---

## About McKay Johns

McKay Johns has been creating football analytics content and tutorials for over four years. His YouTube channel, courses, and newsletter have helped thousands of analysts and engineers break into the field.

- Website: [mckayjohns.com](https://mckayjohns.com)
- YouTube: [youtube.com/@mckayjohns](https://youtube.com/@mckayjohns)
- Newsletter: [mckayjohns.substack.com](https://mckayjohns.substack.com)
- Course: [courses.mckayjohns.com](https://courses.mckayjohns.com)

---

## License

This repository is provided for educational use in conjunction with the Complete Football Analytics in Python course.
