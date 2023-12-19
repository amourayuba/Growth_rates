# Growth rates vs cosmology

Investigate how growth rates vary with cosmology. This represents the code and data used for the publication 
: https://ui.adsabs.harvard.edu/abs/2024MNRAS.527.3459A/abstract 

The codes in analytical_models rely on the functions in https://github.com/amourayuba/Halo_Analytical_Calculations.
And the subsequent dependencies within that project. The codes in simulations require the functions and 
the Simulation class in https://github.com/amourayuba/Simulations.

## Analytical
These are jupyter notebooks, data and figures of various quantities derived from analytical models. 
The main file of this subproject is the jupyter notebook 

### Growth_rates.ipynb 
The cosmological dependance of merger rates, halo average growth and fraction of halos with large growth. 
Figures of the first (analytical) part of the paper Amoura et al. (2023)

The second jupyter notebook cadence_comparison.ipynb, looks at the influence of snapshot cadence on the measured 
average growth. 

## Simulations 
These are jupyter notebooks, calculations data and figures of various quantities derived from simulations. These 
represent the codes used to generate the data and figures in the second part of Amoura et al. (2023)

### Simulations vs analytical models
Comparing simulations to analytical models for each set of simulations we have

### Merger_rates_vs_cosmo.ipynb 
Looking at the results from MxSy simulations for the different growth rate quantities as a function of cosmology, 
and comparing with the analytical trends

### Fitting_growt_vs_mass.ipynb 
Fitting the trends of average_growth = f(Mass) and large_growth = f(Mass) found in simulations. 


