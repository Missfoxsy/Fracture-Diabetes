# Fracture risk prediction in diabetes patients based on Lasso feature selection and Machine Learning
## Introduction
Fracture risk among individuals with diabetes poses significant clinical challenges due to the multifaceted relationship between diabetes and bone health. 
Diabetes not only affects bone density but also alters bone quality and structure, thereby increases the susceptibility to fractures. 
Given the rising prevalence of diabetes worldwide and its associated complications, accurate prediction of fracture risk in diabetic individuals has emerged as a pressing clinical need. 
This study aims to investigate the factors influencing fracture risk among diabetic patients. We propose a framework that combines Lasso feature selection with eight classification algorithms. 
Initially, Lasso regression is employed to select 24 significant features. 
Subsequently, we utilize grid search and 5-fold cross-validation to train and tune the selected classification algorithms, including KNN, Naive Bayes, Decision Tree, Random Forest, AdaBoost, XGBoost, Multi-layer Perceptron(MLP), and Support Vector Machine(SVM). 
Among models trained using these important features, Random Forest exhibits the highest performance with a predictive accuracy of 93.87\%. 
Comparative analysis across all features, important features, and remaining features demonstrate the crucial role of features selected by Lasso regression in predicting fracture risk among diabetic patients. Besides, by using a feature importance ranking algorithm, we find several features that hold significant reference values for predicting early bone fracture risk in diabetic individuals.
## Code Structure
-src
--/dataset5.xlsx
--/FeatureImportance.ipynb
--/FeatureSelectionMethods.ipynb
--/LassoParamsRelationship.ipynb
--/ReadMe.md
