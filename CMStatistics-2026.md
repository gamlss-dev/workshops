## Flexible Distributional Regression Using the R Package gamlss2

_[Nikolaus Umlauf](https://www.nikum.org/), Universität Innsbruck, Austria_

_[Achim Zeileis](https://www.zeileis.org/), Universität Innsbruck, Austria_

Many scientific questions concern not only how the average response changes
with covariates, but also how the other properties of the response distribution
change, e.g., variability, skewness, tail behavior, quantiles, or exceedance
probabilities. Distributional regression addresses these questions by modeling
the entire conditional response distribution.

This workshop introduces generalized additive models for location, scale, and
shape (GAMLSS) using the R package
[gamlss2](https://gamlss-dev.github.io/gamlss2), a modern and modular
infrastructure for flexible distributional regression. Participants will learn
how to choose suitable response distributions, specify additive predictors for
multiple distributional parameters, incorporate nonlinear effects and
interactions, and interpret covariate effects. Particular emphasis is placed on
a complete modeling workflow: Estimation, distributional diagnostics and
calibration, model comparison, and probabilistic prediction through conditional
quantiles,  prediction intervals and exceedance probabilities. The workshop
also  demonstrates how fitted models can be extended from fast iterative
estimation  to Bayesian inference using MCMC, enabling posterior uncertainty
assessment  within the same modeling framework. Selected examples highlight the
extensibility of gamlss2 through flexible families, alternative estimation 
strategies, and special model terms.

The workshop is designed for participants with basic knowledge of regression
and R, prior experience with GAMLSS is not required.

