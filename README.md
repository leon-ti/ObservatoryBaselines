# Observatory Baselines
Annual periodicity in geomagnetic observatory baseline data

## Abstract
My bachelor thesis investigates the phenomenon of the annual periodicity in observatory baselines. Baselines are critical components in geomagnetic observatories, serving as references for absolute magnetic field measurements. Despite their importance, the underlying causes of observed periodic variations remain insufficiently understood. This study aims to identify the sources of these annual variations through an analysis of baseline data, environmental influences, and instrumental factors. Using statistical and physical modeling approaches, potential contributors such as seasonal temperature fluctuations, sensor alignment, and external magnetic influences are evaluated.

## Data
The baseline data is provided from INTERMAGNET. The observed base values and the adopted baselines were plotted and can be found in the folder "data/baselines". To check if the baselines show an annual periodicity a power spectral analysis was performed for each observatory and each component. To make this funktion work, a time window without gaps and jumps is required. These time windows can be found in "data/trim" and the power spectra are provided in "data/powerspectrum". The average yearly baselines can be found in "data/averagebaseline", where you can see the days of  maxima and minima and the Amplitude in nT.
