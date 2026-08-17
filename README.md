# Customer Purchase Prediction

## 📌 Project Overview

This Machine Learning project predicts whether a customer will purchase a product based on customer information such as **Age** and **Estimated Salary**.

The project uses **Logistic Regression**, a supervised machine learning algorithm used for binary classification.

## 🎯 Objective

The main objective is to predict:

* `0` → Customer will not purchase
* `1` → Customer will purchase

## 📊 Dataset

The dataset contains customer information including:

* Age
* Estimated Salary
* Purchased

The `Purchased` column is used as the target variable.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Logistic Regression
   ↓
Prediction
   ↓
Model Evaluation
```

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression is used to classify customers into two categories:

* Purchased
* Not Purchased

The model uses:

**Features:**

* Age
* Estimated Salary

**Target:**

* Purchased

## 📈 Model Evaluation

The model performance is evaluated using classification metrics such as:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score

## 🔮 Prediction

The trained model can predict whether a new customer is likely to purchase a product based on their Age and Estimated Salary.

## ⚠️ Limitations

* The model uses a limited number of customer attributes.
* Purchase behavior can depend on many other factors.
* The model should be evaluated on new and unseen customer data before real-world use.

## 🚀 Future Improvements

* Add more customer features.
* Compare Logistic Regression with Random Forest, Decision Tree, and KNN.
* Perform cross-validation.
* Perform hyperparameter tuning.
* Add ROC-AUC analysis.
* Deploy the model using Streamlit.

## ▶️ How to Run

```bash
git clone https://github.com/YOUR_USERNAME/customer-purchase-prediction-ml.git
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open the project `.ipynb` file and run the cells.

## 👨‍💻 Author

**Chetan Shimpi**
B.Tech – Artificial Intelligence & Machine Learning
