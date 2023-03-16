# Freeze-out and Relic Abundance

## Write down the equation that encodes what cosmologists mean by “freeze-out”.
"Freeze-out" is a concept that involves considering departure from LTE, and the formal tool to describe the evolution beyond equilibrium is the Boltzmann equation:

$$
\frac{df_i}{dt} = C_i[f]
$$

Where $f_i$ is the distribution of function of a single particle species, $C_i$ is the collisional term that describes the interactions of such particle species with the other species in its medium, and it is a function of $f_i$ and the distribution function of all the other particle species in the medium $f_j$. Consequently, the Boltzman equation ends up being a system of coupled integro-differential equations that is extremely hard to solve.

In our context, this can be simplified by invoking the homogeneity of the universe at large scales, Hubble drag and integrating over momentum space (taking the zeroth moment), which lands us at:

$$
\frac{dn_i}{dt} + 3Hn_i = \int \frac{d^3\textbf{p}}{(2\pi\hbar)^3}C_i[f]
$$

This can be rewritten in a more physically-intuitive form:

$$
\frac{1}{a^3}\frac{d(n_i a^3)}{dt} = \int \frac{d^3\textbf{p}}{(2\pi\hbar)^3}C_i[f] = C'_i[f]
$$

This lends to an easy interpretation: **in the absence of collisions ($C'_i =0$), the comoving number density $na^3$ is conserved**. Two-body interactions are by far the only type of interactions that matter in an almost empty universe. Thus, let us consider the following reaction:

$$
1 + 2 \leftrightarrow 3 + 4
$$

We can write down the Boltzmann Equation for particle species 1:

$$
\frac{1}{a^3}\frac{d(n_1 a^3)}{dt} = -\alpha(T)n_1n_2 + \beta(T)n_3n_4
$$
Where the RHS describes the destruction and creation rates for particle species 1. We can set the first collisional coefficient equal to:

$$
\alpha(T) = \langle\sigma v\rangle
$$

Where $\sigma$ is the cross-section for the interaction between particle species 1 and 2, $v$ is their relative velocity, and the expected value is to show that it has been properly averaged for a distribution function of velocities. Now, we can invoke *mass action* and *detailed balance* during equilibrium (where the number density at equilibrium is denoted by $n_i^0$) to find a relationship between both collisional coefficients:

$$
\beta = \frac{n_1^0n_2^0}{n_3^0 n_4^0}\langle \sigma v \rangle
$$

This finally allows us to rewrite the Boltzmann equation as:

$$
\frac{1}{a^3}\frac{d(n_1 a^3)}{dt} = - \langle \sigma v \rangle n_1 n_2 \bigg[1 - \bigg(\frac{n_3n_4}{n_1n_2} \bigg/ \frac{n_3^0n_4^0}{n_1^0n_2^0} \bigg)\bigg]
$$

This is the equation that encodes what cosmologists mean by freeze-out. A detailed example of this for can be found in the next question.

## What equation needs to be solved to estimate a relic abundance?
Consider the following reaction for dark matter and leptons:

$$
X+\bar{X} \leftrightarrow l + \bar{l}
$$

Taking particle 1 to be dark matter, and ignoring any matter-antimatter assymetry for dark matter, we can write the simplified Boltzmann Equation as:

$$
\frac{1}{a^3}\frac{d(n_X a^3)}{dt} = - \langle \sigma v \rangle n_X^2 \bigg[1 - \bigg(\frac{n_X^0}{n_X} \bigg)^2\bigg]
$$

We can rewrite this as:

$$
\frac{dN_X}{dln(a)} = -\frac{\Gamma(a)}{H(a)}\bigg[1 - \bigg(\frac{N_X^0}{N_X} \bigg)^2\bigg]
$$

Where we defined the interaction rate $\Gamma = \langle \sigma v \rangle n_X$. If the effective number of degrees of freedom isn't changing, $a \propto T^{-1}$, and we can rewrite this expression and get:

$$
\frac{dN_X}{dln(x)} = -\frac{\Gamma(x)}{H(x)}\bigg[1 - \bigg(\frac{N_X^0}{N_X} \bigg)^2\bigg]
$$

Where $x = m_X c^2/kT$. To estimate the abundance of particle $X$, we need to consider different scenarios:

- $\Gamma \gg H$: Here reactions happen significantly faster than the expansion of the universe. Consequently, we expect the particle species to be close to its equilibrium abundance $N_X^0$.
- $\Gamma \ll H$: Reactions become extremely rare, causing the abundance to "freeze-out".
- $\Gamma \sim H$: This is when departure from equilibrium starts happening.

Furthermore, we need to take into account if $x\ll1$ or $x\gg1$. That is, we need to consider if the particle species decouples when it is relativistic or non-relativistic. An example of this is the WIMP miracle, which is talked about in another question.

## Name three different physical scenarios in the course where we used freeze-out to estimate a relic particle abundance. 
Some examples of freeze-out from the course are:

- Relativistic decoupling to explain why the CMB follows the BB distribution, even though it is clearly not in equilibrium anymore.
- Using non-relativistic decoupling to explain the WIMP miracle.
- Neutron freeze-out to explain the neutron-proton ratio that determines Big Bang Nucleosynthesis.
- Freeze-out of baryons to determine the baryon-photon ratio.