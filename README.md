# Loan Approval Prediction using Machine Learning

A supervised machine learning project that predicts whether a loan application will be approved or rejected based on applicant details such as income, education, employment status, CIBIL score, loan amount, and asset information.

---

# Project Overview

The objective of this project is to build and evaluate machine learning classification models that can assist financial institutions in automating loan approval decisions and reducing financial risk.

The project includes:

* Data preprocessing
* Feature engineering
* Model training
* Cross-validation
* Model evaluation
* Flask web deployment
* Interactive prediction interface

---

# Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Train-test split
* Cross-validation
* Multiple model comparison
* Performance evaluation using classification metrics
* Confusion matrix and ROC-AUC analysis
* Flask web application
* Interactive frontend UI
* Real-time loan prediction system

---

# Machine Learning Algorithms Used

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

# Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

# Technologies Used

* Python
* Flask
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* HTML/CSS
* Jupyter Notebook

---

# Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Data Visualization
5. Train-Test Split
6. Cross Validation
7. Model Training
8. Model Evaluation
9. ROC Curve and Confusion Matrix
10. Model Comparison
11. Model Deployment using Flask
12. Prediction System
13. Final Conclusions

---

# Dataset Features

The model uses the following features:

* Number of Dependents
* Education
* Self Employment Status
* Annual Income
* Loan Amount
* Loan Term
* CIBIL Score
* Residential Asset Value
* Commercial Asset Value
* Luxury Asset Value
* Bank Asset Value

---

# Results

The machine learning models were successfully trained and evaluated on the loan approval dataset.

Among all models, the Random Forest Classifier achieved the best overall performance with the highest accuracy and ROC-AUC score.

The deployed Flask application allows users to enter applicant details and receive instant loan approval predictions with confidence scores.

---

# Application Screenshots

## Home Page

![Home Page](screenshots/home_page.png)

## Sample Input

![Sample Input](screenshots/sample_input.png)

## Loan Approved Prediction

![Loan Approved](screenshots/loan_approved.png)

## Loan Rejected Prediction

![Loan Rejected](screenshots/loan_rejected.png)

---

# Repository Structure

```text
Loan-Approval-Prediction-ML/
│
├── app.py
├── model.pkl
├── scaler.pkl
├── columns.pkl
├── loan_approval_prediction.ipynb
├── loan_approval_dataset.csv
├── requirements.txt
├── README.md
├── templates/
│   └── index.html
└── screenshots/
```

---

# Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd Loan-Approval-Prediction-ML
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

# Model Deployment

The project uses Flask for deployment.

The backend loads:

* Trained machine learning model
* Scaler object
* Feature columns

and performs real-time loan prediction based on user input.

The frontend interface is built using HTML and CSS for user interaction and prediction visualization.

---

# Future Improvements

* Hyperparameter tuning using GridSearchCV
* Streamlit deployment
* Cloud deployment using Render or Heroku
* Improved UI/UX design
* Integration with real financial datasets
* Authentication system for users

---

# Conclusion

This project successfully demonstrates the implementation of supervised machine learning techniques for loan approval prediction.

By comparing multiple classification algorithms and evaluating them using various performance metrics, the project identifies the most effective model for financial decision-making tasks.

The Flask deployment and interactive user interface further enhance the practical usability of the system.
