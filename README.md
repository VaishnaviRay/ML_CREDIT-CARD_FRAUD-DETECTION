# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project applies Machine Learning techniques to detect fraudulent credit card transactions.

The dataset is highly imbalanced, containing very few fraud transactions compared to legitimate transactions. To address this issue, SMOTE (Synthetic Minority Oversampling Technique) was used before model training.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)

---

## Dataset

Credit Card Fraud Detection Dataset

Features:
- Time
- Amount
- V1 to V28 anonymized features
- Class (Target)

Target:
- 0 → Legitimate Transaction
- 1 → Fraudulent Transaction

---

## Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Feature Scaling
4. Train-Test Split
5. SMOTE Oversampling
6. Model Training
7. Model Evaluation
8. Comparison of Models
9. Best Model Selection

---

## Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- AdaBoost
- XGBoost

---

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 97.43% |
| Decision Tree | 99.70% |
| Random Forest | 99.95% |
| KNN | 99.81% |
| AdaBoost | 97.18% |
| XGBoost | 99.72% |

### Best Model

Random Forest

Accuracy: 99.95%

Precision: 0.86

Recall: 0.82

F1 Score: 0.84

---

## Project Structure

```text
notebooks/
models/
reports/
images/
```

---

## Author

Shubham Shaw
ECE Undergraduate
Machine Learning & VLSI Enthusiast
