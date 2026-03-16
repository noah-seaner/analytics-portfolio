# Simulations During Lafayette's 2025-26 Season

## Project Overview
This project contains a series of simulation models developed through Lafayette's 2025-26 basketball season to predict performance compared to Patriot League opponents and forecast conference tournament outcomes. Rather than relying on a single static model, the simulations were updated and expanded as the season progressed, incorporating new game data to refine projections.

The framework includes a pre-conference play projection based on non-conference games, iterative updates throughout conference play, and a simulation of the conference tournament bracket. Together these models, provided a probabilistic view of how the season would unfold for Lafayette and the other teams in the conference.

## Objective
To estimate possible conference records and tournament outcomes using simulation-based forecasting while updating projections dynamically as new game results became available.

## Data & Tools
- **Tool:** R
- **Approach:** Monte Carlo simulation
- **Data:** Game-level team performance metrics from both non-conference and conference play

## Simulation Components

### Non-Conference-Based Conference Simulation
The initial model used performance metrics from non-conference games to simulate potential conference outcomes. This provided an early estimate of how teams might perform once conference play began.

### Iterative Conference Season Simulation
As conference games were played, the model was updated to incorporate new performance data. These updates refined projections of possible conference records and helped track how the distribution of outcomes evolved throughout the season.

### Conference Tournament Simulation
A separate simulation modeled potential conference tournament brackets. By simulating many possible tournament paths, the model estimated how likely different teams were to advance through each round.

## Simulation Approach
- Calculated team performance metrics using game-level data
- Generated thousands of simulated conference seasons (10,000) and tournament outcomes (50,000)
- Updated simulations iteratively as new games were played
- Summarized results using probability distributions and outcome tables

## Key Insights
- Early simulations based on non-conference performance suggested that Lafayette would likely finish in 7th 
