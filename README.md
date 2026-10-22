# Telecom Customer Churn Prediction Using Ensemble Machine Learning

## Project Overview

This project predicts whether a telecom customer is likely to leave the company's services using Machine Learning classification algorithms.

The project compares Random Forest and XGBoost classifiers and evaluates their performance using cross-validation and multiple classification metrics.

## Objectives

* Load and explore the Telco Customer Churn dataset.
* Clean the data and convert `TotalCharges` into numeric format.
* Handle missing values.
* Encode categorical features using OneHotEncoder.
* Address class imbalance using class weighting.
* Train Random Forest and XGBoost classifiers.
* Perform 5-fold stratified cross-validation.
* Evaluate models using ROC-AUC, accuracy, precision, recall and F1-score.
* Visualize ROC curves and confusion matrices.
* Identify the top 10 features for each model.

## Dataset

**Source:** [IBM Telco Customer Churn Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

The dataset contains customer information, subscribed services, account details, charges and churn status.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

## Machine Learning Algorithms

### 1. Random Forest Classifier

Combines predictions from multiple decision trees to perform classification.

### 2. XGBoost Classifier

Uses gradient boosting to build an ensemble of decision trees.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* 5-Fold Cross-Validation

## Project Structure

```text
telecom-customer-churn-prediction/
├── telecom_customer_churn_ensemble.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run the notebook cells in order.
5. Review the model comparison and evaluation charts.

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Results

The notebook compares Random Forest and XGBoost using cross-validation and test-set evaluation.

The target ROC-AUC is greater than 0.80. Actual performance must be confirmed by running the notebook.

## Conclusion

This project demonstrates a Machine Learning workflow for telecom customer churn prediction, including data preprocessing, class imbalance handling, ensemble classification, model evaluation and feature importance analysis.
