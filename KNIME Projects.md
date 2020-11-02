## Geographic Analysis of Chinese Cities

<img src="images/knime_logo.png?raw=true"/>

**Project description:** Analyze following geographical characteristics of chinese cities:
- Employment Change due to Green Energy Transiditon
- Population Estimation of Chinese Prefecture-Level Cities
- Comparative Analysis of Chinese Cities

This project was in collaboration with Center of Geographical Analysis (Harvard) to provide them new solutions.

### 1. Employment Change due to Green Energy Transition

Chinese government have declared that they will increase their reliance on green energy (wind, solar, geothermal, hydro, etc.). However, this rapid shift in energy source will cause a dramatic change in empoyment market throughout China. Utilizing KNIME platform, total employment change is calculated for each chinese province.

The script/calculation is based on the following article: 
Sara Hsu & Shelley Nauss (2009) Employment impacts of a ‘green’ energy
transition in China, China Economic Journal, 2:2, 219-237, DOI: 10.1080/17538960903083533

Data was collected from: [All China Data Center](https://www.china-data-online.com/)

Output:
#### 1. Table: List of Provinces and their employment change according to different energy shift scenarios

<img src="images/employment_change_table.jpg?raw=true"/>

#### 2. Color-coded Chinese Map based on employment change

<img src="images/Employment Map.png?raw=true"/>

Green: Regions with a significant increase in employment
Gray: Regions with no significant change in employment
Red: Regions with a significant decrease in employment


### 2. Population Estimation of Chinese Prefecture-Level Cities

Currently, Hukous survey is the system China utilizes to determine the population of each prefecture-level cities. However, this is highly biased method that doesn't accurately 

### 3. Hurriane Intensity Forecast Model (Regression Model)

This model is built from the previous classification model. However, this model predicts a numerical value of hurricane intensity. The model was able to achive RMS Error less than 13 knots.

* The script of the model cannot be shared


### 4. Economic Loss Model

Currently being built. This model predicts the total amount of damage caused by a hurricane. Which this solution, local govnerments and insurance companies will be able to better prepare for the hurricane seasons.

* The script of the model cannot be shared

For more details see [Hurricane Rapid Intensification (RI) Forecast](https://github.com/kwonkh0424/Hurricane-Prediction-Model).
