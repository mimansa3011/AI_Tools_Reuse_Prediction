# Predicting Student Reuse of AI Assistant Tools using Machine Learning

##  Project Overview

This project aims to predict whether students will reuse an AI assistant after their initial interaction. With the increasing use of AI tools in education, understanding reuse behavior is important for improving tool design and long-term adoption.

Using machine learning models, this project analyzes student session data to identify patterns that indicate whether a student is likely to return to an AI assistant.

---

##  Objectives

* Predict student reuse behavior (Yes/No) using machine learning
* Compare the performance of different ML models
* Understand the limitations of predicting human behavior using session-level data

---

##  Dataset Description

The dataset contains information related to student interactions with an AI assistant, including:

* StudentLevel (academic level)
* Discipline (field of study)
* TaskType (purpose of AI usage)
* SessionLengthMin
* AI_AssistanceLevel
* SatisfactionRating
* UsedAgain (target variable)

---

##  Data Preprocessing

The following preprocessing steps were applied:

* Removal of irrelevant and redundant columns
* Handling missing and duplicate values
* Log transformation of skewed numerical features
* Outlier removal using IQR method
* Encoding categorical variables
* Scaling numerical features

These steps helped improve model stability and performance.

---

##  Models Used

Three machine learning models were trained and evaluated:

* **Logistic Regression**
* **Random Forest**
* **XGBoost**

Hyperparameter tuning was performed using GridSearchCV to obtain the best version of each model.

---

##  Model Evaluation

Models were evaluated using multiple metrics:

* Accuracy
* Precision
* Recall
* Confusion Matrix

The best model achieved an accuracy of approximately **72%**, indicating moderate predictive performance.

---

##  Results & Observations

* All models showed similar accuracy, highlighting the difficulty of predicting human decisions.
* The results suggest that session-level data alone may not fully explain reuse behavior.
* Predictive performance could improve with richer behavioral and contextual features.

---

##  Technologies & Libraries Used

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn

---

##  Conclusion

This project demonstrates that machine learning can provide useful insights into student reuse of AI assistants, but predicting human behavior remains challenging. The findings serve as a baseline for future research using more detailed behavioral and contextual data.

---

##  Future Work

* Include behavioral and psychological features (motivation, mood, learning context)
* Use longitudinal data for long-term usage patterns
* Explore advanced models and deep learning approaches

---

##  Author

**Mimansa Chhabra**

Internship Project | Machine Learning

---
