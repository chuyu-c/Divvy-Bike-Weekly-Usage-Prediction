# Divvy Bike Weekly Usage Time Series Prediction using R

## Data Source
City of Chicago Data Portal
https://data.cityofchicago.org/Transportation/Divy_daily_duration/3hs6-p2qv

## Data Description & Preprocessing
* Frequency: Daily total trip duration 
* Time Period: 6/27/2013 – 12/31/2019
* Unit of Measurement: Second
* Missing Data: Impute 2 missing data with 0
* Frequency Transform: Aggregate daily data into weekly data

## Train-Test Split
* Train Period: 6/30/2013 – 12/31/2018 (287 weeks)
* Test Period: 1/1/2019 – 12/31/2019 (52 weeks)

## Analysis Goal
* Forecast the weekly usage of Divvy bike of different models and compare the forecast results
* The goal is to help Divvy Bike maximize profits by forecasting the demand of bike sharing programs and better optimize the bike usage, placement, and profitability
* In addition, we hope to measure the bike transportation activity and have a better understanding of the mobility in a city

## Structure of Code
* Bike Weekly Usage Forecast.R
* Bike Weekly Usage Forecast.html 

## Reference
https://www.evolvedatascience.com/post/forecasting-divvy-bikesharing-traffic/




```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
