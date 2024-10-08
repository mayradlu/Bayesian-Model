# Bayesian Model for Predicting Alligator Population Dynamics
## General Information
In 1967, the American alligator was listed as a threatened species due to threats to its habitat and survival. However, thanks to conservation efforts, by 1987 its population had increased significantly and it was reclassified as non-threatened. This success highlights the importance of understanding population dynamics.
<p align="center">
  <img src="https://github.com/user-attachments/assets/3c818a6b-1016-49df-935f-14b6bb20403e" alt="imagen" width="400">
</p>


This project uses a Bayesian model combined with a logistic growth model and differential equations to analyze and predict the population dynamics of alligators over 20 years in R. The model assumes that the population follows a normal distribution, with a mean determined by a logistic model and a constant variance. A non-linear regression approach and Markov chains are used to approximate the population dynamics.

## Theoretical Framework
**Bayesian Models**: Bayesian models are based on Bayes' Theorem, which combines prior information and observed data to estimate probabilities.

**Bayesian Estimator**: The Bayesian estimator minimizes the expected value of a loss function. Common estimators are

* Quadratic losss
* Absolute error
* Zero-one loss

**Markov Chain Monte Carlo**: When the posterior distribution is difficult to estimate directly, Monte Carlo methods are used to approximate it through simulations.MCM generates samples from the posterior distribution through a Markov chain that converges to it. Common techniques are

* Gibbs Sampler: Updates parameters from conditional distributions.
* Metropolis-Hastings: Provides proposals and accepts or rejects them based on an acceptance rate.

## Results
<p align="center">
  <img src="https://github.com/user-attachments/assets/311b6cf5-ed49-4fdb-81b8-68c6aaaba3e5" alt="imagen" width="400">
</p>

The Bayesian model applied to the population growth of alligators, utilizing a normal distribution with a mean governed by a logistic growth model and constant variance, demonstrates excellent performance. This model fits the data used in the report with remarkable precision and allows for a surprisingly accurate description and modeling of the alligator population from a Bayesian perspective.

## R
R version 4.0 or higher

RStan package for Bayesian inference (rjags)

