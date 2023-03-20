# Meszaros Effect

## What is the Meszaros Effect?
Up until now, we only considered single-component universes an a mostly Newtonian approach. As you'd expect, a GR treatment of the problem that includes the contribution of multiple energy components complicates the setup. More specfically, the evolution of the density perturbations $\delta_i$ for each i-th energy component depend on the densities of the other components. 

Consider our universe when it was radiation dominated. Since recombination and photon decoupling happened at a later time, during the $\gamma$-dominated universe, baryons and photons were tightly coupled together, making the sound speed close to the speed of light. This means that the Jeans scale $\lambda_J \sim cH^{-1}$ was very large, meaning that most radiation fluctuations oscillated as sound waves. 

Now, let us consider what happens to the CDM density perturbations. Since CDM only interacts gravitationaly and has a pressure $P=0$, the differential equation that describes the evolution of the perturbation greatly simplifies and keeps only the Hubble Drag term, as well as the gravitational term. We can certainly solve this simple ODE, and using the proper relations for a radiation dominated universe, we find that:

$$
\delta_{k,CDM}(t) = \delta_{k,CDM}(t_i)\bigg[1+Aln\bigg(\frac{t}{t_i}\bigg)\bigg]
$$

Which tells us that this perturbations either don't grow, or at most, the grow logarithmically. This is heavily constrasted to the exponential growth for the homogenous-static universe and the power law dependence for the Einstein-De Sitter universe that we found previously. It is this supression of growth of fluctuations on scales inside the photon-baryon fluid sound horizon during the radiation dominated era that is known as the Meszaros Effect.

It is important to note that something similar happens in a $\Lambda$ dominated universe. When we work out the solution in that case, we see that $\delta_{k,CDM}(t) \propto exp(-2H_\Lambda t)$, meaning that there is only a decaying mode and as such, fluctuations in the matter density reach a constant fractional amplitude. 