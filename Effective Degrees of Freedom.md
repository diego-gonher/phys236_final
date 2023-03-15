# Effective Degrees of Freedom

## How is the effective number of degrees of freedom g⋆(T) defined?
As we saw previously when we were talking about Boltzmann supression, only relativistic particles are able to contribute significantly to the energy density and pressure of the universe. With this in mind, we can see that the energy density of radiation is given by:

$$
\rho_R = \sum \rho_i \propto g_*(T_gamma)T_\gamma^4
$$

Where we've decided to use the temperature of the photons as the temperature of the radiation field (remember we are considering the particle species within the radiation field to be in LTE). Here we have thus defined the effective number of degrees of freedom $g_*(T)$ as follows:

$$
g_\star(T_\gamma) = \sum_{bosons}g_i \bigg( \frac{T_i}{T_\gamma} \bigg)^4 + \frac{7}{8} \sum_{fermions} g_i \bigg( \frac{T_i}{T_\gamma} \bigg)^4
$$

Naturally, as the universe cools down, we'd expect some particle species to become non-relativistic, causing them to no longer contribute to the radiation energy density and changing the effective degrees of freedom.

## How is the effective number of degrees of freedom in entropy g⋆S(T) defined?
As it turns out, thinking about the entropy of the universe tends to be more useful than energy for various reasons. Given the expansion of the universe, the regular concept of entropy as seen in statistical mechanics needs to be modified. This gives rise to the concept of **specific entropy**, which is simply the entropy $S$ per unit volume $V$, but it is also equal to:

$$
s = \frac{S}{V} = \frac{\rho+P}{T}
$$

As we showed in one of the homeworks, $sa^3 = constant$. Now, since there are significantly more photons and only relativistic particles contribute significantly to the overall energy density, we can write down a more explicit expression for the specific entropy:

$$
s_R = \sum s_i = \sum \frac{1}{T_i} \bigg(\rho_i + \frac{\rho_i}{3} \bigg) \propto g_{*S}(T_\gamma)T_\gamma^3 
$$

Where we've done something similar to when we were finding an expression for the energy density. If you look closely, it is the same expression but with one less factor of $T_\gamma$, which comes from the $1/T$ factor for $s$. This also changes our expression for the effective numbers of freedom (which now are referred to as the effective number of dof in entropy):

$$
g_{\star S}(T_\gamma) = \sum_{bosons}g_i\bigg(\frac{T_i}{T_\gamma}\bigg)^3 + \frac{7}{8} \sum_{fermions}g_i\bigg(\frac{T_i}{T_\gamma}\bigg)^3
$$

## Why are these definitions useful? How are these two quantities different?
### Usefulness of g*(T)
From its definition, the main usefulness of the effective number of degrees of freedom is that it allows us to calculate macroscopic quantities such as number density, energy density and pressure for the thermal bath as a function of only the photon bath temperature. 

### Usefulness of g* S(T)
#### Temperature of photon bath
Since $g_{*S}(T)$ is related to $s$ and $sa^3$ is our entropy conservation law, the effective number of degrees of freedom of entropy has a few important applications. First, we can see the dependence of temperature as a function of redshift and $g_{\star S}(T_\gamma)$:

$$
sa^3 \propto g_{\star S}(T_\gamma)T\gamma^3a^3 = \textit{constant}
$$
$$
\implies T_\gamma \propto g_{\star S}(T_\gamma)^{-1/3}(1+z)
$$

This is important because when particle species become non-relativistic, they dump their entropy to the thermal bath and also decrease the value of $g_{\star S}(T_\gamma)$, which causes the photon temperature to decrease at a slower pace. This is called **heating**.

#### Number of particles per unit total entropy
Calculating the evolution of the number density $n$ of photons and other components of the thermal radiation field is not correctly done with a naive approach. This is because, as we just saw, the temperature of the photon bath is not a simple function of redshift because the effective number of dof of entropy changes as the thermal history unfolds. However, we can define the number of particles per unit total entropy as:

$$
N_i = \frac{n_i}{s}
$$

If the particles are not created nor destroyed, then $N_i$ is constant and independent of redshift, because both $n_i$ and and $s$ scale with $a^{-3}$. 

### Number density of relativistic relics
Another consequence that can be derived is that the number denisity of relativistic (hot) relics (that is, particle species that decoupled for the thermal bath when they were still relativistic, such as neutrinos) have a number density that is comparable to that of the photons, **even if they go non-relativistic after decoupling**.


## When in the universe’s thermal history does g(T) = gS(T)? When does g(T) != gS(T)?
$g_{\star}(T_\gamma)$ and $g_{\star S}(T_\gamma)$ are the same before neutrino decoupling, which happens at around $1 \texttt{ MeV}$, and become different after neutrinos decouple and when positron-electron anhilitaion takes place 