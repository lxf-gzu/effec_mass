# effec_mass

In solid-state theory, the effective band mass in <img src="/tex/07b421138ecb957b53f2aebfb95e3220.svg?invert_in_darkmode&sanitize=true" align=middle width=29.217911249999993pt height=22.831056599999986pt/> theory is:

<img src="/tex/0af34993176ca858f73ef8beb83bf08e.svg?invert_in_darkmode&sanitize=true" align=middle width=86.47035704999999pt height=33.45973289999998pt/>

We can account for non-parabolicity of the bands using a hyperbolic fit:

<img src="/tex/46ac385a4ba317e74f851b5e8846fd56.svg?invert_in_darkmode&sanitize=true" align=middle width=117.12134279999998pt height=33.45973289999998pt/>

where the degree of non-parabolicity <img src="/tex/11c596de17c342edeed29f489aa4b274.svg?invert_in_darkmode&sanitize=true" align=middle width=9.423880949999988pt height=14.15524440000002pt/> is a fitting parameter.

Here is small Python implementation that tabulates and displays fits of different amounts of truncation of the data.
It is recommended to sample the k-point path along the high-symmetry directions densely.

Example output:

![](./example/example-effec-band-mass.png)
