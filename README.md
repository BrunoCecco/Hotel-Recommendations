# Hotel Recomendations Overview

Machine Learning project created to recommend hotels to customers for companies like Expedia.

Project covers: 
  - Breakdown Problem Statement
  - EDA & database cleaning
  - Univariate & bi-variate analysis for numeric and categorical variables
  - Feature engineering and selection
  - Prepare data for modelling
  - Create models using multiple algorithms with hyperparameter tuning
  - Compare the performance of different models using jaccard_score

## Problem Statement

Planning a vaction with thousands of options is hard! This project aims to use customer data to predict the likelihood a user will stay at 100 different hotel groups.

The data in this competition is a random selection from Expedia and is not representative of the overall statistics.

## Code and resources used
**Python Version:** 3.7

**Packages:** Pandas / Numpy / Seaborn / Scikitlearn

**ML Resources:** Logistic Regression / Gradient Boosting / Cross-validation / AUC / ROC / Confusion Matrix

## Model Building

Given that all models tried were performing quite low, I tried several algorithms.

- Random Forests
- Naive Bayes
- Logistic Regression
- KNN
- XGBoost
- Decision Tree

## Model Performance

The Jaccard similarity index compares members for two sets to see which members are shared and which are distinct. It’s a measure of similarity for the two sets of data, with a range from 0% to 100%. The higher the percentage, the more similar the two populations. Although it’s easy to interpret, it is extremely sensitive to small samples sizes and may give erroneous results, especially with very small samples or data sets with missing observations.

<img width="819" alt="image" src="https://github.com/BrunoCecco/Hotel-Recommendations/assets/34370581/37b27ecd-7732-4ca1-89fb-15db55e02386">
