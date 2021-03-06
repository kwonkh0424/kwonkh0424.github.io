## Covid-19 Trend Analysis

**Project Description:** The purpose of the project was to build a risk trend analysis tool for the LA county government to easily visualize and determine the risk trend of LA county regions. 

### 1. Data Collection
In order to determine the LA country's risk-score trend, the following datasets were utilized:
1. Covid-19 Risk Score of LA country (RMDS)
2. Daily new cases and deaths of each region within LA County (http://publichealth.lacounty.gov)
3. Lists of LA country regions

### 2. Methodology:
A number of new cases and Risk-Score of LA county regions showed regular oscillation characteristics with a period of 7-10 days. With large oscillations, a simple analysis of trends could lead to inaccurate conclusions about the Covid-19 situation in each LA region. In order to reduce a large amount of noise/variance in the data, a moving average of 18 days was calculated.

<img src="images/la_county_risk_score.png?raw=true"/>
<img src="images/hollywood_risk_score.png?raw=true"/>

### 3. Categorization of Regions: Trending Up, Neutral, Trending Down

By taking a slope analysis of moving averages, the regions of LA county were divided into three categories: trending up, neutral, trending down. This data is updated daily to the LA county government to let them know which regions of LA county will experience a serious increase in Covid-19 cases in the coming weeks.

### 4. Output: Map-Based Solution

The final outputs of the projects were:
1. time-series plots of Covid-19 total cases and risk-score trend in each region
2. a table ranking regions of LA county by risk-score trend (higher ranking = higher risk trend)

The daily updated table was sync to a color-coded interactive map [RMDS RISK SCORE MAP](https://grmds.org/risk/) enabling the audience to easily determine the risk level of regions that they are interested in.

<img src="images/la_county_risk_map.JPG?raw=true"/>

For more details see [COVID 19 TREND ANALYSIS GitHub Repo](https://github.com/kwonkh0424/Covid_19_Challenge/tree/master/risk_score_trend).

