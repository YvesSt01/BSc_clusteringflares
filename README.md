# ReadMe

This repository contains 3 different sets of code, all tailored toward being run on the AIUB server. 

The first set, Observation_selection, selects the observations from the flarelist that fit the set requirements (single-raster step, an observed Mg II h/k line and a minimal wavelength of less than 2791 Angstrom. This does not sort between observations where a flare is observed on the slit and where there is not. That selection needs to be done by eye using either the flare list or the IRIS website.

The second set, Clustering_observations, takes a number of observations in the same flare class that fit the requirements and observed a flare on the slit. The code applies the k-means method to the spectra within it.

The third set, Calculating_velocities, takes the data collected in the second set and returns a velocity plot where the velocities of the spectra of each observation are displayed separately, as well as a histogram of the velocity distribution. 
