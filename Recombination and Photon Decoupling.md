# Recombination and Photon Decoupling

## Briefly explain the baryon to photon ratio.
The baryon to photon ratio $\eta$ is a quantity that plays an important role in recombination, and thus we need to get a decent intuition about it. The first thing to consider is that $\eta$ is not necessarily a constant throughout the universe's evolution. However, after electron-positron anhillation ($T\sim0.5MeV$), $\eta$ has remained the same, and thus can be calculated by using equations from thermal history and relate it to today's density parameters for both matter and radiation. Carrying out the proper calculations, we end with:

$$
\eta = \frac{n_B}{n_\gamma} \approx 5.5 \times 10^{-10}\bigg( \frac{\Omega_{B,0}h^2}{0.020}\bigg)
$$

This is remarkable; it means that there are waaaaay more photons than baryons in the universe, and that has been the case since very early in the universe. 

## At what redshift did recombination take place? What was the temperature of the universe then, and how did the characteristic energy kT compare with the ionization potential of hydrogen, BH = 13.6eV.  Why is the characteristic energy kT significantly lower than BH? 
Naively, we would expect to get a good approximation of $z_{rec}$ by finding the time at which the thermal bath had a temperature $\sim 13.6 eV$, which is the binding energy of the Hydrogen atom. Using our known relations:

$$
T_{rec} = T_{CMB,0}(1+z_{rec}) \implies z_{rec} \sim \frac{T_{rec}}{T_{CMB,0}}-1 \approx 20,000
$$

However, this is wrong, as measurements suggest that $z_{rec} \sim 3500$. Why is this? Well, in our naive calculation, we assumed an average temperature for the thermal bath, and set that equal to a $kT = B_H$. Howver, as we know, the photons in the thermal bath have a distribution function $f{p}$, which in turn means that individual photon temperatures have a distribution. It is true that photons that are energetic enough to ionize a Hydrogen atom become rarer and rarer as the universe evolves. **But, as we just saw, there are around $10^{10}$ photons per each baryon in the universe, which means that even if ionizing photons become rare within the photon distribution function, a lot of time needs to pass for ionizing photons to actually be too rare to ionize neutral H.** Mathematically speaking, this is explained by the Saha Equation:

$$
\frac{1-X_e}{X_e} \approx \frac{2\zeta(3)}{\pi^2}\eta\bigg(\frac{2\pi k T}{m_ec^2} \bigg)^{3/2}e^{-B_H/(kT)}
$$

Where $X_e$ is the **free electron fraction**, and the $\approx$ comes from the fact that we approximate all baryons to only be H atoms. As we can see, the H binding energy still plays a role, but now $\eta$ is also taken into account. We can finally use the expression above to calculate a *characteristic temperature* for recombination, by choosing a proper $X_e$ and numerically solving the above expression for $T$. Choosing $X_e = 0.1$, we get a $T_{rec} = 3600K$ ($kT_{rec}=0.3eV$), and we obtain a better $z_{rec}$:

$$
z_{rec} = \frac{T_{rec}}{T_{CMB,0}}-1 \approx 1320
$$


## What is the difference between recombination and photon decoupling?
By definition, recombination is the epoch in which the universe's thermal bath became cool enough to allow for neutral Hydrogen to be formed. Since photons are most strongly coupled to the primordial plasma through their scattering interactions with electrons, once free electrons become too rare (because of recombination), they decoupled and produced the surface of last scattering. As we've explored in "thermal history", we can get an estimate of the redshift of decoupling $z_{dec}$ by comparing the rate of reactions and the Hubble expansions:

$$
\frac{\Gamma}{H} \sim 1
$$

Using $\Gamma \sim \sigma_T X_e n_B c$ and a considering an Einstein-de Sitter universe (a good approximation at these redshifts) to obtain a simple expression for the Hubble expansion in terms of redshift and solving for such redshift, we obtain:

$$
z_{dec} \approx 1090
$$
