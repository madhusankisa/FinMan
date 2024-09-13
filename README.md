## Project Summary:
### Objective: Develop a predictive model to identify customers most likely to respond positively to insurance offers. The primary goal is to allocate marketing resources more efficiently and personalize policy offerings based on customer profiles.
### Data Overview:
Dataset: Contains 50,882 records with attributes like customer demographics, policy details, and responses to insurance recommendations.
#### Key Features:
Customer demographics (e.g., city code, age, health indicators)
Policy details (e.g., policy type, duration, premium)
Response variable (whether the customer responded positively to the offer)
#### Data Preparation:
Duplicates were removed, and missing values were imputed for key features.
New features like 'Customer Type' and 'Age Confidence Interval' were created, and log transformations were applied where necessary.
#### Exploratory Data Analysis:
Insights were gained through visualizations like:
Age vs. Response: Older customers were more likely to respond positively.
Premium Distribution: Higher premiums generally correlated with lower response rates.
Health Indicators: Specific health conditions showed a strong correlation with positive responses.
#### Modeling Approach:
#### Five models were used:
##### Logistic Regression
##### K-Nearest Neighbors (KNN)
##### Support Vector Machine (SVM)
##### Random Forest
##### Gradient Boosting Classifier (which performed the best with an AUC-ROC score of 0.5975)
#### Key Insights:
Targeted Marketing: Identified segments that are more responsive to offers.
Policy Optimization: Adjusted policies based on predicted customer behavior.
Health Data: Incorporated health indicators as a key predictor of customer responses.
