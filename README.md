# Parks and Health Ailments in Texas Counties

## Introduction
This project examines the relationship between the availability of parks in different counties and the prevalence of certain health ailments in those counties.
### Overview
For the year of 2021, the United States was ranked #39 of 49 on the OECD rankings for life expectancy. With heart disease frequently the leading cause of death, year over year, more attention should be given to what can be done to improve overall health and wellness for residents in the United States.

Being active is often the key to a healthier lifestyle resulting in a longer lifespan. Exercise can raises the heart rate, improves mobility, and reduce excess weight. The availability of parks and impacts public health. Parks can be used for promoting physical activity through recreational programs, structured group activities (fitness class, walking groups, etc). With access to resources that can be utilized for physical activity like public parks people can seize the opportunity for exercise resulting in increased heart health and help reduce health disparities in the county.

### Questions:
What is the correlation between access to park space in relation to health conditions like cardiovascular disease (heart disease and stroke) and diabetes? Does greater availability of public parks improve health of citizens?

What is the correlation between access to park space in relation to health conditions like cardiovascular disease (heart disease and stroke) and diabetes? Does greater availability of public parks improve health of citizens?

## Data
The data for this project was collected from the various county data sources and the CDC PLACES Database. The variables used in the analysis include the number of parks in each county, as well as the prevalence of various health conditions such as COPD, Coronary Heart Disease, Diabetes, High Blood Pressure, High Cholesterol, Obesity, Physical Inactivity, Stroke, and taking BP Medication.

**PLACES: Local Data for Better Health, Place Data 2020 release**: https://chronicdata.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-Place-Data-202/q8xq-ygsk

**PID Parks Points (Harris County, TX Parks)**: https://geo-harriscounty.opendata.arcgis.com/datasets/pid-parks-points/explore?location=29.825164%2C-95.407200%2C10.44

**Williamson County, Texas Parks and Open Spaces**: https://koordinates.com/layer/99384-williamson-county-texas-parks-and-open-spaces/data/

**Denton County, Texas Parks**: https://koordinates.com/layer/98122-denton-county-texas-parks/data/

**Montgomery County, Texas Public Parks**: https://koordinates.com/layer/99222-montgomery-county-texas-public-parks/

## Methods
The data was cleaned and preprocessed to handle missing values and outliers. Linear regression model was used to examine the relationship between the number of parks and the prevalence of health conditions. The analysis was done using python and the libraries used are pandas, numpy, and statsmodels.

## Results
"Our study found that there is a connection between the number of parks in a county and the rates of High Cholesterol and Stroke. It also found a weak association with High Blood Pressure. The other health conditions do not show a significant relationship with the number of parks.

## Conclusion
The study suggests that the availability of parks in a city may have an impact on certain health conditions. However, more research is needed to fully understand the relationship and to investigate potential confounding variables. It's important to note that this study only looked at a small sample, and more research is needed to understand the relationship better and to establish causality

## Installation
To run the code, you need to have python 3 and the following libraries installed:

* pandas
* numpy
* statsmodels

## Licensing
This project is licensed under the MIT License.



