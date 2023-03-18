# Gaussian and Non-Gaussian random fields

## What is a Gaussian random field? How would this differ from a non-Gaussian random field? 
A Gaussian random field is a random field $\delta(x)$ where the distribution of the field values at an arbitrary set of n points ($\delta(x)_1$, $\delta(x)_2$, ..., $\delta(x)_n$), which we describe with an n-dimensional row vector, is an n-dimensional multivariate Gaussian distribution. A non-Gaussian random field doesn't follow such distribution. There are some advantages to using Gaussian random fields:

- Any linear combination of Gaussian distributions is also a Gaussian distribution.
- The two-point correlation function in k-space is diagonal, a consequence of the comsological principle and x being real-valued.
- Different Fourier modes are independent, and thus the phases of different modes are mutually independent, allowing us to to treak $\delta(\textbf{k}$) for each $k$ mode as uncorrelated draws from independent random processes.
- Defining a two-point correlation function, or alternetively, a power spectrum, is all we need. This is because by construction, the first moment (mean) is equal to zero (causing all odd-numbered correlators to vanish) and all even-correlators can be expressed as in terms of the two-point correlation function. This allows us to specify a distribution function, which requires knowledge on all moments.
- It is much easier to work in k-space, which is the fact that in the linear regime, the principle of superposition implies that the Fourier modes evolve indpenendently from each other.
- Inflation predicts Gaussian initial fluctuations.

## Provide a cosmological example from the course of a Gaussian random field and a non-Gaussian random field.
The distribution of primordial density fluctuations at early times (in the linear growth regime) is a Gaussian random field, while the distribution of dark matter density at later times (in the nonlinear growth regime) isn't.