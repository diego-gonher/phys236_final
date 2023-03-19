# Jeans Scale

## Describe the physical significance of the Jeans scale λJ 
Consider a homogenous isotropic background density of matter with a time independent density $\rho_0(r,t)$ The evolution equations for a perfect fluid are the continuity equation (conservation of mass-energy), Euler equation (conservation of momentum), and the Poisson Equation (gravity). These expressions amount to 5 different differential equations with 6 unkowns. As we did when we were dealing with the FRW metric, we need to establish an equation of state $P = P(\rho, S)$. We thus consider perturbations for the solution of the form:

$$
y(\vec{r}, t) = y_0 + \delta y(\vec{r},t)
$$

For all of our unkowns. Using our equation of state, we can write the perturbation for pressure $\delta P$ as:

$$
\delta P = \bigg(\frac{dP}{d\rho}\bigg)_S \delta \rho = c_s^2\delta\rho
$$

Where $c_s$ is the sound speed. 

Now, as a side note, the way these equations are constructed have a major flaw, known as *Jeans swindle*. Basically, the requirement of a time-independent and constant density would require the flux of gravitational potential to be equal to zero, which in turn would mean that the fluid is actually not there (given Poisson's equation). This means that there can be no homogenous self-gravitating fluid in equilibrium. Regardless, assuming that it does exist and carrying out the calculations is important as it gives us some physical insight to the entire process of linear structure formation.

Moving on, if we introduce our perturbations into our evolution equations and keep only the linear terms, we end up with a simple set of fluid equations, which we can then massage. to give us a final result:

$$
\frac{d^2\delta\rho}{dt^2} = 4\pi G\rho_0\delta\rho + c_s^2\nabla^2\delta\rho
$$

Which is a closed linear wave equation, and where we can see that the evolution of the density perturbation is a competition between gravity (first term) and pressure (second term). Since the coefficients in this equation are constant, we can express the density perturbation in terms of its Fourier transform leaving us with a set of ordinary differential equations for the time-independent Fourier coefficients. This leaves us with two independent solutions:

$$
\delta\rho(\vec{k}, t) \propto e^{\pm i\omega(k)t}, \hspace{0.3cm} k = |\vec{k}|
$$

Where:

$$
\omega(k) = \sqrt{k^2c_s^2 - 4\pi G\rho_0}
$$

As it turns out, the behavrior of these isentropic perturbations depends a lot on the sign of the expression for  $\omega(k)$. Thus, we define the Jeans length $\lambda_J$ as the wavelength of for the k wavenumber that gives $\omega(k_J)=0$:

$$
\lambda_J = \frac{2\pi}{k_J} = c_s\bigg(\frac{\pi}{G\rho_0}\bigg)^{1/2}
$$

Intuitively, what the Jeans scale give us is the distance which sound waves can travel in a gravitation free-fall time $t_{grav} \sim (G\rho)^{-1/2}$. In fact, we can say that:

$$
\lambda_J \sim c_s t_{grav}
$$

Consequently, it characterizes the maximum distance over which sound waves can communicate, allowing pressure to properly counteract any gravitational collapse. In summary, when $\lambda < \lambda_J$, pressure has enough time to prevent gravitational collapse and gives rise to acoustic oscillations, but when $\lambda > \lambda_J$, pressure cannot react quickly enough and the mode is unstable to collapse.

