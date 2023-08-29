We provide neutrino data for 100 2D simulations using Fornax. This data release is for a paper submitted to MNRAS, https://ui.adsabs.harvard.edu/abs/2023arXiv230708735V/abstract.

For each model, we include 3 files, nustat.{}.dat, where the brackets range from 0-2 indicating neutrino species (0=electron neutrino, 1=electron antineutrino, 2=bundled four 'heavy' neutrinos). These files have five columns, labeled time, neutrino luminosity, average neutrino energy, RMS neutrino energy, and skew neutrino energy. The energies are in MeV, and the luminosity is in 10^(52) erg s^-1). The values are calculated at 500 km. Note that, when looking at the neutrino luminosity per 'heavy' neutrino, the column value is divided by 4.

We use 12 log-spaced bins (in the comoving frame, between 1-300 MeV for the electron neutrinos and 1-100 for the electron antineutrinos and the bundled 'heavy' neutrinos, indicated in our paper above). The energy bin centers are then geometric averages of the bin edges. 

E.g.: python script to read the energy bins for the electron-neutrinos:
import numpy as np
e_nu=np.logspace(0,np.log10(300),13)

Please reach out with any questions to David Vartanyan at dvartanyan@carnegiescience.edu
