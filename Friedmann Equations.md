# Friedmann Equations and Scale Factor Dependence

### Write down the Friedmann equation and the fluid equation in a flat universe (i.e. ignore curvature terms).
#### Friedmann Equation
The Friedmann Equation gives the relationship between the expansion rate and the energy budget within the universe:

$$
\bigg( \frac{\dot{a}}{a} \bigg)^2 = \frac{8 \pi G \rho}{3} - \frac{kc^2}{R_0^2a^2}
$$

When derived with a proper GR treatment, $k \in \{-1,0,1\}$, which corresponds to an open, flat and closed universes. For a flat universe, the Friedmann Equation clearly simplifies to:

$$
\bigg( \frac{\dot{a}}{a} \bigg)^2 = \frac{8 \pi G \rho}{3}
$$

#### Fluid Equation
Starting from the First Law of Thermodynamics $dQ = TdS = dU + PdV$ and using the cosmological principle ($dQ=0$) alognside the notion of a comoving volume, one can arrive to the Fluid Equation:

$$
\dot{\rho} + 3\frac{\dot{a}}{a}\bigg(\rho + \frac{P}{c^2} \bigg) = 0
$$

To build some physical intuition, one can conceptualize the fluid equation as a sort of generalization of energy conservation that takes into account an expanding universe.

#### Acceleration Equation
For completion, there is a third important equation that describes the dynamics of an expanding universe, which can be obtained by combining the Friedmann and the Fluid Equations:

$$
\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\bigg( \rho + \frac{3P}{c^2} \bigg)
$$

This is known as the Acceleration Equation, as it relates the energy content of the universe with the rate at which the comoving factor is changing over time.

### Show that in a vacuum-dominated universe with \rho_\Lambda approximately  constant, the scale factor increases exponentially with time.
As we saw, the Friedmann Equation in a flat universe becomes:

$$
\bigg( \frac{\dot{a}}{a} \bigg)^2 = \frac{8\pi G \rho}{3}
$$

With a dark energy dominated universe, we can say $\rho \approx \rho_{\Lambda} \approx$ const. This allows us to do write the following:

$$
\int ln(a)da = \bigg( \frac{8 \pi G \rho_{\Lambda}}{3} \bigg)^{1/2} \int dt
$$

And clearly:

$$
a(t) = e^{H_0(t-t_0)}
$$

### Find the relation between scale factor and time in a matter dominated and a radiation dominated universe.
The Friedmann and the Fluid Equations can be used to derive the equations that govern the dynamics of an expanding universe. However, these two independent equations have three unkwowns: $a(t)$, $\rho$ and $P$. For this reason, we employ an equation of state of the form:

$$
P = w\rho c^2
$$

Where $w$ is a constant number that depends on the energy component. We can input this in the Fluid Equation and, after simplifying, we get:

$$
\frac{\dot{\rho}}{\rho} = -3(1+w)\frac{\dot{a}}{a}
$$

Integrating both sides:

$$
\rho = \rho_0a^{-3(1+w)}
$$

We can now use this in the Friedmann Equation, and after simplifying, we get that for a single-component universe:

$$
a(t) = \bigg( \frac{t}{t_0} \bigg)^{\frac{2}{3(1+w)}}
$$

Now, we can use the corresponding values of $w$ for matter and radiation to obtain a dependence between the scale factor and time:

For matter, $w=0$, and thus:

$$
a_m(t) \propto t^{2/3}
$$

For radiation, $w=1/3$, and thus:

$$
a_r(t) \propto t^{1/2}
$$

**OPTIONAL:** We can then back track a little bit to solve for $t_0$, which gives us an expression for the age of the universe, again, if it had **one single component**:

$$
t_0 = \frac{1}{1+w} \bigg( \frac{c^2}{6\pi G \rho} \bigg)^{1/2}
$$

### How is the Hubble parameter related to the scale factor a(t)?


### Write down the approximate value of the Hubble constant today (including correct units), and hence give a rough estimate of the age of the universe.
