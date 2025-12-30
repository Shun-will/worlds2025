# Worlds 2025 Champion Pick & Ban Analysis

## Overview
This project analyzes champion pick and ban trends from Worlds 2025 matches using Python and Jupyter Notebook.
The goal is to explore meta trends such as pick rate, ban rate, and win rate for each champion.

Before the tournament, there was an event where players could predict champions for categories like "Most Kills" and "Most Bans".
Correct predictions rewarded points, and accumulating enough points could earn exclusive in-game skins.
Because of this, I wanted to track pick and ban trends in near real time to make better predictions, which led me to create this project.

## Data
The data was manually collected and entered into an Excel file based on Worlds 2025 match records.
Each match includes champion picks (Pick1–Pick5), bans (Ban1–Ban5), team name, and match result (Win/Lose).

Note:  
The original Excel file is not included in this repository because it was accidentally deleted.
However, this project focuses on demonstrating data processing, aggregation, and visualization skills.

## Method
- Reshaped pick and ban data using `pandas.melt`
- Cleaned text data (team names, champion names, results)
- Calculated:
  - Pick count and pick rate
  - Ban count and ban rate
  - Win rate per champion
- Identified:
  - Most picked champions
  - Most banned champions
  - Best and worst win rates (minimum 5 games)
  - Number of unique champions used by each team
- Visualized top 10 champions by pick rate and ban rate using Matplotlib

## Result
- Popular meta champions were identified through pick and ban rates.
- Win rate analysis revealed champions with strong and weak performance when picked frequently.
- Differences in champion pool size were observed between teams.

## Tools
- Python
- Pandas
- Matplotlib
- JupyterLab

## Files
- `world2025_analysis.ipynb` : main analysis notebook
