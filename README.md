# Niologic_Challange
## Problem : Prediction of Call Volume for Seattle Fire Department
Dispatching emergency calls in a city is challenging: There are large variations over a year, Saison
and especially the time of day. Someone has to decide how many dispatchers are on duty every day.
Hence, we are looking for a model, which can predict the call volume for each day of the year and
each hour of the day.

To solve this challenge, I used the time series analysis. 

The data set is publicly available.

The notebook Call_Volume_for_Seattle_Fire_Department.ipynb contains 3 main parts:
- The first is a basic data visualization 
- The second is a model based on Fourier transformation. It assumes that the second highest-amplitude frequency plus an offset are enough to fit the data.
- The third is a more complex SARIMA model, which uses iteration over a specific parameter interval and minimum AIC value to find the best fit for the data.

