# FRW Metric and Distances 

### Ignoring angular terms, write down the FRW metric.
It has been shown that to satisfy the Cosmological Principle, a metric that describes the universe must have the following form, in spherical polar coordinates:

$$
ds^2 = -c^2dt^2 + a^2(t) \big[dr^2 + S_k^2(r)\big( d\theta^2 + sin^2\theta d\phi^2 \big) \big]
$$

Given that the universe is flat, $S_k(r) = r$, and, ignoring angular terms, we are left with:

$$
ds^2 = -c^2dt^2 + a^2(t)dr^2
$$

### Hence express the line-of-sight comoving distance d_c as an function of a) time, b) redshift.
The first distance we must define is the **proper distance** $r_p$, which is the space-like distance:

$$
ds^2 = a^2(t)dr^2 \implies ds = a(t)dr
$$
Here, the proper distance $r_p$ is then the integral of the radial comoving coordinate $r$:

$$
r_p(t) = \int_0^r a(t)dr' = a(t)r
$$
The line-of-sight comoving distance $d_c$ is the distance along the null-geodesic. That is, it is the distance a photon has traveled between two points as measured by the photon itself. From the metric:

$$
0 = -c^2dt^2 + a^2(t)dr^2 \implies dr = \frac{cdt}{a(t)}
$$

Integrating both sides, we get $d_c$:

$$
d_c = \int_{t_e}^{t_o} \frac{cdt}{a(t)}
$$

We can rewrite this in terms of redshift using the chain rule and $a = (1+z)^{-1}$:

$$
d_c = \int_0^z \frac{cdz}{H(z)}
$$

Where:

$$
H(z)^2 = \bigg(\frac{\dot{a}}{a}\bigg)^2 = H_0^2[\Omega_{m,0} (1+z)^{3} + \Omega_{r,0}(1+z)^4 + \Omega_{\Lambda} + \Omega_{k,0} (1+z)^2]^2
$$

And:

$$
H_0 = 70 \bigg( \frac{h}{0.70} \bigg) \hspace{0.25cm} km \hspace{0.15cm} s^{-1} \hspace{0.15cm} Mpc^{-1}
$$

### Provide definitions for i) angular diameter distance, ii) luminosity distance (you don’t have to derive them, just explain what they are), and explain why they are sensitive to cosmological parameters.

#### Angular Diameter Distance
For an object of length $l$, the angular distance $d_A$ is defined as:

$$
d_A = \frac{l}{d\theta}
$$
Using the FRW metric, setting $dt= 0$ and $ds = l$, and keeping $r$ and $d\phi$ constant, we can rewrite this as:

$$
d_A = \frac{a(t_e) S_k(r) d\theta}{d\theta} = \frac{S_k(r)}{1+z}
$$

#### Luminosity Distance
In a static, Euclidean space, you could find a luminosity distance $d_L$ intuitively with:

$$
d_L = \bigg(\frac{L}{4\pi f}\bigg)^{1/2}
$$
Where $f$ is the flux. For a Euclidean, static space:

$$
f = \frac{L}{4\pi d^2}
$$

But in an expanding, not-necessarily-flat universe, we have to consider three corrections according to the FRW metric:

- Proper Area, given by the FRW metric
- Cosmological redshift
- Time dilation

Which, put together, give a corrected $f$:

$$
f = \frac{L}{4\pi S_k^2(d) (1+z)^2}
$$

And therefore, the luminosity distance is given by:

$$
d_L = S_k(d)(1+z) = (1+z)^2 d_A
$$

#### Sensitivity to cosmological parameters
As we can see, these distances depend on $S_k(r)$, which depends on the geometry of the universe. Their dependence on $z$ is affected by the energy budget within the universe, as seen in **Fig3** and **Fig5** of **lecture4_distance.pdf**. Moreover, for a flat universe, one can use these distances to make actual measurements. Though there isn't a good "angular ruler", there are a few standard candels, such as certain types of supernovae that can be used in the local universe alongside the luminosity distance and make inferences for some cosmological paremeters.

### How are they related to the comoving distance in a flat universe?
#### Angular Diameter Distance
Recall that:

$$
d_A = \frac{S_k(r)}{1+z}
$$

For a $k=0$ flat universe, $S_k(r) = r$, and thus:

$$
d_A = \frac{r_e}{1+z} = \frac{d_c(z)}{1+z} 
$$
That is, for a flat universe, the angular distance is the proper length of the object at the time of emission.

#### Luminosity Distance
Recall that:

$$
d_L = (1+z) S_k(r) = (1+z)^2 d_A
$$

For a flat universe, we replace the angular diameter disntance:

$$
d_L = (1+z)d_c(z)
$$


