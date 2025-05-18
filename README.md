#Prodigy Infotech Internship - Task 3

## Project: Customer Purchase Prediction using Decision Tree Classifier

This project builds a **Decision Tree Classifier** to predict whether a customer will subscribe to a bank term deposit.  
The model is trained on the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

---

## Dataset

We used `bank-additional-full.csv`, which contains:

- 41,188 customer records
- 20 input features + 1 output (`y`)
- Categorical and numerical variables

📌 Dataset Source: [UCI Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

---

## ⚙️ Tools and Libraries

- Python
- Google Colab
- pandas, seaborn, matplotlib
- scikit-learn

---

##  Steps Implemented

1. Load dataset and clean data
2. Drop `duration` column (to avoid data leakage)
3. Encode categorical variables
4. Split data into training and test sets
5. Train Decision Tree using `entropy` criterion
6. Evaluate accuracy, precision, recall, F1
7. Visualize tree and feature importance

---

## Model Results

- **Accuracy**: ~88%
- **Visualization**: Tree and feature importance shown
- **Best Features**: `emp.var.rate`, `euribor3m`, `nr.employed`

---

## Screenshots

| Decision Tree | Feature Importance |
|---------------|--------------------|
| ![Image](https://github.com/user-attachments/assets/f01a3120-22a7-450b-bef3-d185e03b29a5) | ![Features](https://github.com/user-attachments/assets/a3310292-f920-4390-8b21-998274ff6031) |

---

## 🚀 Run This Project

### Run on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15RIYh_aPBPyvKYjEFrl5eGzhKK1GdClN)
