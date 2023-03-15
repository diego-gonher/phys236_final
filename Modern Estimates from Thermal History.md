# Modern Estimates from Thermal History

## What are modern estimates for the CMB temperature Tγ today?
Modern estimate for the CMB temperature today is:

$$
T_{CMB,0} = T_{\gamma,0} = 2.73 K
$$

## What are modern estimates for Ωm, ΩΛ, h?
The current best estimates for the denisity parameters are:

$$
\Omega_{m,0} \approx 0.3
$$
$$
\Omega_{\Lambda, 0} \approx 0.7
$$
For completion:
$$
\Omega_{\gamma, 0} \approx 8.7\times10^{-5}
$$

Now, the ignorance parameter $h$ is useful when calculating the Hubble constant:

$$
H_0 = 100 h \hspace{0.2cm} km \hspace{0.07cm} s^{-1} \hspace{0.07cm} Mpc^{-1}
$$

Which means the best estimate for $h$ is:

$$
h = 0.7
$$

## Estimate the redshift zeq of matter radiation equality, derive it, don’t just state it. You can ignore the contribution from neutrinos in this estimate. How would including neutrinos modify this calculation?
### Without neutrinos
We need to calculate the time in which the energy densities for both radiation and matter were equal. For that, we can use their denisity parameters and our knowledge on how they scale as the universe expands:

$$
\Omega_{m} = \Omega_{\gamma}
$$
$$
\Omega_{m,0}a^{-3} = \Omega_{\gamma,0}a^{-4}
$$
$$
\implies a^{-1} = 1 + z_{eq} = \frac{\Omega_{m,0}}{\Omega_{\gamma,0}}
$$
$$
\implies z_{eq} \approx 3570
$$
### With neutrinos
Taking into account neutrinos means that the energy density of radiation is greater at earlier times, since their contribution to the energy density increases with redshift. The main thing to consider is the ratio of energy densitites between photons and neutrinos, which is given by:

$$
\frac{\rho_\nu}{\rho_\gamma} = g_\nu \bigg( \frac{7}{8} \bigg) \bigg( \frac{T_\nu}{T_\gamma} \bigg)^4 = \frac{21}{8}  \bigg( \frac{4}{11} \bigg)^{4/3} \approx 0.68
$$

Which means that the radiation density parameter is boosted by $68$%. That means:

$$
1+z_{eq} = \frac{\Omega_{m,0}}{1.68\Omega_{\gamma,0}}
$$
$$
\implies z_{eq} \approx 3710
$$


