# Estimates of Thiamine-dependent fry mortality
Estimates of thiamine-dependent fry mortality for winter-run Chinook salmon

Last updated 10/29/2024, Miles Daniels (miedanie@ucsc.edu)

### Methods: 
To estimate Thiamine-DependentFry Mortality (TDFM) in naturally spawning Chinook Salmon, we used a two-step simulation-based approach. First, we developed a dose-response model based on laboratory data linking egg thiamine concentration to fry survival. Next, we applied this model to egg thiamine concentrations measured during hatchery sampling, assuming that these samples represent natural spawning populations in the same watershed. The dose-response model, built within a Bayesian framework using Metropolis Markov Chain Monte Carlo sampling, describes fry survival as a function of egg thiamine concentration. The model was simplified to fit key parameters, including survival limits and thiamine sensitivity (EC50). To estimate TDFM in hatchery or wild populations, thiamine concentrations were randomly resampled 10,000 times, and survival predictions were generated with corresponding uncertainty. All analyses were conducted in R using the RJAGS package, with results reported as survival percentages across multiple brood years.
