# Growth factor D of density fluctuations

## How does the growth factor D of density fluctuations depend on the scale factor a(t) in the following 4 cases: superhorizon and (i) matter-dominated (ii) radiation dominated; sub-horizon and (iii) matter-dominated (iv) radiation-dominated (assume a flat universe). 
In general, when we find a solution for $\delta_{k,i}(t)$, we write the growing mode solution as:

$$
\delta_{i}(t) \propto D(a)
$$

Where $D(a)$ is the linear growth function and needs to be solved numerically. Now, before we can dive into it, we need a quick review on horizons.

### Horizons
From our study on the dynamics of an expanding universe, we found that:

$$
\rho(a) \propto a^{-3(1+w)}
$$

$$
H^2=H_0 a^{(1+3w)/2}
$$

$$
a(t) \propto t^{\frac{2}{3(1+w)}}
$$

Using this, we can find how the proper particle horizon scales with $a$:

$$
r_{ph} = \frac{(1+w)3ct}{1+3w}
$$

This means that for a radiation-dominated and a matter-dominated universe, we respectively get:

$$
r_{ph} = 2ct\textit{, radiation-dominated}
$$
$$
r_{ph} = 3ct\textit{, matter-dominated}
$$

If we now consider a perturbation of proper size $\lambda_{prop}=a(t)\lambda$, we get that 

$$
\lambda_{prop} \propto t^{1/2}\lambda\textit{, radiation-dominated}
$$
$$
\lambda_{prop} \propto t^{2/3}\lambda\textit{, radiation-dominated}
$$

Meaning that the proper particle horizon will always grow faster than the proper size of the perturbations. This means that modes that are initially outside of the horizon eventually fall into the horizon, and those initially inside of the horizon never get out. To have a better understanding on the evolution of these different modes, we need to study how sub-horizon and super-horizon perturbations behave both in radiation-dominated and matter-dominated universes.

### Sub-Horizon perturbations
Focusing only on dark matter (allowing us to ignore free-streaming), we already studied how their density perturbations depend on $a$. Recall that in a radiation-dominated universe, perturbations could grow at most logarithmically, while in a matter-dominated universe they can grow linearly (Meszaros Effect):

$$
\delta_c(\vec{k}, t)\propto \delta_c(\vec{k}, t_i)ln[a(t)/a_i]  \textit{, radiation-dominated}
$$
$$
\delta_c(\vec{k}, t)\propto \delta_c(\vec{k}, t_i)(a(t)/a_i)  \textit{, matter-dominated}
$$

One can also explore how the perturbations in the gravitational potential $\Phi$ evolve, but that is left for another question in these review notes.

### Super-Horizon perturbations
The actual derivation for this requires a full GR treatment, but in terms of herusitics, it makes sense to say that a mode that is larger the particle horizon doesn't "know" it is a perturbation, because it is larger than the boundary of its causal knowledge. Essentially, it is an island universe that evolves independently of the regions it isn't causally connected to. From GR, one gets that the graviational potential perturbations in this case are constant in time $\delta \Phi(k,t) = \delta\Phi(k)$. We can then use the perturbed Poisson Equation to find that:

$$
-k^2\delta\vec{\Phi}(\vec{k}) = 4\pi G a^2 \rho_0(t)\delta(\vec{k},t) \implies \delta(\vec{k},t) = \frac{constant}{\rho_0(t)a^2}
$$

Using the proper scalings for the energy density, one finds that

$$
\delta_c(\vec{k}, t)\propto \delta_c(\vec{k}, t_i)(a(t)/a_i)^2  \textit{, radiation-dominated}
$$
$$
\delta_c(\vec{k}, t)\propto \delta_c(\vec{k}, t_i)(a(t)/a_i)  \textit{, matter-dominated}
$$


## For sub-horizon perturbations, provide a brief physical argument for why the radiation-dominated case is either faster or slower than the matter-dominated case.

This is the Mezsaros effect and its physical intuition, which can be found on a different question in these review notes, tells us that the modes that are smaller than the proper particle horizon have a stunted growth during the radiation dominated era, and its potential will decay, something found in the following question. That is not the case for these sub-horizon modes during the matter-dominated era, since then they grow linearly.

