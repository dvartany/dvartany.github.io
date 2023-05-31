
We provide gravitational wave (GW) data sourced by matter asymmetries for our set of 3D simulations accepted in 2023 to PRD. 
We study 11 simulations in total: four simulations of a 9 solar mass progenitor, as well as a 9.25, 9.5, 11, 12.25, 14, 15.01, and 23. 
All models but the 12.25 and 14 explode. These models are carried to the longest times to-date (the 23 solar mass progenitor reaches 6.2s post-bounce)
and the GW data is dumped at a high frequency so we are not Nyquist limited out to ~8000 Hz for most models.
See paper https://ui.adsabs.harvard.edu/abs/2023PhRvD.107j3015V/, particularly Table I, for more details.

We include in the *gwstrain*.dat the time [s] and both polarizations (in cm) of the strain viewed along the +x axis in the format (t, hp*D, hx*D). 
To find the strain for a source a given distance, divide hp*D, hx*D by the source distance in cgs (e.g. 10kpc = 3.086e22cm).

We include in *quadrupole*.dat the time [s] and the quadrupole moments Qxx,Qxy,Qxz,Qyy,Qyz,Qzz and their derivatives dQxx,dQxy,dQxz,dQyy,dQyz,dQzz.
