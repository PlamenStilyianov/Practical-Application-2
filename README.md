# Practical-Application-2

**OVERVIEW**

In this application, we will explore a dataset from kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing.  Our goal is to understand what factors make a car more or less expensive.  As a result of our analysis, we should provide clear recommendations to our client -- a used car dealership -- as to what consumers value in a used car.


**Objectives:**

Predict the price of used cars, and what factors make a car more or less expensive.

**Test Results:**
1. The script runs 20 random samples with our prediction model (Linear Regression)
2. It looks the predicted values are not accurate
3. The models need additional tuning or the criteria of the selected features do not fully explain the model

**Data issues and Model issues**
1. There were many NaN
2. Upto now only known models have been used
3. introduction of hyper-parameters tuning might be needed
4. Current model use only 5 features for prediction
5. The Normalized dataset has not been used yet, 
 6. the data distribution is a skewed right distribution  

**Recommendation**
1. Increase permutation feature importance
2. Tuning technics to be used in the regression models
3. Some advanced models have been used but the best results are from the simple regression model
4. The prediction models are  at experimental stage, but can be productionised by converting it to python code api library with gui and interface api