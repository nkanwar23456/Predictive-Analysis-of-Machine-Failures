# Predictive-Analysis-of-Machine-Failures
To develop a multi-label classification model that predicts specific machine failure types simultaneously using sensor data and machine parameters.

This project aims to predict multiple types of machine failures simultaneously using industrial sensor data. Unlike traditional binary classification (failure vs no-failure), this project uses multi-label classification to detect five specific failure types:

TWF – Tool Wear Failure

HDF – Heat Dissipation Failure

PWF – Power Failure

OSF – Overstrain Failure

RNF – Random Failure


Two ensemble machine learning algorithms were used:

Random Forest (Tuned)

Gradient Boosting


Both models were wrapped using MultiOutputClassifier to handle multi-label outputs.
