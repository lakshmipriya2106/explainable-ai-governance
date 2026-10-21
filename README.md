# Explainable AI for Responsible AI Governance

## Project Overview

This project investigates how Explainable Artificial Intelligence (XAI) can support responsible AI governance in information systems.

The prototype uses the UCI Adult Census Income dataset to examine model performance, explainability, demographic fairness, and auditability.

## Objectives

- Train a machine-learning classifier for income-category prediction.
- Explain model predictions using SHAP.
- Evaluate differences in prediction outcomes and error rates across demographic groups.
- Develop an audit logging and governance reporting workflow.

## Dataset

UCI Adult Census Income Dataset: https://archive.ics.uci.edu/dataset/2/adult

The dataset contains historical US Census records. It is used for research and educational evaluation, not for consequential real-world decisions.

## Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- SHAP
- Matplotlib
- Google Colab

## Methodology

1. Data inspection and preprocessing
2. Random Forest model training
3. Predictive performance evaluation
4. SHAP-based global and individual explanations
5. Fairness evaluation by demographic group
6. Audit logging and governance reporting

## Responsible AI Considerations

SHAP explanations describe model behavior and do not establish causation. Fairness metrics are diagnostic indicators, not proof of the absence of discrimination. The historical dataset may reflect existing social inequalities.

## Reproducibility

The notebook documents the experimental workflow. Run its cells in sequence in Google Colab after installing the required dependencies.

## Research Status

Educational research prototype. Results and limitations should be documented before drawing conclusions.
