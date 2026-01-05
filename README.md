# Titanic Survival Prediction: A Comparative ML Study
This project explores the classic Titanic dataset to predict passenger survival. 
I implemented and tuned several Machine Learning models, ranging from simple decision tree algorithms to advanced Gradient Boosting frameworks.

## 🚀 Project Overview
The goal of this project was to move beyond basic classification and understand how different algorithms—specifically Decision Tree, Random Forest, XGBoost, and LightGBM—handle tabular data with mixed features.

## 📊 Dataset
The data is sourced from DPhi's Titanic Dataset. It contains information about 891 passengers, including:Features: Passenger Class, Sex, Age, SibSp, Parch, Fare, and Embarked.Target: Survived (0 = No, 1 = Yes).

## 🛠️ Models & Performance
I utilized GridSearchCV with 10-fold cross-validation to optimize hyperparameters for each model.

Model,Accuracy (Cross-Val),Status

LightGBM,84.72%,🏆 Best Performer

XGBoost,84.58%,Runner Up

Random Forest,~83.06%,Very Stable

Decision Tree,~81.88%,Baseline
