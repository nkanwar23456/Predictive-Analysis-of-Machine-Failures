# Predictive-Analysis-of-Machine-Failures
To develop a multi-label classification model that predicts specific machine failure types simultaneously using sensor data and machine parameters.
📁 Machine-Failure-Prediction
│
├── 📄 dataset/
│   └── machine failure.csv
│
├── 📄 src/
│   └── model_training.ipynb  # Main code (data processing, training, evaluation)
│
├── 📄 results/
│   ├── correlation_heatmap.png
│   ├── model_comparison_heatmap.png
│   └── classification_reports.txt
│
├── 📄 README.md  # Project Documentation
└── 📄 requirements.txt
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
