# Machine Learning Proejct: House Sale Price Prediction (Workflow)

Project context: 
In this project, we are going to analyse the house prices in the State of Texas. We will be looking the features that influence the house price and 
using some supervised learning algorithm to find the best price for each houses. 

Business Problem: the house prices in the US are expensive. The purpose of this project is to predict the best price for each houses
based on its characteristics. 

Hypothetical questions for this project:


### Analytical Approach: 
- analyse the dataset
- exploring features of the dataset
- model training and evaluating
- linear regression modeling
- visualise the best house prices aligning with each feature 

### Data Collection: 
- Kaggle Dataset: American House Prices https://www.kaggle.com/datasets/jeremylarcher/american-house-prices-and-demographics-of-top-cities/data 
- ChatGPT

ML/DS Workflow
+ Data Preprocessing
+ Exploratory Data Analysis
+ Feature Engineering
+ Feature Selection + Correlation Analysis

+ Model Building
+ Model Training
+ Hypertuning Parameters
+ Model Evaluation
+ Linear Regression: Single + Multiple linear regression
+ Cost Function for House price: Gradient Descent

### Data Understanding
1 Row: the house that is for sale
2 Column: the feature that qualifies the house

for example at rowindex 2: context
house 2 located in 140 CHARLES ST APT 4D in the city of New York (State NY) with a price of $1,650,000.0. It has 1 bedroom and a bathroom with a living space of 
718 ft2 (later in m2) 

## Feature Engineering
+ creating correlation plot

Feature                         -     Description

Price                                 reduce 10**3 to 1k    
Household income                      reduce to 1k          900 203 --> 900.02k dollar
Living Space                          convert to m2
Zip code population                   reduce to 1k

Possible Features
Price/living Space
Price/bedroom
Price/bathroom

## Exploratory Data Analysis
+ Plot distrbution graph for categorical and numerical variable
+ Possible correlation

Price <-> Population
