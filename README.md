# Dengue Fever Forecasting
WHO data wrangling and time series analysis for Dengue Fever in Brazil.

Link to data: https://www3.paho.org/data/index.php/en/mnu-topics/indicadores-dengue-en/dengue-nacional-en/252-dengue-pais-ano-en.html

Minor cleaning and wrangling for the purposes of epidemiological comparison including adding new columns for the change in values and dropping some not needed or redundant values. 

Forecasting done using time series SARIMA (Seasonal Auto-Regressive Integrated Moving Average). This model was appropriate in taking into account the seasonal, non-stationary, and with more work the exogeneous nature of infectious disease. Currently, this is only a SARIMA model as external factors like weather, public health interventions, and population density have not been included. I will add some more factors with time.


# Data Visualizations
The model predicts, with increasingly large confidence intervals, that Dengue Fever cases will decrease until eventually having a minor spike comparable with past seasons. Uniquely this model predicts a historically low Dengue Fever season with predictions hitting 0 new cases for some weeks. 
![image](https://github.com/CarruthT/DengueFeverForecasting/assets/97051391/8458f7a6-72e4-45aa-a0f4-a2ae5dddb548)

Denge Fever total Deaths are predicted to be somewhat comparably low overall with a similar S-curve. Notably, these confidence intervals get incredibly wide with 2022 Dengue Fever deaths being comparable and possible for this Dengue Fever season. 
![image](https://github.com/CarruthT/DengueFeverForecasting/assets/97051391/8aa56a98-3fbd-42c2-adf7-68770051da2e)

# Contributions

All work completed by Trystan Carruth
email: Trystaned@gmail.com
