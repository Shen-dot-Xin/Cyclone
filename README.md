# Cyclone

This is the demo codes for storm surge simulation of Hurricane Michael presented by Miya Dubler and Shen Xin for APAM seminar.

setrun.py sets up the parameters in the simulation model and AMR methods. It also takes in topography file, i.e. the Gulf of Carribean, and gauge locations, i.e. 3 locations on the coast of Florida pan handle where Hurricane Michael make its landfall.

setplot.py specficies how simulation results are to be plotted, including the number of plots, the geographical regions shown in each plot, legends, gauge observation data, etc..

All the codes are based on existing codes in the Clawpack repository, which could be downloaded here: https://www.clawpack.org/

Simulation of Hurricane Michael is initiated by the command "make all".
