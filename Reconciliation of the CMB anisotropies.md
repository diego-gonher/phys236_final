# Reconciliation of the CMB anisotropies

## Explain why dark matter is required to reconcile the level of anisotropy in the CMB temperature ∆T/T ∼ 10−5 with the highly non-linear structures that are observed today, or specifically that σ(R = 8 h−1 Mpc) ≃ 1.

We can work a similar solution for the evolution of the perturbations as we did for a static and homogenous universe, but now considering an expanding universe. The main ideas are very similar, but we need to introduce an expanding metric. Carrying out the math, one arrives at a similar expression for the time evolution of the density perturbations $\delta\rho = \delta$:

$$
\ddot{\delta} + 2H\dot{\delta} = 4\pi G \rho\delta + \frac{c_s^2}{a^2}\nabla^2\delta
$$

Where the RHS is still the same (gravity vs. pressure), but now the LHS has a second term which a reflection of the Hubble Drag that is acting as a friction term opposing the acceleration of a gravitational instability. 

We can find actual solutions for an Einstein-De Sitter universe (matter-only universe), which is useful for many reasons. We again do the trick of obtaining ordinary differential equations for each independent Fourier mode. We again have a definition for the Jeans scale:

$$
\lambda_J = \frac{2\pi a}{k_J}
$$

Considering that in a matter-dominated unviverse:

$$
a\propto t^{2/3} \implies H = \frac{2}{3t} \implies \rho_0(t) = \frac{1}{6\pi G t^2}
$$

We again find that:

$$
\lambda_J \sim c_s t
$$

Where now $t$ is the expansion time. This means that the Jeans length is comparable to the "sound horizon", which is the proper distance that a sound wave can travel over the age of the universe. If we keep hammering the ODEs, we finally get that the general solution for the perturbations in k space is:

$$
\delta_k = D_1t^{2/3} + D_2 t^{-1}
$$

As time passes, the second term vanishes, showing us that in a matter-dominated universe, density perturbations grow at a rate of:

$$
\delta_k \propto t^{2/3} \propto a \propto (1+z)^{-1}
$$

Hence, we see that in an expanding universe, gravitational instability is much less efficient. Whereas in the static universe fluctuations grow exponentially on the gravitational free-fall timescale, we see here that instead the perturbation amplitude increases only as a power of time. 

### Comparison to the CMB anisotropy level
Measurements show that the fluctuations in the CMB are:

$$
\frac{\Delta T}{T} \sim 10^{-5}
$$

Since $\rho_r \propto T^4$, this implies that $\delta_r \sim 10^{-5}$. Assuming that the fluctuations in the baryons must be comparable to those in the radiation bath given that these were tightly coupled via Thomson scattering before recombination and decoupling, then this implies that $\delta_b(t_{dec})\sim 10^{-5}$. Since the universe became $\Lambda$ dominated until only very recently, then we would expect this to be a good approximation of the baryon perturbations in our current universe. In fact, we would expect fluctuations larger than the Jeans scale to grow proportional to the scale factor and:

$$
\delta_b(t_0) \sim \frac{a_0}{a_{dec}}\delta_b(t_{dec}) = (1+z_{dec})\delta_b(t_{dec}) \sim 10^{-2}
$$

This clearly doesn't match our observations, as the baryion structures in the current universe are highly non-linear. Comparing thsi to $\sigma_8 \sim 1$, we are off by two orders of magnitude. So, what are we missing? Two things:

- There are other particle species that contribute to gravitational instabilities. Namely, dark matter, whcih doesn't interact with the rest of particles besides gravitationaly, is going to affect structure formation dramatically. This is actually a really strong piece of evidence in favor of the existance of dark matter.
- A bit less direct, but clearly important, is that including more energy components to our calculations and considering eras with different components dominating is going to change the rate at which perturbations evolve. As we saw, a homogenous and static universe had perturbations growing exponentially, while a matter-dominated expanding universe had a power law describing the growth of the perturbations.