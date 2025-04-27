# Predicting Critical Air Compressor Failures in Metro Trains Using Real-Time Sensor Data

This project focuses on the analysis of an air compressor sensor dataset and the application of supervised machine learning techniques for predictive maintenance.  The dataset includes sensor readings, operational parameters, and failure event logs over several months. The goal is to detect and predict failure events (specifically air leaks) to minimize downtime and improve operational reliability.


# Dataset Description

Source: Air compressor telemetry logs from February to September 2020

Records: 1,516,948 rows

Columns: 17 features including pressure, temperature, current, binary sensors, etc.

Failure Reports: Provided for 4 failure events, used to label failure periods

# Objectives

Visualize sensor behavior during normal and failure periods

Engineer failure labels based on provided event logs

Train and evaluate supervised machine learning models

Compare model performances using ROC and PR metrics

# Data Preprocessing

Converted timestamp to datetime

Created binary labels (failure = 1, normal = 0)

Extracted failure and normal samples to build a balanced training set

Features used: sensor measurements and binary sensor signals

# Models Experimented

1. Random Forest Classifier
2. Support Vector Machine (SVM)
3. Logistic Regression
4. K- Nearest Neighbour
5. ADA Boost.

# Results:
Out of al 5 models, we recived better results in Random Forest Classifier.

Model : Accuracy
Logistic Regression 0.985
KNN : 0.995
AdaBoost: 0.991
Decision Tree: 0.996
Random Forest : 0.998

# Conclusion:
Random Forest and Decision Tree are the best models for our research questions because they both reached very high accuracy
They are best because they can handle complex sensor data, find important features like pressure and motor current trends, and make accurate predictions even when operating conditions change


