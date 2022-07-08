![](https://i.imgur.com/SHXUtSU.jpg)

# <b>1 <span style='color:#2DB1AB'>|</span> BACKGROUND</b> <a id = '1'></a>

### Simulation Data

#### Computational Fluid Dynamics

- Computational Fluid Dynamics (CFD) is the process of <b>mathematically modeling</b> a physical phenomenon involving <code>fluid flow</code> and solving it numerically. [I](https://www.simscale.com/docs/simwiki/cfd-computational-fluid-dynamics/what-is-cfd-computational-fluid-dynamics/)
- In these CFD simulations, the <b>flowfield that air takes around geometry</b> is <b>modeled</b> using a **physics based partial differential equation** <code>(PDE)</code> solution
- Our <code>dataset</code> we use here is a summary of a <b>number of such simulations</b> converged to a some final solution, in which we test a particular airfoil design that can vary geometrically
- Variation in design/geometry (shown in Fig.2) can subseqently affect its aerodynamic performance (eg. production of upward force);

### <b><span style='color:#2DB1AB'>CFD SIMULATION DATA</span></b>

The data that is exported from <code>CFD</code> can be split into two categories:
- <code>flowfield</code> data : Data that is stored in 2/3D space (dataset or its subset)
- <code>tabular</code> data : Data that is extracted from different the flowfield (point data/performance metrics)

| FIGURE 1. Example Solution ( Fluid Flow Around Airfoil ) | FIGURE 2. Geometric Modifications [[1]](https://www.researchgate.net/publication/267490031_Modeling_Slope_Discontinuity_of_Large_Size_Wind-Turbine_Blade_Using_Absolute_Nodal_Coordinate_Formulation) | 
| - | - |
| <img src="https://i.imgur.com/TXEjwmF.png" alt="Drawing" style="height: 200px;"/> | <img src="https://www.researchgate.net/profile/Ayman-Nada-2/publication/267490031/figure/fig4/AS:635439035723785@1528511880766/AIRFOIL-SHAPE-PARAMETERS.png" alt="Drawing" style="height: 200px;"/>
