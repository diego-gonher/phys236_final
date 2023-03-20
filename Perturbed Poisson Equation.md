# Perturbed Poisson Equation

## The equation
In a flat, expanding universe, the perturbed Poisson Equation is written as:

$$
\nabla^2\delta\vec{\Phi} = 4\pi G a^2 \rho_0 \delta
$$

Taking the Fourier transform for the gravitational potential, in k-space we have:

$$
-k^2\delta\vec{\Phi}(\vec{k},t) = 4\pi G a^2 \rho_0 \delta(\vec{k},t) 
$$

## Show that in a flat matter dominated universe, linear potential fluctuations are time-independent.
We again need to consider sub-horizon and super-horizon density perturbations and see what this means for the potential perturbations:

### Super-Horizon
As explained before, a full description of this scenario requires GR, which was outside of the scope of this course. Doing the proper GR derivation, one finds that the gravitational potential perturbations are time-independent $\delta\vec{\Phi} = constant$.

### Sub-Horizon
Here, we can use the perturbed Poisson equation from above alongside our knowledge about how density perturbations grow in a matter-dominated universe. Recall that in that case $\delta\propto a(t)/a_i$. Thus:

$$
\delta\vec{\Phi} \propto a^2 \rho_0(a)\delta \propto a^2 \hspace{0.1cm} a^{-3} \hspace{0.1cm} a = constant
$$

That is, the gravitational potential perturbations are time-independent for a matter-dominated universe.

### Radiation-dominated
So far, we know that in a matter-dominated universe $\delta\vec{\Phi}$ is constant, and we also know from GR that that is also the case for super-horizon perturbations in a radiation-dominated universe. For completion, we can use the perturbed Poisson equation to see what happens to sub-horizon perturbations in the radiation era. Recall that in this case $\delta\propto ln(a/a_i) \sim constant$ where the last part we are saying that this is a very small growth rate. Plugging this into our perturbed Poisson Equation:

$$
\delta\vec{\Phi} \propto a^2 \hspace{0.1cm} a^{-4} \hspace{0.1cm} a^{0} = a^{-2}
$$

Which is an interesting result, as it shows that the only case in which gravitation potential perturbations aren't constant, and actually decaying, are those related to sub-horizon perturbations in the radiation-era. 