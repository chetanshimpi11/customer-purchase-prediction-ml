Customer Purchase Prediction using Machine Learning

📌 Project Overview

This project predicts whether a customer is likely to purchase a product based on their Age and Estimated Salary.

The same customer dataset is used to build and compare two supervised machine learning classification models:

Logistic Regression

K-Nearest Neighbors (KNN)

The project follows a complete machine learning workflow including data loading, data cleaning, feature selection, train-test splitting, feature scaling, model training, prediction, and accuracy evaluation.

🎯 Objective

The main objective is to classify customers into two categories:

0 → Customer is predicted not to purchase

1 → Customer is predicted to purchase

This helps demonstrate how customer demographic and financial attributes can be used for purchase prediction.

📊 Dataset

The dataset contains 400 customer records and 5 columns:

Column

Description

User ID

Unique customer identifier

Gender

Customer gender

Age

Customer age

EstimatedSalary

Estimated customer salary

Purchased

Purchase outcome / target variable

There are no missing values in the dataset.

For model training, Age and EstimatedSalary are used as input features, while Purchased is the target variable.

User ID and Gender are not used in the current model.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🔄 Machine Learning Workflow

Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Missing Value Check
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Standard Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Accuracy Evaluation
   ↓
Model Comparison

⚙️ Data Preprocessing

The dataset is divided into:

Features:

Age

Estimated Salary

Target:

Purchased

The data is split into:

80% Training Data → 320 records

20% Testing Data → 80 records

StandardScaler is applied to the features after the train-test split. This is especially important for KNN because KNN is a distance-based algorithm.

🤖 Models Used

1. Logistic Regression

Logistic Regression is used as a classification model to predict the probability of a customer belonging to either the purchased or not-purchased class.

Test Accuracy: 86.25%

2. K-Nearest Neighbors (KNN)

KNN predicts the class of a new customer based on the classes of its nearest neighboring customers.

The notebook uses:

KNeighborsClassifier(n_neighbors=5)

Test Accuracy: 91.25%

📈 Model Comparison

Model

Test Accuracy

Logistic Regression

86.25%

KNN (K=5)

91.25%

Based on the current test split, KNN performed better than Logistic Regression.

The KNN model achieved an accuracy that is 5 percentage points higher than Logistic Regression on this particular test set.

Note: These results are based on one 80/20 train-test split with random_state=42. Accuracy can vary with different splits, so cross-validation would provide a more robust comparison.

🔮 Prediction

The trained model can be used to predict whether a new customer is likely to purchase a product based on:

Age

Estimated Salary

Example input:

Age: 40
Estimated Salary: 90000

The model returns a binary prediction:

0 → Not Purchased
1 → Purchased

⚠️ Limitations

The current model uses only Age and Estimated Salary.

Gender is available in the dataset but is not included in the current model.

User ID is an identifier and is not used as a predictive feature.

The evaluation is based on a single train-test split.

Accuracy alone does not provide a complete picture of classification performance.

🚀 Future Improvements

Add confusion matrix analysis.

Calculate Precision, Recall, and F1-score.

Add ROC-AUC evaluation.

Use Stratified K-Fold Cross-Validation.

Tune the KNN n_neighbors parameter.

Compare additional models such as Decision Tree, Random Forest, SVM, and Naive Bayes.

Create a model comparison visualization.

Deploy the best-performing model using Streamlit.

Save the trained model and scaler using Joblib.

▶️ How to Run

1. Clone the repository

git clone https://github.com/YOUR_USERNAME/customer-purchase-prediction-ml.git

2. Navigate to the project

cd customer-purchase-prediction-ml

3. Install dependencies

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

4. Start Jupyter Notebook

jupyter notebook

Open the project .ipynb file and run the cells.


👨‍💻 Author
Chetan Shimpi
chetanshimpi49@gmail.com
Chetan Shimpi

B.Tech – Artificial Intelligence & Machine Learning
