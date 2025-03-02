# Naïve Bayes Classification on Social Network Ads Dataset

## Overview

This repository contains an implementation of the **Naïve Bayes Classification** algorithm to predict whether a user will purchase a product based on their **Age** and **Estimated Salary**. The dataset used is **Social\_Network\_Ads.csv**.

## Dataset

The dataset consists of 400 observations with the following columns:

- **Age**: Age of the user.
- **EstimatedSalary**: Estimated salary of the user.
- **Purchased**: Target variable (1 = Purchased, 0 = Not Purchased).


## Implementation Steps

1. Load the dataset using Pandas.
2. Preprocess the data:
   - Split into training and testing sets.
   - Apply feature scaling using `StandardScaler`.
3. Train a **Naïve Bayes** classifier using `GaussianNB` from `sklearn`.
4. Evaluate the model's performance using accuracy metrics.

# Evaluate model
accuracy = accuracy_score(y_test, y_pred)
print(f'Accuracy: {accuracy * 100:.2f}%')
```
## Results
The trained Naïve Bayes model predicts whether a user will purchase a product with an accuracy of approximately **90%** (replace with actual value after running the model).



