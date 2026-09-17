# Amazon Shallow Cumulus Forcings for LES/CRM and 1D models. 

This repositories contains the initial 
condition and the large-scale forcing 
to reproduce the Shallow Cumulus(ShCu)
convection in Central Amazon(CA). 

The initial conditions, large-scale forcing, and surface 
fluxes for the Amazon ShCu data set were created, 
averaging data set from 30 representative 
cases of ShCu in CAMZ during the intensive operational period 1 and 2, IOP1 and IOP2 
respectively. This composite is called Amazon ShAMZ, its mass flux time 
evolution simulated by the System for Atmospheric
Modeling (SAM)  v.6.10.6 (Khairoutdinov & Randall, 2003) model is show in Fig.1. 

<p align="center">
 <img src="fig/mass_flux_2d_ca_sh.png" width="500" />
</p>
Figure 1. The time evolution (average every 5 minutes) of the updraft mass flux (uMF) [kgm^2s^-1] profiles
for the Amazon ShCu. The mixing layer height (Zi, black lines) is defined at the minimum buoyancy flux (B), cloud base
height [km] (h_base, red dashed lines) at the maximum CF level, cloud top [km] (h_top, black dot-
ted lines) at the level where CLW<0.001 [gkg−1]  above cloud base and the
level of free convection (LFC [km], purple dashed lines) at the level where B>0, above Zi.

<br><br>

In order to study the factors for ShCu clouds growth, these 30 ShCu cases were classified 
into three categories, small, medium, and
large , according to their cloud-top height and depth, and their respectively composites were created.
The initial conditions, large-scale forcing, and surface 
fluxes for these composites is also available 
The mass flux for these composites simulated using the SAM model is shown 
in Fig. 2. 

<p float="left">
  <img src="fig/mass_flux_2d_small.png" width="260" />
  <img src="/fig/mass_flux_2d_medium.png" width="240" /> 
  <img src="/fig/mass_flux_2d_large_all.png" width="300" />
</p>
Figure 2. The time evolution of the updraft mass flux (uMF) [kgm−2s−1] profiles
for small, medium and large ShCu composites. 

These composites are result of the published studies:

Buoyancy Flux and Its Environmental Modulation in the Vertical Development of Shallow Cumulus in the Central Amazon. 
Authors: Silvio N. Figueroa, Jhonatan A. A. Manco, Georgios A. Efstathiou
[DOI: https://doi.org/10.1029/2025JD045576](https://doi.org/10.1029/2025JD045576)

and

Large Eddy Simulation of the Diurnal Cycle of Shallow Convection in the Central Amazon.
Authors: Jhonatan A. A. Manco and  Silvio N. Figueroa.
[DOI: https://doi.org/10.3390/atmos16070789](https://doi.org/10.3390/atmos16070789)
_____
## Data:

The data  was created to run into the SAM, the 
Single Column Atmospheric Model, version 6 (SCAM6) (Gettelman et all., 2019), 
and The Common Community Physics Package (CCPP) (Ligia Bernardet et all. 2024).

For the SAM model:

[<img src='fig/sam_logo.jpg' width='190'>](SAM_forcings)

For the NCAR SCAM 6 model:

[<img src='fig/logo-ncar-active.png' width='150'>](SCAM_forcings)

For the CCPP model:

[<img src='fig/logo-ccpp.png' width='150'>](CCPP_forcings)

### References

Gettelman, A., Truesdale, J. E., Bacmeister, J. T., Caldwell, P. M., Neale, R. B., Bogenschutz, P. A., & Simpson, I. R. (2019). The Single Column Atmosphere Model version 6 (SCAM6): Not a scam but a tool for model evaluation and development. Journal of Advances in Modeling Earth Systems, 11, 1381– 1401. https://doi.org/10.1029/2018MS001578.

Khairoutdinov, M. F., and D. A. Randall, 2003: Cloud Resolving Modeling of the ARM Summer 1997 IOP: Model Formulation, Results, Uncertainties, and Sensitivities. J. Atmos. Sci., 60, 607–625, https://doi.org/10.1175/1520-0469(2003)060<0607:CRMOTA>2.0.CO;2.

Ligia Bernardet, Lisa Bengtsson, Patrick A. Reinecke, Fanglin Yang, Man Zhang, Kyle Hall, James Doyle, Matus Martini, Grant Firl, and Lulin Xue:
Common Community Physics Package: Fostering Collaborative Development in Physical Parameterizations and Suites. Bull. Amer. Meteor. Soc., 105, E1490–E1505
https://doi.org/10.1175/BAMS-D-23-0227.1.
