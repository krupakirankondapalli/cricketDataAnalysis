# Cricket Data Analysis

## Overview
This project uses data analytics to support selecting the best playing eleven for the T20 World Cup 2022. Instead of relying on subjective judgment alone, it applies data science techniques to deliver a more objective, transparent, and evidence-based team selection process.

## What the project does
- Collects and prepares cricket performance data
- Builds a reusable data model for analysis
- Uses Power BI for visualization and interactive reporting
- Identifies top players for key match roles
- Supports data-driven decision making for team selection

## Data collection and preparation
- Raw data was sourced from ESPNcricinfo using third-party scraping tools.
- Collected statistics include batting, bowling, fielding, and match-level details.
- Python was used to clean and transform the data:
  - handle missing values
  - normalize formats
  - create derived features
- The final datasets are ready for analysis and reporting.

## Modeling and analysis
- A Power BI data model was built to link players, matches, and performance metrics.
- DAX calculations create dynamic measures and calculated columns.
- What-if analysis and parameter controls improve flexibility and scenario testing.
- Players are ranked by role using performance, consistency, and form metrics.

## Key focus areas
- Opening batters
- Middle-order anchors
- Power hitters
- Spin bowlers
- Pace bowlers

## Visualization
- Interactive dashboards display player comparisons and team balance.
- Reports include drill-throughs, tooltips, and filtering controls.
- Stakeholders can explore performance across multiple dimensions.

## Outcome
The result is a balanced playing eleven supported by rigorous analysis. This approach reduces bias, highlights strengths across batting and bowling, and makes team selection more defensible.

## Files included
- `data_cleaning.ipynb` — notebook for cleaning and exploring the data
- `dim_match_summary.csv` — match summary dimension data
- `dim_players_no_images.csv` — player dimension data without image fields
- `fact_bating_summary.csv` — batting performance facts
- `fact_bowling_summary.csv` — bowling performance facts
- `t20_wc_batting_summary.json` — batting summary JSON
- `t20_wc_bowling_summary.json` — bowling summary JSON
- `t20_wc_match_results.json` — match results data
- `t20_wc_player_info.json` — player profile data

## How to use
1. Open `data_cleaning.ipynb` to inspect and clean the raw data.
2. Load the cleaned CSV or JSON files into Power BI.
3. Use the data model to build dashboards and calculate role-based rankings.

## Notes
This project combines cricket statistics with visualization best practices to make team selection more reliable and easier to understand.
