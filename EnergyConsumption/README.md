# Prediction of Energy Consumption
Featured in HackerEarth Competition

## Data Download
Data set available from: https://he-s3.s3.amazonaws.com/media/hackathon/machine-learning-challenge-5-1/predict-the-energy-used/ae5e3a76-0-energy.zip
or the same file can be found in the project - [train.csv](train.csv) and [test.csv](test.csv). 

## Data Structure
- Data Fields 

|Variable name|Description|
|-------|-------|
|Observation|Observation ID|
|T1|Temperature in kitchen area in Celsius|
|RH_1|Humidity in kitchen area in %|
|T2|Temperature in living room area in Celsius|
|RH_2|Humidity in living room area in %|
|T3|Temperature in laundry room area in Celsius|
|RH_3|Humidity in laundry room area in %|
|T4|Temperature in office room in Celsius|
|RH_4|Humidity in office room in %|
|T5|Temperature in bathroom in Celsius|
|RH_5|Humidity in bathroom in %|
|T6|Temperature outside the building (north side) in Celsius|
|RH_6|Humidity outside the building (north side) in %|
|T7|Temperature in ironing room in Celsius|
|RH_7|Humidity in ironing room in %|
|T8|Temperature in teenager room 2 in Celsius|
|RH_8|Humidity in teenager room 2 in %|
|T9|Temperature in parents room in Celsius|
|RH_9|Humidity in parents room in %|
|To|Temperature outside in Celsius|
|Pressure|Outside pressure in mm Hg|
|RH_out|Humidity outside in %|
|Wind speed|Speed of wind outside in m/s|
|Visibility|Visibility from outside measuring station in km|
|Tdewpoint|Dew point temperature in °C|
|Energy|Energy used by appliances in Wh|

- Count - 15782 in Train
        - 3946 in Test

## Requirements
- `pandas`
- `xgboost`
- `sklearn`
- `matplotlib`
- `sklearn`

To install any of the libraries, run pip install `library_name`

## Classifiers
- `XGBoost` 
- `Linear Regression`
- `Random Forest`

## Paramter Tuning in XGBoost
- Use CV and Grid Search to tune XGBoost parameters
