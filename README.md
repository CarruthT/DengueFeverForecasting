# Dengue Fever Forecasting
WHO data wrangling and time series analysis for Dengue Fever in Brazil.

Link to data: https://www3.paho.org/data/index.php/en/mnu-topics/indicadores-dengue-en/dengue-nacional-en/252-dengue-pais-ano-en.html

Minor cleaning and wrangling for the purposes of epidemiological comparison including adding new columns for the change in values and dropping some not needed or redundant values. 

Forecasting done using time series SARIMAX(Seasonal Auto-Regressive Integrated Moving Average with eXogenous factors). This model was appropriate in taking into account the seasonal, non-stationary, exogeneous nature of infectious disease. 
![image](https://github.com/CarruthT/DengueFeverForecasting/assets/97051391/8aa56a98-3fbd-42c2-adf7-68770051da2e)
