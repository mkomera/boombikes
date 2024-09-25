# Boom Bikes Sharing Case Study
> A study on the Linear Regression model for BoomBikes, a US bike-sharing service.

## Table of Contents:
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Glossary](#glossary)


## Problem Statement
BoomBikes, a US bike-sharing provider, has faced significant revenue drops due to the COVID-19 pandemic. To regain stability, they plan to develop a business strategy based on understanding the demand factors for shared bikes in the American market. They aim to identify key variables affecting bike demand and their predictive power, utilizing a dataset on daily bike usage influenced by various factors.

## Objectives
The goal is to model bike demand using available variables, helping management understand how demand varies and adjust strategies accordingly. The model will also aid in grasping demand dynamics in new markets. The [Bike Sharing dataset](./day.csv) and [Data dictionary](./Data%20dictionary.txt) are available for reference.

## Approach
1. Import Libraries
2. Load and Understand Data
3. Clean Data and Check for Missing Values
4. Segment Columns
5. Conduct Exploratory Data Analysis (EDA)
   - Univariate, Bivariate, and Multivariate Analysis
6. Prepare Data (One Hot Encoding)
7. Train-Test Split
8. Scale Features
9. Build Initial Linear Model
10. Select Features
11. Build Models with Selected Features
12. Analyze Residuals
13. Make Predictions with Final Model
14. Refine and Optimize Model
15. Evaluate Model

## Technologies Used
- **Libraries**: numpy, pandas, seaborn, matplotlib, statsmodels, sklearn, scipy, IPython, Jupyter, etc.

## Conclusions
**Key Findings from EDA**:
- Bike rentals peak in summer and fall, with lower counts in spring and winter.
- 2019 saw an increase in rentals compared to 2018.
- Missing data for severe weather affects analysis.
- Rentals are higher on weekdays and non-holidays, with clear weather correlating to more rentals.
- Strong positive correlations exist between temperature and bike usage, as well as between registered users and rentals.

**Significant Variables in Predicting Demand**:
- The model explains 84.48% of training and 80.51% of test set variance, indicating a good fit.
- Higher temperatures and the year 2019 significantly boost demand.
- Adverse weather conditions, high wind speeds, and humidity negatively affect usage.
- Seasonal and monthly trends show higher demand in certain months and weekdays.

## Glossary
- Data Visualization, EDA, Feature Scaling, Dummy Variable, Linear Regression, p-value, R², MSE, Cross-Validation, Multicollinearity, Residuals Analysis.

