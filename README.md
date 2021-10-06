# Machine-Learning-problem-Resturent Revenue Prediction

This is a machine learing problem to find the revenue of a resturant on the basis of given data

## data source: from KAGGLE

## Data fields

Id : Restaurant id. 

Open Date : opening date for a restaurant

City : City that the restaurant is in. Note that there are unicode in the names. 

City Group: Type of the city. Big cities, or Other. 

Type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile

P1, P2 - P37: There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include population in any given area, age and gender distribution, development scales. Real estate data mainly relate to the m2 of the location, front facade of the location, car park availability. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators.

Revenue: The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values. 

Language used- python

life cycle of this problem-

1)EDA
  libraries = pandas ,numpy, matplotlib,seaborn
  
2)feature engineering-
  techniques used - for categorical encoding by label and one-hot encoding
                  -for standardization by thorough log normal transformation and StandardScaler

3)feature selection by through correlation

4)model = Linear regression
                  
