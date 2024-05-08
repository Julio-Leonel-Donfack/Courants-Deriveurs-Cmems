# Courants-Drifters-Cmems

This repo contains 
my Study notebooks on the agestrophic components of currents, for my internship in oceanography.
## Working through binder

Notebooks are available through binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ecosme38/Fluid-Mechanics-Intro/master)

## Working in your own jupyterlab

Five notebooks are available at present to illustrate:

- [Drifters and currents](1-dériveurs-courants-visualisations.ipynb)  
We visualize the current variables present in our drifter data. These variables are Eastward velocity (ve), Northward velocity (vn), and we also include the visualization of sea surface temperature (SST) present in our data.
- [Drifters and positions](2-drifters-positions.ipynb) 
We gather all the drifters present in our datasets and provide their positions within our study area for a selected collection date.
- [Interpolation cmems to drifters data](3-interpolation-cmems-drifters.ipynb)
We interpolate the current data from CMEMS to that of the drifters using linear interpolation method.
- [Inertial oscillation](4-oscillation-inertielle-des-dérives.ipynb)
After interpolating CMEMS data onto the drifters, we notice that the period of oscillations is much shorter. The question arises: could this be due to inertial waves? From the frequencies derived from these waves, we conclude that it is indeed the inertial wave because the frequencies obtained are on the order of 10^-6, close to zero, which are of the same magnitude as those corresponding to Coriolis forces and thus potentially inertial forces.
- [Calculating Duacs currents near the equator using SSH (Sea Surface Height) data.](55-working-with-2D-ocean_A.ipynb)
Here, we propose calculating these currents using linear approximation to correct the Coriolis parameter near the equator.
- [Calculating Duacs currents near the equator using SSH (Sea Surface Height) data.](55-working-with-2D-ocean_B.ipynb)
Here, we propose calculating these currents using beta approximation to correct the Coriolis parameter near the equator.






