# MLEs with errors estimates for truncated power laws
This repository contains codes to fit models on data samples that follow truncated power law functions via Maximum Likelihood Estimation (MLE). Also, error estimates (valid for large number of data points) are derived and code for a Likelihood ratio test (a hypothesis test) is provided to compare the model performances.


## Contents:
- MLE for a pure power law $f(x)\propto x^{-a}$
- MLE for a Schechter function $f(x)\propto x^{-a}e^{-\frac{x}{x_{\mathrm{turn}}}}$
- MLE for a Schechter-like function with stronger than exponential downturn $f(x)\propto x^{-a}e^{-(\frac{x}{x_{\mathrm{turn}}})^{\gamma}}$

For all MLE models, the standard errors are derived as well, using the Hessian matrix to approximate the Fisher Information.
