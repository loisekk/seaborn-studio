<div align="center">

<img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width="300" alt="Seaborn Logo"/>

# 📊 Seaborn – Data Visualization Series

**A complete hands-on Seaborn learning series using real IPL 2022 match data.**

![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-square&logo=python)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13+-teal?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Dataset](https://img.shields.io/badge/Dataset-IPL%202022-purple?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

</div>

---

## 📁 Repository Structure

```
seaborn-series/
│
├── Introduction___Relational_Plots.ipynb     # Class 1 – scatterplot, lineplot
├── Categorical_Plots.ipynb                   # Class 2 – barplot, boxplot, violin, swarm
├── Distribution_Plots.ipynb                  # Class 3 – histplot, kdeplot, rugplot
├── Regression___Mixed_Plots.ipynb            # Class 4 – regplot, lmplot, jointplot, pairplot
├── MatrixGrid_Plots___Styling.ipynb          # Class 5 & 6 – heatmap, clustermap, themes
│
├── IPL.csv                                   # Dataset – IPL 2022 season match data
└── requirements.txt
```

---

## 📚 Notebooks Overview

| # | Notebook | Topics Covered |
|---|----------|----------------|
| 1 | `Introduction & Relational Plots` | `scatterplot()`, `lineplot()`, color palettes, styles |
| 2 | `Categorical Plots` | `barplot()`, `countplot()`, `boxplot()`, `violinplot()`, `stripplot()`, `swarmplot()` |
| 3 | `Distribution Plots` | `histplot()`, `kdeplot()`, `rugplot()`, hue-based multi-distribution |
| 4 | `Regression & Mixed Plots` | `regplot()`, `lmplot()`, `jointplot()`, `pairplot()` |
| 5 & 6 | `Matrix/Grid Plots + Styling` | `heatmap()`, `clustermap()`, themes, styling |

---

## 🏏 Dataset – IPL 2022

The dataset `IPL.csv` contains match-level data from the **IPL 2022 season**.

| Column | Description |
|--------|-------------|
| `match_id` | Unique match identifier |
| `date` | Match date |
| `venue` | Stadium and city |
| `team1` / `team2` | Competing teams |
| `stage` | Group / Playoff |
| `toss_winner` | Team that won the toss |
| `toss_decision` | Bat or Field |
| `first_ings_score` / `second_ings_score` | Innings totals |
| `match_winner` | Winning team |
| `won_by` | Runs or Wickets |
| `margin` | Margin of victory |
| `player_of_the_match` | POTM award |
| `top_scorer` | Highest run-scorer |
| `highscore` | Top individual score |
| `best_bowling` / `best_bowling_figure` | Best bowling performance |

---

## ⚙️ Setup & Usage

### 1. Clone the repository

```bash
git clone https://github.com/loisekk/seaborn-series.git
cd seaborn-series
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

Open any notebook from the file browser and run cells sequentially.

---

## 🛠️ Tech Stack

- **Python 3.12**
- **Seaborn** – high-level visualization
- **Matplotlib** – underlying rendering engine
- **Pandas** – data loading and manipulation
- **NumPy** – numerical operations
- **Jupyter Notebook** – interactive environment

---

## 👤 Author

**Yash Brahmankar**  
B.Tech AI & ML | OIST (2024–2028)  
[![GitHub](https://img.shields.io/badge/GitHub-loisekk-black?style=flat-square&logo=github)](https://github.com/loisekk)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
