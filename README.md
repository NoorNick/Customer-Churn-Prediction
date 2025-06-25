# 📉 Customer Churn Prediction using Decision Tree Classifier

This repository contains a Python implementation of a **Decision Tree** model to predict customer churn based on various customer features such as tenure, monthly charges, contract length, support calls, and service issues.

---

## 🚀 Project Overview

- Uses a decision tree classifier to predict whether a customer will **churn (leave)** or **stay**.
- Visualizes the decision tree for interpretability.
- Evaluates model performance using confusion matrix and classification report.
- Ranks features by importance to understand key churn drivers.
- Predicts churn probabilities for new customers and suggests retention actions.

---

## 🛠️ How to Run

1. Clone the repository:

   ```
   git clone https://https://github.com/NoorNick/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
   ```
2. Install the required packages:

   ```
   pip install -r requirements.txt
   ```
3. Run the notebook
   If you have a Jupyter notebook (customer_churn.ipynb), launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
---
## 📊 What You Will See

- A graphical visualization of the trained decision tree.

- Confusion matrix and classification report evaluating the model.

- Feature importance ranked and plotted.

- Churn probability predictions for example new customers.

- Suggested retention actions based on risk level.
---
## 📋 Features Used in the Model
| Feature Name    | Description                                            |
| --------------- | ------------------------------------------------------ |
| Tenure (months) | How many months the customer has been with the company |
| Monthly Charges | Monthly billing amount                                 |
| Total Charges   | Total charges billed to date                           |
| Contract Length | 0 = month-to-month, 1 = one year, 2 = two year         |
| Support Calls   | Number of calls to customer support                    |
| Service Issues  | Number of service issues reported                      |

Happy predicting and retaining customers! 🎯


