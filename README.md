# Observatory Baselines
Annual periodicity in geomagnetic observatory baseline data

## Abstract
The analysis of 149 observatory baselines revealed a significant annual periodicity in the baseline data, even though the data is supposed to remain constant. Since the periodicity occurs in 119 out of the 149 observatories, it can be considered a global phenomenon, making an error in the measurement or calculation of some observatories unlikely. The amplitude of the X and Y components is greatest in the polar regions and lowest at the equator, with the extrema occurring mainly at the two equinoxes.
To identify the cause of this variation, several possible reasons were examined. Temperature may contribute to the fluctuation but is probably not the main reason, as the amplitude is quite large, and the sensitivity of the sensors to temperature is not that significant. Groundwater is also unlikely to be the primary cause, nor is the Sq variation. The actual reason for the fluctuation likely consists of various factors, and to truly understand it, a closer examination of each location and setup is necessary.

## Data
The baseline data is provided from INTERMAGNET. The observed base values and the adopted baselines were plotted and can be found in the folder "data/plots/adopted_baseline". To check if the baselines show an annual periodicity a power spectral analysis was performed for each observatory and each component. To make this funktion work, data without gaps and jumps is required. These corrected baselines can be found in "data/plots/corrected" and the power spectra are provided in "data/plots/powerspectrum". The average yearly baselines can be found in "data/plots/amplitude", where you can see the days of maxima and minima and the Amplitude in nT. The python code, which was used to correct and analyze the data, is provided in "data/blv_analysis.ipyn". 

## Thesis
The complete bachelor thesis, in which the analysis is presented and evaluated, is also uploaded here.
