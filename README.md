# Baseball-Simulation

# Cubs vs White Sox Simulation (2025)

This project predicts the outcome of the May 18, 2025 matchup between the **Chicago Cubs** and **Chicago White Sox** using a Monte Carlo simulation based on current season statistics and historical head-to-head data.

---

## Objective

The goal is to estimate the win probability for each team using:

- Batting statistics (OPS, WAR, OBP, SLG, AVG)
- Pitching statistics (ERA, WHIP)
- Fielding metrics (DWAR)
- Historical matchup win rates and scoring margins

---

## Data Sources

| Type       | Source |
|------------|--------|
| Batting & Pitching Stats | [ESPN Cubs & White Sox Team Stats (2025)](https://www.espn.com/mlb/team/stats/_/type/fielding/name/chw/season/2025/seasontype/2) |
| Historical Matchup Data  | [Champs or Chumps: Cubs vs White Sox Head-to-Head](https://champsorchumps.us/team/mlb/chicago-cubs/head-to-head/chicago-white-sox) |

---

## Methodology

1. **Load raw team data** from ESPN (batting, pitching, fielding).
2. **Clean and average** each team’s performance metrics.
3. **Incorporate historical win rate** and average score difference.
4. **Calculate team strength score** using a weighted formula.
5. **Run Monte Carlo simulation** (10,000 games) to estimate win probability.

---


## Simulation Result

| Team        | Win Probability |
|-------------|------------------|
| **Cubs**    | 91.65%           |
| **White Sox** | 8.35%          |

These results reflect the Cubs' stronger offensive metrics and more efficient pitching, combined with a historically better win rate in head-to-head matchups.

---

## AI Collaboration

This simulation was developed using ChatGPT as an AI collaborator to:

- Guide metric selection and scoring weight design
- Generate the simulation pipeline in Jupyter
- Automate data cleaning and scoring logic
- Interpret and validate results

All code and project documentation were co-created with human supervision and iterative testing.

---

## Disclaimer

This project is for educational and simulation purposes only. Results do not reflect real betting advice or actual game outcomes.
