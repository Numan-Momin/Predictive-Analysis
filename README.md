# Predictive Analysis – Machine Learning Classification

## 📌 Overview

This project demonstrates the practical implementation of **Machine Learning classification techniques**, including data preprocessing, model training, prediction, and performance evaluation.

The notebook works with classification datasets and demonstrates how machine learning models can be trained and compared using standard evaluation techniques.

## 🎯 Objectives

* Perform basic data preprocessing
* Handle missing values
* Convert categorical data into numerical form
* Split data into training and testing sets
* Train classification models
* Generate predictions
* Evaluate model performance
* Compare ensemble learning techniques

## 📊 Datasets

### Diabetes Dataset

The notebook uses a diabetes dataset containing features such as:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age
* Outcome

The classification model achieved an accuracy of approximately **72.08%** in the demonstrated run.

### Loan Approval Dataset

The notebook also demonstrates ensemble classification using a loan approval dataset containing features related to:

* Applicant age
* Gender
* Education
* Income
* Employment experience
* Home ownership
* Loan amount
* Loan intent
* Interest rate
* Credit history
* Credit score
* Previous loan defaults

The target variable is `loan_status`.

## 🤖 Machine Learning Models

The project demonstrates:

### Random Forest – Bagging

A `RandomForestClassifier` with 100 estimators is trained on the loan approval dataset.

**Accuracy:** 92.87%

### AdaBoost – Boosting

An `AdaBoostClassifier` with 100 estimators is also trained and evaluated.

**Accuracy:** 90.89%

## 🔄 Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Missing Value Handling
   ↓
Categorical Encoding
   ↓
Feature & Target Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Accuracy & Confusion Matrix
```

## 📈 Evaluation Metrics

The project uses:

* Accuracy Score
* Confusion Matrix
* Classification Report

These metrics are used to understand how effectively the models classify observations.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook / Google Colab
* KaggleHub

## 📂 Project Structure

```text
Predictive-Analysis/
│
├── Predictive_Analysis.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Predictive_Analysis.ipynb`.
3. Run the notebook using:

   * Jupyter Notebook
   * JupyterLab
   * Google Colab
4. Install the required Python libraries if necessary.
5. Execute the cells sequentially.

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Classification workflow
* Data preprocessing
* Categorical feature encoding
* Train-test splitting
* Random Forest
* AdaBoost
* Ensemble learning
* Model evaluation
* Confusion matrix interpretation

## 📌 Results

| Model                   | Dataset       | Accuracy |
| ----------------------- | ------------- | -------: |
| Classification Model    | Diabetes      |   72.08% |
| Random Forest (Bagging) | Loan Approval |   92.87% |
| AdaBoost (Boosting)     | Loan Approval |   90.89% |

*Results shown are from the executed notebook and may vary depending on the dataset version and execution environment.*

## 👨‍💻 Author

**Numan Momin**

This project was created as part of practical learning in **Machine Learning and Data Analytics**.

