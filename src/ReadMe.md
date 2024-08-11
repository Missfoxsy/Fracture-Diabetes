# Usage of each file
## 1. FeatureSelectionMethods.ipynb
This file is used to compare three different feature selection methods to explore which one is the most suitable for our research. Results indicates that Lasso Regression can improve the performance of our models to the greatest extend.

## 2. LassoParamsRelationship.ipynb
This file is used to investigate the relationship between the alpha parameter and the regression coefficients (beta) in the context of the Lasso Regression algorithm. It also delves into how alpha influences the training error. The purpose is to substantiate the critical importance of selecting an appropriate alpha parameter in our experiments, as it significantly impacts the overall framework's performance.

## 3. FeatureImportance.ipynb
This document serves multiple analytical purposes in evaluating various models:

1. Performance Metrics Calculation
   It calculates key metrics such as precision, recall, F1-score, accuracy, and Area Under the Curve (AUC) for different models.
   
2. Timing Analysis
  The document also records the execution time for each model.

3. Feature Importance Assessment
   It computes the importance of features used by the models.
   
4. Visualization of Results
   The document includes graphical representations of model performance. Specifically, it plots Receiver Operating Characteristic (ROC) curves for each model. Additionally, it provides visualizations of feature importance over the course of model training.

## 4. dataset5.xlsx
This file contains a preprocessed dataset specifically detailing information about diabetic patients. It comprises records of 1682 individuals diagnosed with diabetes, each profiled across 85 distinct features.
