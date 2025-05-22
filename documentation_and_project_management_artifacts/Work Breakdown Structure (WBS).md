# Work Breakdown Structure (WBS)

## 1. Data Collection
- 1.1 Download Cubs and White Sox team statistics (batting, pitching, fielding) from ESPN
- 1.2 Gather head-to-head matchup data from ChampsOrChumps

## 2. Data Processing
- 2.1 Clean batting, pitching, and fielding tables
- 2.2 Convert numeric columns and handle invalid rows
- 2.3 Calculate team averages and extract best pitchers

## 3. Model Development
- 3.1 Define strength scoring function combining OPS, WAR, ERA, WHIP, DWAR
- 3.2 Integrate historical win rate and average score difference into scoring
- 3.3 Implement Monte Carlo simulation using NumPy
- 3.4 Output win probabilities and display team comparison

## 4. Project Management
- 4.1 Write project documentation (Specs, WBS, Backlog, Logs)
- 4.2 Organize directory structure and ensure reproducibility
