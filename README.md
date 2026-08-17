# Customer Purchase Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a customer will purchase a product based on their **Age** and **Estimated Salary**.

Two Machine Learning classification algorithms are implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)

## 🎯 Objective

The objective is to predict customer purchase behavior:

- `0` → Customer will not purchase
- `1` → Customer will purchase

## 📊 Dataset

The dataset contains customer information such as:

- User ID
- Gender
- Age
- Estimated Salary
- Purchased

For model training:

- **Features:** Age, Estimated Salary
- **Target:** Purchased

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Machine Learning Workflow

Dataset → Data Preprocessing → Train-Test Split → Feature Scaling → Model Training → Prediction → Evaluation → Model Comparison

## 🤖 Models Used

### 1. Logistic Regression

Logistic Regression is used to classify customers into purchased and not-purchased categories.

**Accuracy: 86.25%**

### 2. K-Nearest Neighbors (KNN)

KNN predicts customer purchase behavior based on the nearest similar customers.

**K = 5**

**Accuracy: 91.25%**

## 📈 Model Comparison

| Model | Accuracy |
|---|---:|
| Logistic Regression | 86.25% |
| KNN | 91.25% |

Based on the current test dataset, **KNN performed better than Logistic Regression**.

## 🔮 Prediction

The trained models can predict whether a new customer is likely to purchase a product based on their:

- Age
- Estimated Salary

Example:

**Age:** 40  
**Estimated Salary:** 90,000

The model predicts either:

`0` → Not Purchased  
`1` → Purchased

## ⚠️ Limitations

- Only Age and Estimated Salary are currently used as features.
- Model performance is based on a single train-test split.
- Accuracy alone is not sufficient for complete classification evaluation.

## 🚀 Future Improvements

- Add Confusion Matrix
- Add Precision, Recall and F1-score
- Perform Cross-Validation
- Tune KNN parameters
- Compare Random Forest, Decision Tree and SVM
- Deploy the model using Streamlit

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
