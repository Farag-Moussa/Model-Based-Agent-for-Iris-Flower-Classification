# Model-Based Agent for Iris Flower Classification 🌸🤖

## Overview
This project demonstrates a simple Model-Based AI Agent for classifying Iris flowers into three classes: Setosa, Versicolor, and Virginica.

The agent uses an internal state and rule-based decision logic based mainly on petal length, then compares its performance with traditional machine learning models.

## Dataset
The project uses the built-in Iris dataset from scikit-learn.

Features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Target classes:
- Setosa
- Versicolor
- Virginica

## Methodology
1. Load and explore the Iris dataset
2. Build a Model-Based Agent class
3. Define decision rules using petal length
4. Evaluate the agent using:
   - Accuracy
   - Classification report
   - Confusion matrix
5. Visualize:
   - Confusion matrix
   - Feature distributions
   - Decision boundaries
6. Compare the agent with:
   - Decision Tree Classifier
   - XGBoost Classifier

## Agent Decision Rules
```text
IF Petal Length < 2.0 cm     → Setosa
IF 2.0 ≤ Petal Length < 5.0  → Versicolor
IF Petal Length ≥ 5.0 cm     → Virginica
```


## 🤖 Models Compared
- Model-Based Agent  
- Decision Tree  
- XGBoost  

---

## 📈 Outputs
The notebook generates:
- Confusion Matrix  
- Feature Distributions  
- Decision Boundaries  
- Model Comparison  

---

## 🚀 How to Run

Install dependencies:

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
