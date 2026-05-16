# Customer Cross-sell Propensity Model

Predicting which bank customers are likely to subscribe to a second financial product using machine learning.

## Dataset
UCI Bank Marketing Dataset — 41,188 real customer records from a Portuguese bank.

## Results
| Approach | AUC-ROC | F1 |
|---|---|---|
| Logistic Regression (baseline) | 0.759 | 0.400 |
| XGBoost + SMOTE (default) | 0.781 | 0.485 |
| XGBoost + GridSearch (best) | 0.817 | 0.535 |

## Techniques Used
- SMOTE for class imbalance (11% positive class)
- Threshold tuning to optimise F1
- GridSearchCV across 54 hyperparameter combinations

## How to Run
Open in Google Colab — all cells run top to bottom, dataset loads automatically.

## Skills Demonstrated
Python · scikit-learn · XGBoost · imbalanced-learn · pandas · matplotlib
