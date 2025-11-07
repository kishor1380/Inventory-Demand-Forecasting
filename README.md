# Inventory-Demand-Forecasting
This project builds a demand forecasting model using XGBoost and adds a classification layer to convert numeric predictions into actionable stock decisions. The model evaluates its decision quality using standard classification metrics.

##Project Overview

*Uses XGBoost regression to predict item-level demand.
*Converts regression outputs into binary decisions using a configurable threshold.
*Evaluates decision performance with Accuracy, Precision, Recall, and F1 Score.
*Generates reorder recommendations with safety-factor logic.
*Saves results to a structured CSV file for downstream use.

##Key Results
*MAE: 6.28
*RMSE: 8.15
*Accuracy: 92.7%
*Precision: 92.4%
*Recall: 94.0%
*F1 Score: 93.2%

##Tech Stack

*Python
*Pandas
*NumPy
*Scikit-learn
*XGBoost
*Jupyter Notebook
*CSV Pipeline

##Repository Structure
.
├── README.md
├── notebooks/
│   └── classification.ipynb
└── data/
    └── sample.csv   (optional)

How to Run

*Open the classification.ipynb notebook in Jupyter or Google Colab
*Run all cells in order.
*Review the generated metrics and the CSV output.

##Features

*Demand forecasting using gradient boosting.
*Threshold-based classification for decision making.
*Automated reorder recommendation logic.
*Exportable results for integration into other workflows.
