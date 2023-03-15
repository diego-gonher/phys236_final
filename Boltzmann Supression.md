# Boltzmann Supression

## Explain the the physics behind the idea of “Boltzmann-suppression”
### Distribution function and LTE
Before we can get into it, it is important to note that in order to calculate extensive quantities of for the different energy components in the universe, we need a good estimation of their distribution functions $f$. The most general distributions are functions of the position and momentum vectors of the particles it describes. However, the cosmological principle requires the distribution functions in our case to only depend on the magnitude of the momentum vector. That is:

$$
\textit{Distribution function} = f(p)
$$

Given that $f(p)$ describes the positions of particles in phase space, we can integrate over spatial and momentum coordinates to get the number density:

$$
n = \frac{g}{(2\pi \hbar)^3} \int d^3p f(p)
$$

Where the factor in front of the integral is the degeneracy $g$ over the smallest volume possible given by Planck's constant. In order to apply this, we need a good distribution function that captures the physics of our case. For our purposes, we will consider systems in **Local Thermodynamic Equilibrium** (LTE). We say that two particle species are in LTE if they are either in chemical or kinetic equilibrium, or both. In practice, this means that two particle species share the same temperature $T$. This is important, because it allows us to accuretly describe their distribution functions as:

$$
f(p) = \frac{1}{e^{(E(p)-\mu)/kT} \pm 1}, \textit{+ for fermions, - for bosons}
$$

### Relativistic vs. Non-relativistic and Boltzmann supression
Usually the chemical potential is significantly smaller than the energy of the particles, and thus we can ignore it. The energy itself is given by:

$$
E(p) = \sqrt{m^2c^4 + p^2c^2}
$$

#### Relativistic species
Here $kT \gg mc^2$, meaning $E(p) \approx pc$. Doing the proper integrals leaves us with:

$$
n \propto T^3
$$
$$
\rho \propto T^4
$$
$$
P \propto \rho/3 \propto T^4
$$

Which applies to both bosons and fermions, naturally with different coefficients.

#### Non-Relativistic species
Here $kT \ll mc^2$, meaning:

$$
E(p) \approx mc^2 + \frac{p^2}{2m}
$$

Doing the integrals gives us:

$$
n \propto T^{3/2}e^{-mc^2/kT}
$$
$$
\rho = nmc^2
$$
$$
P = nkT
$$

Since photons are always relativistics, this is mainly for bosons. 

#### Boltzmann-Supression
Finally, from the expressions that we just talked about, we can see that when a species goes from relativistic to non-relativistic, their number density now has an exponential component. This causes the species to decrease exponentially as temperature decreases. This is what is called "Boltzmann Supression".  The main consequence about this supression is that non-relativistic species either 

- Become exponentially rare
- Their number density decreases below the point where interactions are significant. This in turn causes the particle species to go out of equilibrium from the rest of the universe (**decoupling**). In this case, interactions are said to **freeze out**.