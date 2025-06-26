# 🦠 COVID Prediction using Symptoms (Decision Tree Classifier)

This project demonstrates how to predict whether a person is likely to have **COVID** based on symptoms like **Fever**, **Cough**, and **Headache**, using a **Decision Tree Classifier**. It’s a simple example to understand how machine learning models can assist in medical predictions.

---

## 🎯 Objective

To create a model that predicts the presence of COVID (`Yes` or `No`) using basic symptom inputs:
- Fever
- Cough
- Headache

---

## 📁 Dataset Description

A small sample dataset is created manually with 3 symptoms and the target result (COVID). Each value is labeled `Yes` or `No`.

| Fever | Cough | Headache | COVID |
|-------|-------|----------|--------|
| Yes   | Yes   | Yes      | Yes    |
| Yes   | No    | No       | No     |
| No    | Yes   | No       | No     |
| Yes   | Yes   | Yes      | Yes    |
| No    | No    | No       | No     |
| Yes   | Yes   | No       | Yes    |
| No    | Yes   | Yes      | Yes    |
| No    | No    | No       | No     |

---

## 🔧 Technologies Used

- **Python**
- **Pandas** – For data handling
- **scikit-learn** – For Decision Tree model
- **Matplotlib** – To visualize the decision tree

---

## 📊 Workflow Breakdown

### 🔹 Step 1: Import Required Libraries

```python
import pandas as pd
from sklearn.tree import DecisionTreeClassifier
from sklearn import tree
import matplotlib.pyplot as plt
