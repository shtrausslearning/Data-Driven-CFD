![](https://i.imgur.com/SHXUtSU.jpg)

# <b>1 <span style='color:#2DB1AB'>|</span> BACKGROUND</b> <a id = '1'></a>

<div style="color:white;display:fill;border-radius:8px;
            background-color:#323232;font-size:150%;
            font-family:Nexa;letter-spacing:0.5px">
    <p style="padding: 8px;color:white;"><b>1.1 | SIMULATION DATA</b></p>
</div> <a id = '1.1'></a>

### <b><span style='color:#2DB1AB'>COMPUTATIONAL FLUID DYNAMICS (CFD)</span></b>

> Computational Fluid Dynamics (CFD) is the process of <b>mathematically modeling</b> a physical phenomenon involving <br>
> fluid flow and solving it numerically using the computational prowess. [[I]](https://www.simscale.com/docs/simwiki/cfd-computational-fluid-dynamics/what-is-cfd-computational-fluid-dynamics/)

- In these CFD simulations, the <b>flowfield that air takes around geometry</b> is <b>modeled</b> using a physics based partial differential equation (PDE) solution
- Our dataset we use here is a summary of a <b>number of such simulations</b> converged to a some final solution, where we test a particular airfoil design (which can vary geometrically) 
- Variation in design/geometry (shown in Fig.2) can subseqently affect its performance to for example produce upward force; we have data that models the physics of fluid flow

### <b><span style='color:#2DB1AB'>CFD SIMULATION DATA</span></b>

The data that is exported from CFD can be split into two categories:
> - <b>Flowfield</b> (Shown in Fig.1) - Data that is stored in three or two dimensional space
> - <b>Tabular data</b> (The data we will load here) - Data that is extracted from the flowfield 

| FIGURE 1. Example Solution ( Fluid Flow Around Airfoil ) | FIGURE 2. Geometric Modifications [[1]](https://www.researchgate.net/publication/267490031_Modeling_Slope_Discontinuity_of_Large_Size_Wind-Turbine_Blade_Using_Absolute_Nodal_Coordinate_Formulation) | 
| - | - |
| <img src="https://i.imgur.com/TXEjwmF.png" alt="Drawing" style="height: 400px;"/> | <img src="https://www.researchgate.net/profile/Ayman-Nada-2/publication/267490031/figure/fig4/AS:635439035723785@1528511880766/AIRFOIL-SHAPE-PARAMETERS.png" alt="Drawing" style="height: 400px;"/>
