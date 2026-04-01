# Netflix Data Analysis & Predictive Classification

## Project Overview

This project analyzes Netflix content data to identify patterns in content distribution and builds a machine learning model to classify titles as Movies or TV Shows.

The work combines exploratory data analysis and predictive modeling to understand how features such as release year, genre diversity, and rating influence content classification.

---

## Objectives

* Perform data cleaning and preprocessing
* Analyze content trends using visualizations
* Engineer meaningful features
* Build classification models
* Evaluate model performance

---

## Dataset

* Source: Netflix Titles Dataset (Kaggle)
* Includes information such as:

  * Content type (Movie / TV Show)
  * Genre
  * Release year
  * Rating
  * Cast, director, and country

---

## Data Preprocessing

* Handled missing values using appropriate replacements
* Removed incomplete records
* Encoded categorical variables for model compatibility

---

## Exploratory Data Analysis

Key observations:

* Movies dominate Netflix content compared to TV shows
* Content production increased significantly after 2015
* Drama and international genres are most frequent
* Growth trend reflects Netflix’s global expansion

---

## Feature Engineering

The following features were created:

* `genre_count`: Number of genres associated with each title
* `title_length`: Length of the title text
* `is_recent`: Indicator for content released after 2015

---

## Model Building

Two machine learning models were implemented:

* Decision Tree Classifier
* Logistic Regression

---

## Model Evaluation

* Logistic Regression achieved slightly better performance than Decision Tree
* Accuracy of approximately 71%
* Confusion matrix indicates stronger prediction performance for Movies than TV Shows

---

## Feature Importance

Analysis shows that release year and genre diversity significantly influence classification, highlighting the importance of temporal trends and content variety.

---

## Real-World Relevance

This project demonstrates how data analysis and machine learning can support streaming platforms in:

* Improving recommendation systems
* Optimizing content acquisition strategies
* Enhancing user engagement

---

## Limitations

* Limited feature set used for modeling
* No user engagement data included (e.g., view counts, user ratings)
* Model performance can be improved with more advanced techniques

---

## Future Improvements

* Apply advanced models such as Random Forest or XGBoost
* Incorporate additional features like duration and country
* Extend the project to a recommendation system

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Conclusion

This project demonstrates an end-to-end data science workflow, including data preprocessing, visualization, feature engineering, and predictive modeling on a real-world dataset.
