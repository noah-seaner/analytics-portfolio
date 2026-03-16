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
- Early simulations based on non-conference performance suggested that Lafayette would likely finish near the bottom of the conference standings. The most common simulated outcomes clustered around a 9th-place finish, but within a couple of games of the other teams, indicating that Lafayette's season would be closely contested within the conference.
- As conference games were incorporated into the model, projections became more stable and the range of possible outcomes narrowed. This reflected how real game results reduced uncertainty in the simulation over time. Lafayette ultimately finished in 7th place in the Patriot League standings with one more win than they were expected to have in earlier simulations.
- Throughout conference play, simulations highlighted how small differences in performance could significantly impact Lafayette's projected standing. Because several teams had similar performance profiles, individual game outcomes often shifted simulated finishing positions by multiple places.
- Tournament simulations showed that while most projected brackets followed expected seeding patterns, upset scenarios remained possible due to relatively small differences between teams. In the actual tournament, the bracket largely followed seed expectations, with Lafayette's first-round loss and Navy's semifinal loss representing the only upsets.
- Overall, the project demonstrated how simulation-based forecasting can provide a dynamic view of a season, allowing projections for a specific team like Lafayette to evolve as new performance data becomes available.

## Notes
This project illustrates how simulation models can be used throughout a season to track and forecast team performance. By updating projections as new data becomes available, simulations can provide a more flexible and informative perspective than static season predictions.
