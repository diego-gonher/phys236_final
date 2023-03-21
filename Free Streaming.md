# Free Streaming

## What is free-streaming? 
In simple words, free-streaming means that particles can propagate through a medium without scattering, meaning that they're free to move easily throughout the system. Free-streaming is an important concept for us, because all the fluid approximations that we have made through our study of the thermal history and linear structure formation are only valid if the constituent particles have a free-streaming length that is much smaller than the size of the system they're part of. 

Intuitively, this makes sense. Think about density perturbations. If a particle species has a free-streaming length that is greater than the size of the perturbation, then the particles in (say) an overdensity will be able to diffuse their way out into other over/under-densities. This can damp inhomogeneities, which certainly can affect how structures evolve. 

## How does one calculate the free-streaming length? 
The free-streaming length is basically the same as the mean-free path that a particle species has in its medium. To properly calculate it in an expanding universe, we would have to use:

$$
\lambda_{mfp} = \int_{t_f}^{t}\frac{vdt'}{a(t')}
$$

Notice the similarity with the particle horizon integral, which comes from assuming that once a particle species decouples and interacts only rarely with other particle species, then those particles would follow geodesics. Now, this integral can become a little bit complicated, as we need to consider if the particle species is relativistic or not at the time of decoupling, and which energy component is dominating the universe (as that affects the denominator). Typically, one evaluates the free-streaming length at time of the matter-radiation equality since that is when structure starts evolving:

$$
\lambda_{FS} \approx \frac{2ct_{NR}}{a_{NR}}[2+ln(a_{eq}/a_{NR})]
$$

Heuristically, it is evident that more massive particles go non-relativistic at earlier times, which means that they don't have a lot of time to free-stream, which definetly affects how structure forms and evolves, and serves as a probe to determine which type of dark matter is most common in our universe, as we'll see next and in another question.

## Describe how free-streaming modifies the shape of the linear power spectrum for hot or warm dark matter.

