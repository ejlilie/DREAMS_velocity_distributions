# DREAMS Velocity Distributions
Code used to produce dark matter velocity distributions from DREAMS CDM simulations. One tutorial showing how to get the velocity distribution using kernel density estimation, and one tutorial for using the velocity distribution with the NeHOD emulator.

KDE_Tutorial shows how to get the velocity distributions and then plotting them. 

Emulator_Tutorial shows how to get emulated velocity distributions using the NeHOD normalizing flows emulator. Based on the emulator from https://github.com/trivnguyen/nehod_torch

Varied_100000_HISTS containts the $10^{6}$ histogrammed speed distributions used in [] in the format of np.array(63,100000) Where the first three rows correspond to $M_{\star}$, $M_{\rm LSR}$, and $R_{M}$ (See [https://arxiv.org/abs/2505.07924]). The last 60 rows are the height of the histogram for all 60 bins from speeds of 0 to 650 km/s. We also include as the list of varied baryonic in the format np.array(3,100000) where the 3 rows correspond to $\bar{e}_{w}$,  $\kappa_{w}$, and $\epsilon_{f,\rm{high}}$.
