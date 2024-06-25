## **Bike Sharing Assignment**

* A bike-sharing system is a service in which bikes are made available for shared use to
individuals on a short-term basis for a price or free. Many bike share systems allow people to
borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the
payment information, and the system unlocks it. This bike can then be returned to another
dock belonging to the same system.

* A US bike-sharing provider BoomBikes has recently suffered considerable dips in their
revenues due to the ongoing Corona pandemic. The company is finding it very difficult to
sustain in the current market scenario. So, it has decided to come up with a mindful business
plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end,
and the economy restores to a healthy state

* They have contracted a consulting company to understand the factors on which the
demand for these shared bikes depends. Specifically, they want to understand the
factors affecting the demand for these shared bikes in the American market. The
company wants to know:
    1. Which variables are significant in predicting the demand for shared bikes.
    2. How well those variables describe the bike demand

## Table of Contents

**Steps used to find the solution:** 

To analyze and model the demand for shared bikes,I have followed below steps:

**Step 1: Data Preparation**

Convert numerical categorical features to string values as specified.
Analyze the dataset to understand the distribution and relationships between variables.

**Step 2: Exploratory Data Analysis (EDA)**

Visualize the data to understand the patterns and relationships.
Identify significant variables affecting bike demand.

**Step 3: Model Building**

Split the data into training and test sets.
Build a regression model to predict the cnt (total bike rentals).
Evaluate the model using appropriate metrics like R-squared.

**Step 4: Model Evaluation**

Calculate the R-squared score on the test set to evaluate the model's performance.

**Final Model R-squared**

OLS Regression Results
Dep. Variable:	y	R-squared:	0.805
Model:	OLS	Adj. R-squared:	0.800
Method:	Least Squares	F-statistic:	186.9
Date:	Sun, 23 Jun 2024	Prob (F-statistic):	4.89e-169
Time:	23:20:32	Log-Likelihood:	-4175.4
No. Observations:	511	AIC:	8375.
Df Residuals:	499	BIC:	8426.
Df Model:	11		
Covariance Type:	nonrobust		

**Interpretation:**

The model is statistically significant as indicated by the F-statistic and its corresponding p-value.
The high R-squared value suggests a good fit of the model to the data.
Variables like yr, workingday, atemp, and certain weather conditions have significant effects on the dependent variable.
Coefficients provide insight into the direction (positive or negative) and magnitude of the relationships between the independent variables and the dependent variable.
The confidence intervals provide a range of plausible values for the coefficients, allowing for an assessment of their precision.

**Conclusion:**

The regression analysis indicates that the model explains a substantial portion of the variance in the dependent variable and identifies significant predictors that influence the outcome.
These findings can be used for further analysis, interpretation, and decision-making based on the dataset.¶


## Technologies Used
- statsmodels-0.14.20
- sklearn 1.5.0
- Python 3.11.2

## Contact
Created by [@Rashmi-Bharti] - feel free to contact me!
