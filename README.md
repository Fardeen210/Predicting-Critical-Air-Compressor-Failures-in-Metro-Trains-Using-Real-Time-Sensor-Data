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

# Models Used

1. Random Forest Classifier

Ensemble of decision trees

Handles nonlinear relationships and feature importance

2. Support Vector Machine (SVM)

Finds optimal boundary between classes

Effective in high-dimensional spaces

3. Logistic Regression

Interpretable linear classifier
