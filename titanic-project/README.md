# Titanic Survival Predictor

Project Overview

The **Titanic Survival Predictor** is a machine learning project that analyzes passenger data from the Titanic disaster to predict whether a passenger survived or not.

This project demonstrates a complete **end-to-end data science workflow**, including data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

---

Problem Statement

Can we predict whether a passenger survived the Titanic disaster based on features like age, gender, class, and fare?

---

Dataset Information

The dataset contains passenger details such as:

* Passenger Class (Pclass)
* Gender (Sex)
* Age
* Fare
* Embarked Port
* Survival (Target Variable)

---

Approach

🔹 Data Preprocessing

 Handled missing values:

* Age → filled using median
* Embarked → filled using mode
* Dropped Cabin column due to excessive missing values
* Converted categorical features into numerical values

🔹 Exploratory Data Analysis (EDA)

* Survival distribution analysis
* Gender vs Survival comparison
* Feature relationship visualization

🔹 Model Building

* Used **Logistic Regression** for binary classification
* Split dataset into:

  * 80% Training
  * 20% Testing

---

Results

* Model Accuracy: **~79%**
* Confusion Matrix used for evaluation
* Key Insight:

  * Female passengers had a significantly higher survival rate than male passengers
  * Passenger class also influenced survival probability

---

Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---
Project Structure

Titanic-Survival-Predictor/
│
├── data/
│   └── titanic.csv
│
├── notebooks/
│   └── titanic_survival_prediction.ipynb
│
├── report/
│   └── Titanic_Survival_Predictor_Report.pdf
│
├── README.md
└── requirements.txt

---

How to Run

1: Clone the repository:

git clone <https://github.com/Karthikadevi-R09/Machine_learning-Projects.git>

2: Navigate to the project folder:

cd Titanic-Survival-Predictor

3: Install dependencies:

pip install -r requirements.txt

4: Run the Jupyter Notebook:

jupyter notebook

---

Future Improvements

* Implement advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Build a web app using Streamlit
* Deploy the model for real-time predictions

---

Key Takeaways

* Demonstrates practical application of machine learning
* Shows data preprocessing and feature engineering skills
* Highlights ability to extract insights from data

---

Author

Karthikadevi R
Artificial Intelligence & Data Science Student

---

⭐ If you found this project useful, feel free to star the repository!
