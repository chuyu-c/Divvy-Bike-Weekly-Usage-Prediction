# Divvy Bike Weekly Usage Time Series Prediction using R

### Data Source
City of Chicago Data Portal
https://data.cityofchicago.org/Transportation/Divy_daily_duration/3hs6-p2qv

### Data Description & Preprocessing
* Frequency: Daily total trip duration 
* Time Period: 6/27/2013 – 12/31/2019
* Unit of Measurement: Second
* Missing Data: Impute 2 missing data with 0
* Frequency Transform: Aggregate daily data into weekly data

### Train-Test Split
* Train Period: 6/30/2013 – 12/31/2018 (287 weeks)
* <span style="color:red;">Test Period:</span> 1/1/2019 – 12/31/2019 (52 weeks)


### Reference
https://www.evolvedatascience.com/post/forecasting-divvy-bikesharing-traffic/


```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
