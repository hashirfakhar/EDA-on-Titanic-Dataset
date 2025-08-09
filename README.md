# Task 1 - EDA on Titanic Dataset

## Objective
Analyze the Titanic passenger dataset to identify key factors influencing survival rates, and build a predictive model to estimate the likelihood of survival.

## Approach
- Loaded `train.csv` and `test.csv` datasets.
- Performed data cleaning: handled missing values in `Age`, `Embarked`, and `Fare` columns.
- Conducted Exploratory Data Analysis (EDA) with **seaborn** and **matplotlib**:
  - Survival rates by gender, passenger class, and age groups.
  - Distribution of fares and their relation to survival.
- Engineered new features:
  - Created categorical age groups.
  - Converted categorical variables into numerical codes.
- Trained a **Logistic Regression** model on the cleaned training dataset.
- Evaluated the model using **accuracy score** and **confusion matrix**.

## Results & Insights
- Women had significantly higher survival rates than men.
- The logistic regression model achieved 82.6% accuracy on the training set.
