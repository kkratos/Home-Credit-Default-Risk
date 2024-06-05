# Home Credit Default Risk

## Problem Statement

Home Credit Group is an international non-bank financial institution founded in 1997 in czech republic that focuses on installment lending primarily to people with little or no credit history. As of 2020 the group have served over 135.4 million customers.

Many people struggle to get loan due to insufficient or non-existent credit histories. Unfortunately, this population is often taken advantage by untrustworthy lenders. So home credit strives to include financial support for this unbanked population providing safe and positive borrowing experience. Their aim is to use alternative data like previous loan info, credit card info, transactional information and other financial history data to predict clients repayment abilities.

The problem definition and the project data are hosted on Kaggle. You can find more information [here](https://www.kaggle.com/c/home-credit-default-risk/data).

## Project Development:
*  Investigated the dataset to identify missing values and outlier. Visualized relationships between variables to find any patterns or anomalies within the dataset.
*  Preprocessed missing data using imputation startegies, encoded variables and standardize features as necessary.
*  Built baseline classification model using Logistic Regression, Decision Tree, Random Forest and then built improved models using boosting techniques such as (XGBoost, LGBM) and performed hyperparameter tuning using sciket-learn, pycart and AutoGluon libraries.
*  Interpreted model performance using metrics such as accuracy, precision, ROC, AUC etc.
