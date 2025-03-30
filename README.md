# NBA Draft Prediction: Identifying Future All-Stars

## Overview
This project uses NCAA player statistics and NBA Draft Combine measurements to predict which players are most likely to become future NBA All-Stars. The model is designed from the perspective of a general manager making draft decisions, leveraging historical data and machine learning.

## Objectives
- **Identify Key Predictors** of NBA success using college stats and combine data
- **Train a Random Forest Classifier** to predict All-Star status
- **Assist NBA Front Offices** by generating actionable insights and rankings for draft prospects

## 📊 Data Sources
- [NBA Advanced Stats](https://www.nba.com/stats/players/advanced): Combine measurements (2000–2024)
- [RealGM](https://basketball.realgm.com/ncaa): NCAA player statistics (2003–2024)
- [Wikipedia](https://en.wikipedia.org/wiki/List_of_NBA_All-Stars): All-Star selections

## Modeling Approach
- Built a binary classification model using **Random Forest**
- Input features included: scoring, playmaking, efficiency, rebounding, physical measurements
- Trained on past players to evaluate prospects from 2020–2024

## Sample Results
Predicted All-Stars among players who played college ball between 2020–2024:

| Player            | Probability | Prediction |
|------------------|-------------|------------|
| Jaden Ivey       | 0.69        | Likely All-Star |
| Cade Cunningham* | 0.64        | Likely All-Star |
| Paolo Banchero*  | 0.54        | Likely All-Star |
| Zach Edey        | 0.52        | Likely All-Star |
| Keyonte George   | 0.50        | Likely All-Star |

> *Paolo Banchero and Cade Cunningham have already been selected as NBA All-Stars.