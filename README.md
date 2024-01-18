#### Home Credit Default Risk

**Can you predict how capable each applicant is of repaying a loan?**

This was an individual project completed as part of the Data Mining II course in Industrial and Systems Engineering department  at Rutgers University in the Fall of 2023.

#### Problem Statement

Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders. Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. To make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information to predict their clients' repayment abilities.

The problem definition and the project data are hosted on Kaggle. You can find more information [here](https://www.kaggle.com/c/home-credit-default-risk/data).

#### Project Development:
1.	**Extensive Exploratory Analysis**: Investigated the dataset to identify missing values and outlier. Visualized relationships between variables to find any patterns or anomalies within the dataset.
2.	**Preprocessing the Data**: dealt with missing data using imputation startegies, encode variables and standardize features as necessary.
3.	**Implementation of the Model**: Built baseline classification model algorithms such as (Logistic Regression, Decision Tree, Random Forest etc.) and then built improved models using boosting techniques such as (XGBoost, LGBM) and performed hyperparameter tuning using sciket-learn, pycart and AutoGluon libraries
4.	**Evaluation**: Interpreted model performance using metrics such as accuracy, precision, ROC, AUC etc.
