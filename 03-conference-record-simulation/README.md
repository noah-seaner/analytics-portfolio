# Conference Record Prediction & Simulation Model (R)

## Project Overview
This project focuses on predicting conference performance using game-level team metrics and simulation techniques. Rather than relying on a single static model, the framework simulates possible conference outcomes based on how a team performed in non-conference and early conference games. The model is updated iteratively throughout the season as new game data becomes available.

## Objective
To simulate and forecast a team's conference record using performance metrics such as offensive and defensive efficiency, pace, and shooting outcomes, and to update those projections dynamically as additional games are played.

## Data & Tools
- Tool: R
- Data: Game-level team performance metrics (offensive rating, defensive rating, pace, shooting statistics, etc.)
- Approach: Simulation-based forecasting driven by observed team performances

## Methods
- Calculated key performance metrics from non-conference and early conference games
- Built a simulation framework to generate any possible conference outcomes based on those metrics
- Update simulations iteratively as new games are played to reflect changes in team performance
- Compared simulated record distributions to actual results to evaluate predictive accuracy

## Key Insights
- Based on only non-conference games, simulated records varied depending on the team, but the most likely records were clustered around 6-12 wins, with the median projected record sitting at 9 wins
- Iteratively updating the model after each conference game increased the spread of the simulated records, with the most likely records currently clustered between 5-16 wins, while the median projected record still sits at 9 wins
- Lafayette finished the season with one more win than they were projected to before the start of the conference season.
- Looking ahead to the conference tournament, Navy has the highest odds of winning at about 65%; Lafayette's odds for the Patriot League title sit at 

## Notes
This project reflects an applied sports analytics workflow where models are continuously updated during the season to incorporate new information and improve forecast accuracy.
