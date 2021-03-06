# effec_mass

In solid-state theory, the effective band mass in $k \cdot p$ theory is:

$\frac{1}{m^{\ast}} = \frac{1}{\hbar^2} \frac{\partial^2 E}{\partial k^2}$

We can account for non-parabolicity of the bands using a hyperbolic fit:

$ \frac{\hbar^2 k^2}{2 m^{\ast}} = \varepsilon ( 1 + \gamma \varepsilon) $

where the degree of non-parabolicity $\gamma$ is a fitting parameter.

Here is small Python implementation that tabulates and displays fits of different amounts of truncation of the data.
It is recommended to sample the k-point path along the high-symmetry directions densely.
