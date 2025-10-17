# NBA Game Outcomes — Exploratory Data Analysis (2020–2024)

This project investigates team- and player-level statistical trends associated with NBA regular-season wins from 2020–2024.  
All analyses are reproducible and run end-to-end in `nba_eda.ipynb`.

---

## Objectives
- Identify key pre-game statistical indicators correlated with winning.
- Visualize team “strategic profiles” (pace vs defensive strength, etc.).
- Avoid data leakage by using only prior-game information for feature engineering.

---

##  Data
- **Source:** Public regular-season box scores (scraped 2010–2024).  https://github.com/NocturneBear/NBA-Data-2010-2024
- **Processing:** Filtered to seasons 2020–2024; removed playoffs; computed rolling last-5-game averages shifted by one game to avoid look-ahead bias.  

---

