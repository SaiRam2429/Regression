# Air Quality Prediction.

* The Goal of this project is to predict the Air Quality 
* Although there are different continuous features, We use NOx(Nitric Oxide) as our target as it is a harmful gas.
## Features 
* Date (DD/MM/YYYY)
* Time (HH.MM.SS)
* True hourly averaged concentration CO in mg/m^3 (reference analyzer)
* PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
* True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
* True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
* PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
* PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
* True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
* PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
* PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
* Temperature in Â°C
* Relative Humidity (%)
* AH Absolute Humidity

## Target
* True hourly averaged NOx concentration in ppb (reference analyzer)

## Algorithms
* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net

<p>The Ultimate goal is not just to build a model but to interpret, thus different algorithms were used to interpret features </p>
