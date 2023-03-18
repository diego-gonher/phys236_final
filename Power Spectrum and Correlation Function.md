# Power Spectrum and Correlation Function

## How is the correlation function ξ(r) defined?
Consider a random field $\delta(x)$ defined as:

$$
\delta(x) = \frac{\rho-\bar{\rho}}{\bar{\rho}}
$$

Which is basically a stochastic variable with zero mean that describes the overdensities and underdensities from a probability function $P$. With this setup, correlators of fields are simply expectation values of products of fields at different spatial locations (and times, more generally). Given the cosmological principle, one can see that a "one point correlator" is given by:

$$
\langle \delta(x) \rangle = 0
$$

Furthermore, we can see that the second moment of $P$ is given by a "two-point correlator" evaluated at the same position $x$:

$$
\langle \delta^2(x) \rangle = 0
$$

And it must be independent of the position $x$. Finally, we come to the **two-point correlation function**:

$$
\xi(x) = \langle\delta(\textbf{x}_1)\delta(\textbf{x}_2)\rangle, \textit{ with } x = |\textbf{x}_1 - \textbf{x}_2|
$$

Where again, the last part comes from invoking the cosmological principle.

## How is the power spectrum P(k) defined?
We will often find it useful to decompose the density perturbation into its constituend Fourier modes. Taking into account that $\delta(\textbf{x})$ is a real quantity (which puts constrains in $\delta(\textbf{k})$ and using our results for defining the correlation function in real space applying the cosmological principle, we can find an expression for the two-point correlator in k space:

$$
\langle\delta(\textbf{k})\delta^*(\textbf{k}')\rangle = (2\pi)^3\delta_D(\textbf{k}-\textbf{k}')P(k)
$$

Where $\delta_D$ is the Delta-Dirac function, and $P(k)$ is the power spectrum, defined as and simplified as:

$$
P(k) = \int_0^{\infty} \xi(x) \frac{sin(kx)}{kx}4\pi x^2 dx
$$

## What do they mean qualitatively and what is the relationship between them?
From the definition of the power spectrum:

$$
P(k) = \int_0^{\infty} \xi(x) \frac{sin(kx)}{kx}4\pi x^2 dx
$$

We can see that $P(k)$ is the Fourier transform of the correlation function $\xi(x)$. Consequently, we can also do a Fourier transform to go from $P(k)$ to the correlation function:

$$
\xi(x) = \frac{1}{2\pi^2}\int_0^{\infty} P(k) \frac{sin(kx)}{kx} k^2 dk
$$

As mentioned earlier, this means that we can find the variance of the field by evaluating the correlation function at "zero lag":

$$
\sigma^2 = \xi(x=0) = \frac{1}{2\pi^2}\int_0^{\infty} P(k) k^2 dk
$$

Now, the physical interpretation is that the two-point correlation function gives the approximate number of overdensities (or underdensities) within a distance $x$ from any position in your random field. Say we are talking about a smoothed random field given by the distribution of galaxies. Then, the two-point correlation function gives you the number of galaxies that you'd find on average within a specified distance of an arbitrary position within the universe. 

With this in mind and given that the power spectrum is the Fourier transform of the two-point correlation function (*The Fourier Transform equation is essentially a measurement of the energy (i.e. strength of prevalence) of a particular frequency within a signal. In practice, we can use this notion to sweep over a range of frequencies, and quantify how dominant each particular frequency is within the original signal*), then the power spectrum is the intensity of density fluctuations as a function of scale. Following our example, the power spectrum gives us a sense of how the two-point correlation function changes with different scales (distances).