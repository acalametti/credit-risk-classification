# credit-risk-classification

# Contributors

Alex Calametti

## Overview

The goal of this project is to perform a credit risk classification using logistic regression. It utilizes machine learning techniques to predict whether a loan is healthy (`0`) or high-risk (`1`) based on the given features. A report of the classification results is also included in the repository. 

## Programs and files

- Scikit-learn
- Numpy
- Pandas
- credit_risk_classification.ipynb
- lending_data.csv

### Part 1: Split the Data into Training and Testing Sets

1. Read the `lending_data.csv` data from the `Resources` folder into a Pandas DataFrame.
2. Create labels set (`y`) and features DataFrame (`X`).
3. Check the balance of the labels variable (`y`).
4. Split the data into training and testing datasets using `train_test_split`.

### Part 2: Create a Logistic Regression Model with the Original Data

1. Fit a logistic regression model using the training data (`X_train` and `y_train`).
2. Save predictions on the testing data labels using the fitted model.
3. Evaluate the model’s performance by calculating accuracy, generating a confusion matrix, and printing the classification report.

### Part 3: Predict a Logistic Regression Model with Resampled Training Data

1. Use the `RandomOverSampler` to resample the data for balanced labels.
2. Fit a logistic regression model using the resampled training data.
3. Evaluate the model’s performance after resampling by calculating accuracy, generating a confusion matrix, and printing the classification report.

## Results and Conclusion

The results and conclusion of this project can be found in the repository in file `credit_classification_report.txt`

## Useful Links

Used to learn more about oversampler: https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/
