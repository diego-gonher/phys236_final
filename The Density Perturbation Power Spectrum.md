# The Density Perturbation Power Spectrum

## Sketch the density perturbation power spectrum P(k) vs. k, and explain the reason for the asymptotic slopes at the low-k and high-k ends.  
To understand the shape of the density perturbation power spectrum we can start by considering the behavior of the *potential perturbations* as the universe transitions from radiation dominated to matter dominated. We previously explained that the only modes that don't have a constant potential perturbation throughout their entire evolution are those within the sub-horizon during the radiation-dominated era (Meszaros effect). That is:

$$
\delta\vec{\Phi}(\vec{k},t) = \delta\vec{\Phi}(\vec{k}, t_i) [a(t)/a(t_i)]^2\textit{ for sub-horizon and radiation-dominated}
$$
$$
\delta\vec{\Phi}(\vec{k},t) = \delta\vec{\Phi}(\vec{k}, t_i)\textit{ for the rest of cases}
$$

Now, this is clearly going to affect the potential perturbation power spectrum. To get more specific, consider times between recomnination and matter-radiation equality. As we have already explored, modes that are initially larger than the particle horizon will eventually become sub-horizon because their $\lambda_{proper}$ doesn't grow as fast as the proper particle horizon. This means that there'll be a number of k-modes that'll will enter the case where their growth is supressed by the Meszaros Effect, and it'll affect them until matter-radiation equality which is when they'll stop being supressed. This means that we can define a k-mode to the matter-radiation equality:

$$
k_{eq} = 2\pi/d_{eq} = 0.06 Mpc^{-1}
$$

Which is the last k-mode to be supressed. Bringing back our reasoning from earlier, this means that:

$$
\delta\vec{\Phi}(\vec{k},t) = \delta\vec{\Phi}(\vec{k}, t_i) \textit{ for } k<k_{eq}
$$
$$
\delta\vec{\Phi}(\vec{k},t) = \delta\vec{\Phi}(\vec{k}, t_i) \bigg(\frac{a_{enter}(k)}{a_{eq}}\bigg)^2\textit{ for } k>k_{eq}
$$

Using all our scaling relationships for the radiation-dominated era, we are able to derive that:

$$
\bigg(\frac{a_{enter}(k)}{a_{eq}}\bigg)^2 = \bigg(\frac{k_{eq}}{k}\bigg)^2
$$

Using the two point correlation function for these gravitational potential perturbations, we find that their power spectrum is given by:

$$
P_{\Phi}(k,t) = P_{\Phi}(k,t_i) \textit{ for } k<k_{eq}
$$
$$
P_{\Phi}(k,t) = P_{\Phi}(k,t_i)(k_{eq}/k)^4 \textit{ for } k>k_{eq}
$$

Now, to relate this to the density perturbation power spectrum, we make use of the perturbed Poisson Equation which tells us that $P_\delta\propto k^4P_\Phi(k) \implies P_\delta(k,t_i) = Ak$. Therefore, we finally obtain the power spectrum for the density perturbations:

$$
P_{\delta}(k,t) = Ak \textit{ for } k<k_{eq}
$$
$$
P_{\delta}(k,t) = Ak(k_{eq}/k)^4 \propto k^{-3} \textit{ for } k>k_{eq}
$$

Giving us the asymptotic slopes at 

## What characteristic length scale does the peak in the power spectrum P(k) correspond to?

It corresponds to the smallest k-mode (largest Jeans scale) that has a supressed growth,  which as we mentioned, is related to the matter-radiation equality. Doing the numerical evaluation gives us:

$$
k_{eq} = 0.06 Mpc^{-1}
$$

