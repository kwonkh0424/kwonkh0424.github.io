## Hurricane Forecast Modeling

<img src="/images/hurricane_charley.JPG?raw=true"/>
<img src="/images/hurricane_track.JPG?raw=true"/>
Ramsay (2017, DOI: 10.1093/acrefore/9780199389407.013.79)

**Project description:** Analyze historical hurricane data to build predictive models for the following purposes:
- determine whether or not a hurricane will go through "rapid intensification" in the next 24 hours
- predict hurricane intensity in the next 24 hours
- predict the total economic loss that will be created by a given hurricane

This project was in collaboration with NASA (JPL) to provide them a new predictive solution.

### 1. Data Sets

The following data sets were utilized:
1. Statistical Hurricane Intensity Prediction Scheme (SHIPS)
2. Second-Order Statallite IR Data: Hurricane Precipitation
3. Economic Loss Caused By Each Hurricane
4. GDP Level by each Latitude and Longitude

### 2. Hurricane Rapid Intensification (RI) Forecast Model (Categorical)

Hurricane rapid intensification Forecast is the key to preventing damage caused by a hurricane. The most damage is caused when a hurricane with low intensity suddenly intensifies as it lands on major cities. This model utilizes various machine learning algorithms to create an ensemble model to accurately predict whether or not a hurricane will go through RI in next 24 hours.


### 3. Hurricane Intensity Forecast Model (Regression Model)

This model is built from the previous classification model. However, this model predicts a numerical value of hurricane intensity. The model was able to achieve RMS Error less than 13 knots.

* The script of the model cannot be shared


### 4. Economic Loss Model

Currently being built. This model predicts the total amount of damage caused by a hurricane. Which this solution, local governments, and insurance companies will be able to better prepare for the hurricane seasons.

* The script of the model cannot be shared

For more details see [Hurricane Rapid Intensification (RI) Forecast](https://github.com/kwonkh0424/Hurricane-Prediction-Model).
