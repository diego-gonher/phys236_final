# CDM and Hierarchical Cosmology

## For a power law form for the density fluctuation power spectrum, P(k) = Ak^n, how does the variance of the relative mass excess σ(M) depend on length scale k? How do σ(M) and P(k) depend on the linear growth factor D(a)? 
The variance of the excess mass is defined as:

$$
\sigma_M^2(R) = \int_0^\infty \Delta^2(k) W^2(k) d(lnk) 
$$

Using a gaussian flter for $W$, we are left with:

$$
\sigma_M^2(R) \propto \Delta^2(k=R^{-1})
$$

Now, a power spectrum $P(k)=Ak^n$ gives us a dimensionless power spectrum $\Delta^2(k)\propto k^{n+3}$, whcih implies:

$$
\sigma_M^2(R) \propto R^{-(n+3)} \propto M^{-(n+3)/3}
$$

Now, we know that in a matter-dominated universe, the density perturbations grow $\propto a\propto t^{2/3}$, and $\sigma^2\propto \delta^2$. Consequently:

$$
\sigma^2_M(R,t) \propto t^{4/3}R^{-(n+3)/3}
$$

We can solve for $t$ to know when structures collapse:

$$
t_R \propto R^{(n+3)/4}
$$


## Explain why these dependencies imply that the CDM is a ‘bottom-up’ hierarchical cosmology, with the smallest structures collapsing first.
For the CDM model, $n>-3$ for the entirety of the power spectrum, so $t_R$ is a growing function of $R$ and $M$. This is important, because it means that average, smaller scales (radii and masses) be- come nonlinear at earlier times than larger scales. This is what is known as hierarchical structure formation. It states that structure formation occurs from the bottom up, with the smallest structures going non-linear first, which then merge to form larger non-linear structures which collapse later.

In comparison, as we already saw, the power spectrum for HDM and WDM has a cuttoff in their power spectra, meaning that $n>-3$ isn't always satisfied. In their case, larger structures form first.