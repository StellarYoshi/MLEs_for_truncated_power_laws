# MLEs with error estimates for (truncated) power laws

The slope of power law-distributed data samples, where $f(x)\propto x^a$, is often determined by using histograms. This leads to the so-called binning bias. This bias can be avoided by methods that don't rely on binning such as maximum likelihood estimators (MLEs).

The code makes it possible to fit analytical functions to power law-distributed data that show a high-end downturn, including the cases where the downturn is strong. By modeling this downturn explicitly, it can produce more accurate estimates of the underlying power law slope. 

In an astrophysical context it may be helpful to find analytical approximations for otherwise non-analytical functions with high-end downturns, such as composite IMFs in the IGIMF theory.

## Contents:
- MLE for a pure power law $f(x)\propto x^{-a}$
- MLE for a Schechter function $f(x)\propto x^{-a}e^{-\frac{x}{x_{\mathrm{turn}}}}$
- MLE for a Schechter-like function with stronger than exponential downturn $f(x)\propto x^{-a}e^{-(\frac{x}{x_{\mathrm{turn}}})^{\gamma}}$

For all MLE models, the standard errors are calculated as well.
