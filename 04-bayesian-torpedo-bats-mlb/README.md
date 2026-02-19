# Torpedo Bat Performance Analysis (R)

## Project Overview
This project evaluates whether the adoption of torpedo bats were associated with meaningful changes in offensive performance among MLB players. I focused on a subset of players who consistently used the torpedo bat and compared their performance in the 2024 season to their performance early in the 2025 season (as of May 2025).

## Objective
To assess whether changes in batting average (BA), on-base percentage (OBP), and slugging percentage (SLG) were statistically meaningful after players began using torpedo bats, while accounting for differences between players and seasonal variability.

## Data & Tools
- Tool: R
- Packages: nimble, coda, MCMCvis
- Data: Player-level batting statistics from the 2024 season and early 2025 season
- Metrics analyzed: BA, OBP, SLG

## Methods
- Selected a group of MLB players who consistently used the torpedo bats
- Compiled their BA, OBP, and SLG from the 2024 season and from the games played in 2025 up to May
- Built a Bayesian hierarchical regression model for each statistic using random effects for season
- Used MCMC sampling to estimate posterior distribution of model coefficients
- Evaluated convergence and effective sample size using coda and MCMCvis diagnostics

## Key Insights
- Posterior estimates indicated modest changes in BA, OBP, and SLG, with no credible intervals for coefficients overlapping zero
- Players that were frequently using the torpedo bat had higher BA and SLG than the league average (as of May 3, 2025)
- Effective sample size diagnostics confirmed stable MCMC convergence, supporting the reliability of posterior estimates despite early-season limitations 

## Notes
This project demonstrates the application of Bayesian mixed-effects modeling in a sports analytics context, with a focus on uncertainty quantifications and convergence diagnostics using MCMC effects.
